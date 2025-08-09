# Minimal Firefox Setup

A lightweight customization for Firefox using a single `userChrome.css` file to keep the browser interface clean and distraction-free.

---

## ✨ Features
- Minimal, clutter-free UI  
- Maximized screen space  
- Simple, editable CSS  

---

## 📥 Installation
1. **Enable `userChrome.css` support**  
   - Open Firefox and go to `about:config`  
   - Search for:  
     ```
     toolkit.legacyUserProfileCustomizations.stylesheets
     ```  
   - Set it to **true**  

2. **Find your Firefox profile folder**  
   - Go to `about:support`  
   - Under **Profile Folder**, click **Open Folder**  

3. **Create the `chrome` directory**  
   - Inside your profile folder, create:  
     ```
     chrome
     ```

4. **Add the `userChrome.css` file**  
   - Place it in the `chrome` folder  

5. **Restart Firefox**  
   - Close and reopen Firefox to apply the changes  

---

## 📝 Notes
- Works on Firefox desktop versions  
- CSS is fully tweakable  
- Future Firefox updates may require small adjustments  

---

## 📜 License
MIT License
