Language: [FA](https://github.com/insektdotbin/Tor2DNS/blob/main/README-FA.md)/[EN](https://github.com/insektdotbin/Tor2DNS/blob/main/README.md)

# ☁️ Tor2DNS 

![Tor2DNS-BGRM](https://github.com/user-attachments/assets/44c448fa-627d-424e-8c28-e006fb6de787)

**🌐 Tor2DNS** is a simple command-line script that transforms your Tor proxy into a DNS resolver, utilizing Cloudflare's DNS service. This tool is designed to enhance your online privacy by routing DNS queries through the Tor network.

Tor2DNS executes instructions based on [Cloudflare's DNS-Over-Tor](https://developers.cloudflare.com/1.1.1.1/other-ways-to-use-1.1.1.1/dns-over-tor/).

## ⚙️ Version 

**Tor2DNS Version:** 1.0

## ⭐ Features 

- Convert your Tor proxy into a DNS resolver.
- Utilizes Cloudflare's DNS service for enhanced privacy.
- User-friendly command-line interface with colorful output.
- Supports both Windows and Linux environments.

## 📦 Installation 

To get started with Tor2DNS, you'll need to clone the repository and install the required dependencies. You can do this using the following commands:

```bash
# Clone the repository
git clone https://github.com/insektdotbin/Tor2DNS.git

# Navigate into the project directory
cd Tor2DNS

# Install the required packages
pip install -r requirements.txt
```

## 💻 Usage 

To run the script, use the following command:

```bash
python3 main.py
```

## 🧑‍💻 Author 

This project is maintained by [@insektdotbin](https://github.com/insektdotbin) 

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Notes and Cautions:

- Ensure that the `requirements.txt` file is present in your repository and contains all the necessary dependencies.
- **ALERT: The script may require root or administrator permissions to execute tasks and can pose risks on non-Debian-based operating systems. Misconfigurations or operating system conflicts can lead to system or network failures. The developer will not be held responsible for any resulting damages.**

- **The script is compatible only with Python versions 3.9.x to 3.11.x**