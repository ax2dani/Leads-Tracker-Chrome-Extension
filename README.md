-----

## Chrome Extension: Lead Tracker

This project is a simple Chrome extension that helps you save and manage your web page links (leads). You can manually input URLs or automatically save the URL of your current active tab. All your saved leads are persistently stored using local storage.

-----

### Features:

  * **Save Input:** Manually type and save any URL into your list.
  * **Save Tab:** Instantly save the URL of the currently active browser tab with a single click.
  * **Delete All:** Clear all saved leads from your list with a double-click.
  * **Persistent Storage:** All your leads are saved in your browser's local storage, meaning they'll still be there even after closing and reopening your browser.
  * **Clickable Links:** Saved leads are displayed as clickable links, opening in a new tab for convenience.
  * **Clean UI:** A straightforward and easy-to-use interface.

-----

### How to Use:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/YourUsername/LeadTracker.git
    ```
2.  **Open Chrome Extensions:**
      * Open your Chrome browser.
      * Type `chrome://extensions` in the address bar and press Enter.
3.  **Enable Developer Mode:**
      * Toggle on "Developer mode" in the top right corner of the Extensions page.
4.  **Load Unpacked:**
      * Click the "Load unpacked" button.
      * Select the **`LeadTracker`** folder (the root directory of this project) that you cloned.
5.  **Pin the Extension (Optional but Recommended):**
      * Click the puzzle piece icon (Extensions) in your Chrome toolbar.
      * Find "Lead Tracker" and click the pin icon next to it to make it easily accessible.
6.  **Start Saving Leads\!**
      * Click the extension icon in your toolbar.
      * **To save a typed URL:** Enter the URL in the input field and click "SAVE INPUT".
      * **To save the current tab:** Click "SAVE TAB".
      * **To delete all leads:** Double-click "DELETE ALL".

-----

### Technologies Used:

  * **HTML:** For the structure of the extension's pop-up.
  * **CSS:** For styling the extension's interface.
  * **JavaScript:** For handling user interactions, saving/retrieving data from local storage, and interacting with the Chrome Tabs API.

-----
