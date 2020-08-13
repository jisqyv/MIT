---
layout: page
header:
  title: TECHNOLOGY
  text: >
    Cybersecurity benchmarking and ROI analytics without own-data disclosure
  action: # action button is optional
    label: Find Out More
    url: '#about'


sections:
  - type: call-to-action-technology.html
    section_id: about
    background_style: bg-primary
    title: Technology
    text: 'Our new data analytics platform uses blind computations so firms never need to disclose their own data. Read about the technology and view our code below.'

    actions:
      - title: Get Started!
        url: '#page-top'
        class: btn-light

  - type: technologyservices.html
    section_id: technologyservicesservice
    #background_style: bg-info
    title: Background
    technologytxt:
        text: 'Traditionally, when members of a group want to learn about trends across their membership without revealing information to other members in the group, they need to select a trusted third party. This third party will gather data from all the participants, pool it, run computations on the data to produce summary statistics and analysis, and then send only the results back to all the participants in the pool. The third party needs to be trusted because it can view the data sent in by all the participants. Individual participants cannot see the inputs of other contributors, but the trusted third party can see everything. The process works well when participants are comfortable sharing their information with the third party (a risk) in exchange for learning more about the dynamics of the group (a benefit). 
        
		But what if participants are unwilling to reveal sensitive data to even a trusted third party? Secure multi-party computation (MPC) offers the same functionality as the data pool described above, but without requiring a trusted third party to see the data. This is possible due to a combination of the mathematical properties of encrypted data and clever structuring of the computations.    
        
		SCRAM mimics the traditional aggregation technique, but works exclusively on encrypted data that it cannot see. The system takes in encrypted data from the participants, runs a blind computation on it, and returns an encrypted result that must be unlocked by each participant separately before anyone can see the answer. The security of the system comes from the requirement that the keys from all the participants are needed in order to unlock any of the data. Participants guarantee their own security by agreeing to unlock only the result using their privately held key. 
 
	Cryptographic tools such as multi-party computation and public key cryptography provide a way to perform mathematical operations on encrypted data without ever exposing the underlying data. While there are a variety of solutions to the challenge of secure computation, we choose an approach for SCRAM that provides simple, straightforward security guarantees as well as support for complex computation. The steps of our computations are provided below:'   


     
  - type: aside-technology.html
    section_id: aside
    title: Our Proccess
    actions:
      - title: Read our research
        url: '/MIT/research'
        class: btn-light
      - title: Understand our security 
        url: '/MIT/security'
        class: btn-light
      - title: Evaluate our code 
        url: 'https://github.com/CSAIL/ipri-scram'
        class: btn-light
  
---
