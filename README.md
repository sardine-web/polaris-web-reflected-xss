# polaris-web-reflected-xss

An attacker can inject his own malicious JavaScript code into vulnerable parameters and can also perform various actions, such as stealing the victim's session token or other users' login credentials.

To use this Nuclei template, follow these steps:

    Ensure you have Nuclei installed. If not, you can install it from Nuclei GitHub.
    Save the provided template as polaris-web-reflected-xss.yaml.
    Run Nuclei with the template against your target:


nuclei -t /path/to/polaris-web-reflected-xss.yaml -u https://example.com

Replace https://example.com with the URL of your target.
Disclaimer

This template is intended for educational purposes only. Testing for vulnerabilities should only be performed on systems you have explicit permission to test
