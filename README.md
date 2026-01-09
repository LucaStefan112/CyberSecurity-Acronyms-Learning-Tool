# Security+ Acronym Trainer

An interactive web application for studying and memorizing Security+ certification acronyms. This tool helps you learn 136+ essential cybersecurity acronyms through a simple, distraction-free flashcard interface.

## Features

- **136+ Security+ Acronyms**: Comprehensive collection covering all major Security+ exam domains
- **Two-Step Learning Process**: 
  1. First, see the acronym
  2. Then reveal the full name and description
- **Keyboard Navigation**: Use Enter or Space to reveal and navigate
- **Clean, Modern UI**: Dark theme designed for focused study sessions
- **Detailed Descriptions**: Each acronym includes a concise explanation of its purpose and importance

## How to Use

1. **Open the Application**: Simply open `index.html` in your web browser
2. **Study the Acronym**: The current acronym is displayed prominently
3. **Reveal the Answer**: 
   - Click on the acronym, or
   - Press **Enter** or **Space**
4. **View Details**: The full name and description will appear
5. **Next Acronym**: Press **Enter** or **Space** again (or click) to move to the next random acronym

## File Structure

```
Security+ Acronyms/
├── index.html          # Main application file
├── acronyms.json       # Database of acronyms with names and descriptions
└── README.md          # This file
```

## Acronym Categories

The application covers all major Security+ domains:

- **Access Control**: AAA, ABAC, ACL, DAC, MAC, RBAC, IAM, PAM
- **Cryptography**: AES, DES, 3DES, RSA, SHA, HMAC, PKI, TLS
- **Network Security**: VPN, DMZ, NAC, NGFW, WAF, IDS, IPS, SIEM
- **Cloud Security**: CASB, CSP, IaaS, PaaS, SaaS, VPC, SASE
- **Compliance**: GDPR, HIPAA, PCI DSS, SOX
- **Incident Response**: IR, IRP, IOC, SIEM, SOAR, SOC
- **Application Security**: OWASP, SAST, DAST, XSS, CSRF, SQLi
- **Risk Management**: ALE, ARO, EF, BIA, CVSS, RTO, RPO
- **And many more...**

## Technical Details

- **Pure HTML/CSS/JavaScript**: No dependencies or build process required
- **JSON Data Format**: Easy to extend with additional acronyms
- **Responsive Design**: Works on desktop and mobile browsers
- **Local Storage**: No data is sent to external servers

## Adding More Acronyms

To add more acronyms, edit `acronyms.json` and add entries in this format:

```json
{
  "acronym": "NEW",
  "name": "New Example Acronym",
  "description": "Brief description of what this acronym means and why it's important"
}
```

The acronyms are automatically loaded in random order when the page loads.

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Opera

## License

This project is open source and available for personal and educational use.

## Contributing

Feel free to add more Security+ acronyms or improve the application. Simply edit the `acronyms.json` file to add new entries.

---

**Good luck with your Security+ certification exam!** 🎓
