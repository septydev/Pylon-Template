# Pylon - Minecraft Server Website Template

Pylon is a free, modern, and fully responsive website template designed for Minecraft servers. It provides a sleek and professional landing page to showcase your server's features, community links, and live status.

![Pylon Website Screenshot](https://imgur.com/a/TMJ3ZOe) 

## Features

*   **Live Server Status:** Automatically fetches and displays your server's status (Online/Offline) and current player count using the [mcsrvstat.us](https://mcsrvstat.us/) API.
*   **Modern Design:** A dark, futuristic theme with custom fonts and a pylon-inspired logo.
*   **Responsive:** Looks great on all devices, from desktops to mobile phones, thanks to the Bootstrap 5 framework.
*   **Easy to Customize:** Simple HTML and CSS structure, making it easy to change the server name, description, and links.
*   **Feature Sections:** Pre-built sections to highlight your server's unique features, such as custom worlds, plugins, and community aspects.
*   **Community Links:** Prominently features buttons for your Discord and Twitter/X accounts.

## How to Use

1.  **Download or Clone:** Get the files from this repository.
2.  **Customize `index.html`:**
    *   **Server Name:** Find all instances of `SERVER NAME` and `servername.com` and replace them with your actual server name and address.
        *   In the `<title>` tag.
        *   In the hero section (`<h1>`).
        *   In the server status box (`play.servername.com`).
        *   In the community section (links to social media).
    *   **Description:** Edit the `<p class="lead">` text to describe your server.
    *   **Features:** Update the feature cards with your server's specific details.
    *   **Community Links:** Change the `href` attributes for the Discord and Twitter/X buttons to your own links.
3.  **Customize `style.css` (Optional):**
    *   The CSS is well-commented. You can change the color scheme by modifying the `:root` variables (e.g., `--pylon-accent`).
4.  **Upload to a Web Host:** Upload the `website` directory to any static web hosting service (like GitHub Pages, Netlify, Vercel, or a traditional web host).

## Files

*   `website/index.html`: The main HTML file. This is where you'll make most of your changes.
*   `website/style.css`: The stylesheet for the template. Contains all the custom styling.

## Credits

*   **Template Design:** Septy
*   **Framework:** [Bootstrap](https://getbootstrap.com/)
*   **Icons:** [Bootstrap Icons](https://icons.getbootstrap.com/)
*   **Fonts:** [Google Fonts](https://fonts.google.com/) (Roboto, Orbitron)
*   **Server Status API:** [mcsrvstat.us](https://mcsrvstat.us/)
