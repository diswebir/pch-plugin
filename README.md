# PCH Plugins

**Plugin Name:** PCH Plugins  
**Plugin URI:** [https://disweb.ir/](https://disweb.ir/)  
**Description:** A WordPress plugin that enhances security and customization by allowing you to change the login page logo, modify the admin panel font, disable the plugin and theme editor to prevent potential hacks, block external link requests, and disable automatic updates.  
**Version:** 1.2  
**Author:** Reza_pch  
**Author URI:** [https://disweb.ir/](https://disweb.ir/)  

---

## Features

### 1. **Custom Login Logo**  
Easily change the logo on the WordPress login page to match your website’s branding.

### 2. **Admin Panel Font Customization**  
Personalize the font used in the WordPress admin dashboard for a unique and cohesive experience.

### 3. **Disable Plugin and Theme Editors**  
Prevent access to the plugin and theme file editors, protecting your site from unauthorized modifications and potential security vulnerabilities.

### 4. **Block External Link Requests**  
Block all external HTTP connections and only allow access to trusted domains such as `wordpress.com`, `google.com`, and other approved hosts.

### 5. **Disable Auto Updates for Plugins and Themes**  
Turn off automatic update checks for plugins and themes to prevent unwanted or unapproved changes.

### 6. **Disable Gutenberg Editor & Enable Classic Editor**  
For users who prefer the classic WordPress editor, this plugin disables the Gutenberg editor and switches to the traditional editor for administrators.

### 7. **Hide Unnecessary Admin Menu Items**  
Hide specific menu items and tools in the WordPress admin area to streamline the user interface and improve workflow.

---

## Installation

1. **Upload the Plugin Files**  
   Upload the plugin folder to the `/wp-content/plugins/` directory of your WordPress installation.

2. **Activate the Plugin**  
   Go to **Plugins > Installed Plugins** in your WordPress dashboard and activate the **PCH Plugins** plugin.

3. **Configure the Plugin**  
   Once activated, you can configure the plugin via the provided code or adjust settings to suit your needs.

---

## Usage

### Custom Login Logo  
To change the login logo, simply add the provided code to your `functions.php` file or modify the plugin settings. The logo will be updated automatically upon activation.

### Admin Panel Font Customization  
The font changes will be applied as soon as the plugin is activated. You can modify the font styles to fit your desired appearance for the admin dashboard.

### Block External Link Requests  
To block external link requests, you can add your desired domains to the plugin code. This helps in enhancing security by preventing unauthorized external requests.

---

## Hooks and Filters

This plugin utilizes various WordPress hooks and filters to implement its functionality:

- **`admin_head`**: Injects custom styles into the WordPress admin panel for customization.
- **`wp_enqueue_scripts`**: Adds styles and scripts to be used on the site front end.
- **`login_enqueue_scripts`**: Adds styles specifically for the login page.
- **`use_block_editor_for_post`**: Disables the Gutenberg editor and switches to the classic editor for administrators.

---

## Support

If you need support or have any questions, please feel free to reach out through my website: [https://disweb.ir/](https://disweb.ir/).

---

## License

This plugin is released under the GPL-2.0 or later license.
