## 🔹 Objective
Configure and use a VPN to secure network traffic and verify changes in IP address while browsing.

## 🛠 Tools Used
- VPN Client: ProtonVPN Extension
- Browser: Firefox/Chrome
- IP Check: whatismyipaddress.com

---

## 🚀 Steps Performed

1. Created an account on ProtonVPN.
2. Downloaded and installed the VPN extension on the firefox browser.
3. Launched the extension and logged into the ProtonVPN dashboard.
4. Selected and connected to a recommended server.
5. Verified that the public IP address changed using an IP-lookup site.
6. Browsed multiple websites to confirm encrypted traffic while VPN was active.
7. Disconnected and compared:
   - IP location returned to original
   - Browsing latency slightly increased (expected behavior)

---

## 🔍 Observations

| Criteria | Without VPN | With VPN |
|---------|-------------|----------|
| Public IP | Local ISP IP | Changed to VPN server country |
| Traffic Encryption | No tunnel | Encrypted via VPN tunnel |
| Speed | Normal | Slightly lower |
| Privacy Level | Low | High |

---

## 🧠 Key Takeaways

- VPN masks the real IP address and helps maintain privacy online.
- Encrypted tunneling protects against traffic interception on insecure networks.
- Speed can be affected depending on server location and load.
- VPN enhances privacy but **cannot guarantee complete anonymity** due to dependencies like websites, browser fingerprinting, and DNS leaks.

---

## 📌 Conclusion

Using a VPN significantly improves privacy by encrypting internet traffic and hiding the device’s actual IP address. It is an essential security tool for safe browsing, especially on public or untrusted networks.

---

## 📎 Files Included

- Screenshots demonstrating:
  - VPN connection status
  - Changed IP verification
