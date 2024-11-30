# Password Generator with Strength and Vulnerability Analysis

This is a **Password Generator Web Application** designed to create secure and customizable passwords. It also provides feedback on password strength by estimating the time it would take to crack the password through brute force. Additionally, it integrates with the **Have I Been Pwned API** to check if the password has been exposed in any data breaches.

## Key Features

1. **Dynamic Password Generation**:
   - Customizable length (6 to 50 characters).
   - Options to include uppercase letters, numbers, and symbols.
   - Platform presets (e.g., Google, Facebook) for quick configuration.

2. **Password Strength Analysis**:
   - Displays the estimated time to crack the password using brute force, considering modern computational speeds.

3. **Vulnerability Check**:
   - Uses the [Have I Been Pwned API](https://haveibeenpwned.com/) to determine if the generated password has been compromised in a known data breach.

4. **Copy to Clipboard**:
   - Easily copy the generated password with one click.

5. **Responsive and Modern Design**:
   - Built with a clean, dark-themed UI and animated particle effects using **particles.js** for a sleek user experience.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/santospt77/Advanced-Password-Generator.git
   cd advanced-password-generator
   ```
2. Open `index.html` in your browser.
3. Customize the password options:
   - Set the desired length using the slider.
   - Toggle options for uppercase letters, numbers, and symbols.
   - Choose a platform for predefined configurations.
4. Click **"Generate Password"** to create a secure password.
5. Use **"Copy Password"** to copy it to your clipboard.
6. Check password vulnerability by clicking **"Check Vulnerability"**.

## File Structure

```
password-generator/
├── index.html         # Main HTML file
├── style.css          # CSS styles (inline within HTML for this project)
├── script.js          # JavaScript logic (inline within HTML for this project)
└── README.md          # Documentation
```

## Future Improvements

- **Enhanced Strength Feedback**:
  - Add more detailed feedback on password strength (e.g., entropy calculation).
- **Offline Mode**:
  - Make the app fully functional without an internet connection.
- **Password Export**:
  - Allow users to save generated passwords securely.

## Contributing

Contributions are welcome! If you'd like to improve this project:
1. Fork the repository.
2. Create a new branch (`feature/improvement-name`).
3. Commit your changes.
4. Open a pull request.

---

Made with ❤️ by **Daniel Santos**.
