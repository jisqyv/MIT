---
layout: page
header:
  title: Security
  text: >
    Start Bootstrap can help you build better websites using the Bootstrap
    framework! Just download a theme and start customizing, no strings attached!
  action: # action button is optional
    label: Find Out More
    url: '#about'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: 
    text: Our platform was designed and built by world-leading cryptographers and security specialists because we believe that often the most valuable data is too sensitive to disclose.     


  - type: security.html
    section_id: product
    #background_style: bg-info
    title: At Your Service
    product:
      - title: Secure computation
        text: '[Why the computation is secure]
		<br> Quantum-secure cryptographic protocols
		<br> Local public/private key generation
		<br> Ability to do integrity tests on the solutions'
        icon: fa-gem text-info

      - title: Secure network 
        text: 'The computation requires a network to pass information back and forth to perform the operations on the encrypted data. The only data ever transmitted over the network is either strongly encrypted or is the public key of the clients, which can only be used to encrypt data, not decrypt it. The network uses TLS (Transport Layer Security) for a second layer of encryption to protect the encrypted data in transit. We take additional measures to ensure the security of the network and your data. '
        icon: fa-paper-plane text-info
      - title: Review & audit our code 
        text: We believe that firms should be able to audit our code to ensure that their data is handled correctly and safely, so <a href="https://github.com/CSAIL/ipri-scram" target="_blank">we publish the source code</a>
        icon: fa-laptop-code text-info
     


  - type: securityaside.html
    section_id: aside
    title: Secure & private data aggregation and computation using cryptographic tools built by MIT experts. 
    actions:
      - title: Dig deeper into the technical details
        url: '#'
        class: btn-light



  - type: contact.html
    section_id: contacts
    title: Let's Get In Touch!
    text: >-
      Ready to start your next project with us? Give us a call or send us an email
      and we will get back to you as soon as possible!
    actions:
    - title: +1 617 258 6392
      icon: fa-phone
    - title: scram@mit.edu
      icon: fa-envelope
      url: mailto:contact@scram@mit.edu
    - title: 32 Vassar Street Cambridge, MA 02139 USA
      icon: fa-map

---
