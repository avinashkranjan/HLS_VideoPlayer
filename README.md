# Embeddable HLS Video Player with Subtitles

An easy-to-use and customizable HLS video player designed to be embedded via an iframe in any project. This player supports dynamic video and subtitle URLs, playback speed control, and responsive design.

## Features

- **HLS Video Playback**: Compatible with HLS video streams using `hls.js`.
- **Subtitles Support**: Add WebVTT subtitles dynamically via URL.
- **Playback Speed Control**: Adjust playback speed directly from the player.
- **Responsive Design**: The player adjusts to various screen sizes.
- **Embeddable**: Easily integrate the player into any project using an iframe.

## Demo

Embed the player with a video and subtitles:

```html
<iframe 
  src="https://your-hosted-url/iframe-player.html?video=https://test-streams.mux.dev/x36xhzz/x36xhzz.m3u8&subtitle=https://example.com/subtitles.vtt" 
  width="800" 
  height="450" 
  style="border: none;" 
  allowfullscreen>
</iframe>
```

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/embeddable-hls-player.git
   cd embeddable-hls-player
   ```

2. Host the `iframe-player.html` file:
   - Use a static hosting service like [GitHub Pages](https://pages.github.com/), [Vercel](https://vercel.com/), or [Netlify](https://www.netlify.com/).
   - Alternatively, serve it locally with any web server (e.g., [http-server](https://www.npmjs.com/package/http-server)):
     ```bash
     npx http-server
     ```

3. Use the hosted URL in your iframe's `src` attribute.

## Query Parameters

The player accepts the following query parameters:

| Parameter   | Description                      | Example                                        |
|-------------|----------------------------------|------------------------------------------------|
| `video`     | URL of the HLS video source      | `https://example.com/video.m3u8`              |
| `subtitle`  | URL of the WebVTT subtitle file | `https://example.com/subtitles.vtt`           |

## Usage

To embed the player in your project, use the following iframe code:

```html
<iframe 
  src="https://your-hosted-url/iframe-player.html?video=VIDEO_URL&subtitle=SUBTITLE_URL" 
  width="800" 
  height="450" 
  style="border: none;" 
  allowfullscreen>
</iframe>
```

Replace:
- `VIDEO_URL` with the URL of your HLS video.
- `SUBTITLE_URL` with the URL of your WebVTT subtitle file (optional).

## Dependencies

- [Video.js](https://videojs.com/): A powerful HTML5 video player.
- [hls.js](https://github.com/video-dev/hls.js): JavaScript library for HLS playback.

## Development

To modify or extend the player:

1. Open `iframe-player.html` in a text editor.
2. Update the `script` section for additional features or customization.
3. Test the player locally or deploy it to your hosting environment.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

1. Fork the repo
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request

## License

This project is licensed under the [MIT License](LICENSE).

## Screenshots

### Player Interface
<img width="1680" alt="Player Interface" src="https://github.com/user-attachments/assets/7f46c0b4-be35-44e1-89a1-632bdea571d0">


### Embedded Example
<img width="435" alt="Embedded Example" src="https://github.com/user-attachments/assets/24ef8d74-f996-4dce-9b94-552e440810ce">

---

## Acknowledgments

- Built with [Video.js](https://videojs.com/) and [hls.js](https://github.com/video-dev/hls.js).
- Inspired by the need for a lightweight, embeddable video player with modern features.
```

### Instructions for Hosting
- Replace `https://your-hosted-url/` with the actual URL where the `iframe-player.html` file is hosted.
- Use the player wherever required

