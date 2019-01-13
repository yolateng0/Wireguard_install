# Wireguard_install
Install Wireguard VPN + Locate the proper resolv.conf from /etc/resolv.conf

# Usage

Run the script and follow the assistant:

> wget https://raw.githubusercontent.com/yolateng0/Wireguard_install/master/install.sh -O install.sh

> bash install.sh

Once it ends, you can run it again to add more users. Reboot your server to apply all settings.
> sudo reboot

# Resume

WireGuard® is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPSec, while avoiding the massive headache. It intends to be considerably more performant than OpenVPN. WireGuard is designed as a general purpose VPN for running on embedded interfaces and super computers alike, fit for many different circumstances. Initially released for the Linux kernel, it is now cross-platform and widely deployable. It is currently under heavy development, but already it might be regarded as the most secure, easiest to use, and simplest VPN solution in the industry.

 Simple & Easy-to-use
WireGuard aims to be as easy to configure and deploy as SSH. A VPN connection is made simply by exchanging very simple public keys – exactly like exchanging SSH keys – and all the rest is transparently handled by WireGuard. It is even capable of roaming between IP addresses, just like Mosh. There is no need to manage connections, be concerned about state, manage daemons, or worry about what's under the hood. WireGuard presents an extremely basic yet powerful interface.

 Cryptographically Sound
WireGuard uses state-of-the-art cryptography, like the Noise protocol framework, Curve25519, ChaCha20, Poly1305, BLAKE2, SipHash24, HKDF, and secure trusted constructions. It makes conservative and reasonable choices and has been reviewed by cryptographers.

 Minimal Attack Surface
WireGuard has been designed with ease-of-implementation and simplicity in mind. It is meant to be easily implemented in very few lines of code, and easily auditable for security vulnerabilities. Compared to behemoths like *Swan/IPsec or OpenVPN/OpenSSL, in which auditing the gigantic codebases is an overwhelming task even for large teams of security experts, WireGuard is meant to be comprehensively reviewable by single individuals.

 High Performance
A combination of extremely high-speed cryptographic primitives and the fact that WireGuard lives inside the Linux kernel means that secure networking can be very high-speed. It is suitable for both small embedded devices like smartphones and fully loaded backbone routers.

 Well Defined & Thoroughly Considered
WireGuard is the result of a lengthy and thoroughly considered academic process, resulting in the technical whitepaper, an academic research paper which clearly defines the protocol and the intense considerations that went into each decision.



# Sources

https://wireguard.org

https://github.com/l-n-s/wireguard-install

https://github.com/angristan/openvpn-install/blob/master/openvpn-install.sh
