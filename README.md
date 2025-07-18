# OBS Spotify Widget

A simple widget to display the currently playing Spotify song from a Discord user's activity in OBS.

## Features

- Displays the album art, song title, and artist name.
- Dynamically adjusts the widget size based on the length of the song title.
- Uses a blurred version of the album art as a background.
- Optimized for use as an OBS browser source.

## Prerequisites

- OBS Studio
- A Discord account
- A Lanyard API key (This is not actually needed, Lanyard is public)

## Setup

1.  **Create a new HTML file** (e.g., `index.html`) in your project directory.
2.  **Copy the code** from the provided `index.html` into your new file.
3.  **Replace the `discord_id`** variable in the JavaScript section with your Discord user ID.
4.  **Open OBS Studio.**
5.  **Add a "Browser Source".**
6.  **Set the "Local file"** option and browse to your `index.html` file.
7.  **Adjust the width and height** of the browser source in OBS to fit your needs. A good starting point is 300x100.
8.  **Customize the CSS** in the `index.html` file to match your desired style.

## Customization

You can customize the appearance of the widget by modifying the CSS in the `<style>` section of the `index.html` file. Here are some things you can change:

-   **Fonts:** Change the `font-family` property to use a different font.
-   **Colors:** Modify the `color` properties to change the text color.
-   **Background:** Adjust the `background` and `opacity` properties to change the background appearance.
-   **Image Size:** Change the `max-width` and `max-height` properties of the `img` element to adjust the size of the album art.
-   **Text Size:** Modify the `font-size` property of the `p` element to change the text size.

## Notes

-   The widget updates every 10 seconds. You can change the update interval by modifying the `setInterval` function in the JavaScript section.
-   The widget uses the Lanyard API to fetch the Spotify data from Discord.

## Example

![OBS Spotify Widget Example](https://i.imgur.com/YOUR_IMAGE_HERE.png)

## Contributing

Feel free to contribute to this project by submitting pull requests.

## License

[MIT](LICENSE)
