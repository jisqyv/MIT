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
    text: Our platform was designed and built by the world leading cryptographers and security specialists because we believe that often the most valuable data is too sensitive to disclose.  

    actions:
      - title: Get Started!
        url: '#page-top'
        class: btn-light

  - type: security.html
    section_id: secure
    #background_style: bg-info
    title: At Your Service
    secured:
      - title: Secure computation
        text: '[Why the computation is secure]
		Quantum-secure cryptographic protocols
		Local public/private key generation
		Ability to do integrity tests on the solutions'
        icon: fa-gem text-info

      - title: Secure network 
        text: '[How we have secured the network]
		- Data leaving your site is always securely encrypted.
		- Computation data (multiple encryption layers)
		- Public key (single encryption layer)'
        icon: fa-paper-plane text-info
      - title: Review & audit our code 
        text: We believe that firms should be able to audit our code to ensure that their data is handled correctly and safely. Computation participants get access to our code to review for themselves. 
        icon: fa-laptop-code text-info
     


  - type: aside.html
    section_id: aside
    title: >- 
	The SCRAM computation platform consists of three main elements: a central server, software clients, and a communication network to pass encrypted data between the clients and the server. The central server manages the data collection from the clients and hosts the core cryptographic software that performs only pre-defined and approved computations on the encrypted data. It is also responsible for piecing together and redistributing the joint public key that is used by the clients to encrypt any data for the computation.
	>- 
	The individual software clients create public/private key pairs on the local machine and enable the input of data, its encryption, and the communication back and forth with the server. The individual clients also play a vital role in decrypting the encrypted result of the computation run by the server. If firms wish to have an additional security guarantee, they can compile the joint public key for the computation individually by using the public keys of every other participant as well as their own. This ensures that the joint public key was generated correctly, that is, the data encrypted with this key can only be decrypted if the firm's own private key (which it controls) is used in the distributed decryption process.
	>- 
	The computation requires a network to pass information back and forth to perform the operations on the encrypted data. The only data ever transmitted over the network is either strongly encrypted or is the public key of the clients, which can only be used to encrypt data, not decrypt it. The network uses TLS (Transport Layer Security) for a second layer of encryption to protect the encrypted data in transit.
	
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
