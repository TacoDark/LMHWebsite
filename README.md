# LMHWebsite
Website for a Discord modding server.

## About

Lemons Modding Hub is a mod hosting website primarily for VR games (Meta/Oculus headsets). Mods are contributed by the community, and not all mods may work for every user.

## How to Add Your Own APK

1. **Fork or Clone the Repository**
   - Fork this repo or clone it to your local machine:
     ```
     git clone https://github.com/yourusername/LMHWebsite.git
     ```

2. **Add Your Mod Entry**
   - Open `modded.html` in a code editor.
   - Copy an existing `.mod-card` block inside the `<div class="mod-list">...</div>`.
   - Update the details for your mod:
     - Change the `<h3>` title.
     - Update the tags as needed (`<span class="tag verified">Verified</span>`, `<span class="tag free">Free</span>`, etc.).
     - Edit the description and features.
     - Change the download link in the `<a href="#">Download</a>` button to your APK file or hosting location.

   **Example:**
   ```html
   <div class="mod-card">
       <h3>My Cool Mod</h3>
       <div class="tags">
           <span class="tag verified">Verified</span>
           <span class="tag free">Free</span>
       </div>
       <div style="font-size:0.95em;color:#bbb;">Modded APK for Game XYZ<br>L &bull; Last edited by YourName</div>
       <ul class="pros">
           <li>Custom skins</li>
           <li>Extra features</li>
           <li>Anti-ban</li>
       </ul>
       <div class="links">
           <a href="https://your-link.com/yourmod.apk">Download</a>
       </div>
       <div class="price paid">$0.00 <span style="font-weight:normal;">Free</span></div>
   </div>
   ```

3. **Commit and Push**
   - Save your changes.
   - Commit and push to your fork or submit a pull request if you want your mod added to the main site.

4. **Host Your APK**
   - Make sure your APK file is hosted on a reliable file-sharing service (Google Drive, Dropbox, etc.) and the link is public.

## Disclaimer

Mods are provided by the community. Use at your own risk. Not all mods are guaranteed to work or be safe.
