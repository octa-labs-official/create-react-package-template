
# ReactPlayerModal

This React component wraps the `react-player` library in a modal, allowing for a popup video player in your React applications. It is designed to be easy to integrate and customizable for different use cases.

## Installation

To install ReactPlayerModal, run the following commands in your project directory:

```bash
npm install react-player
npm install react-player-modal
```

## Usage

To use the ReactPlayerModal in your React application, import and embed it as follows:

```jsx
import ReactPlayerModal from 'react-player-modal';
import ReactPlayerProps from 'react-player';

function App() {
  const videoProps = {
    url: 'path/to/your-video.mp4', // URL of the video
    playing: true, // Autoplay video
    controls: true, // Show video controls
    // other ReactPlayer props
  };

  return (
    <div>
      <ReactPlayerModal playerProps={videoProps} />
    </div>
  );
}
```

## Props

- **playerProps** (`ReactPlayerProps`): Props for the `react-player` component, allowing for full customization of the video player.

## Features

- Simple integration with existing React applications.
- Customizable video player settings via `react-player` props.
- Modal with custom styles and close functionality.

## Contributing

If you're interested in contributing to the development of ReactPlayerModal, please fork the repository and submit a pull request. We welcome contributions that improve the component's functionality and documentation.

## License

Distributed under the ISC License. See the LICENSE file for more information.
