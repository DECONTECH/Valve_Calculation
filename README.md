# Industry 4.0.
![](https://github.com/DECONTECH/Valve_Calculation/blob/main/Industry_4.jpg)

In 2006, the German government presented its “High-Tech Strategy” at Hannover Messe.

In ‘Die Neue Hightech-Strategie Innovationen für Deutschland’, the government explained how it aimed to drive innovation, which wasn’t just a matter of technological innovation but also about ‘social innovation’ with society overall put at the center.
Industrie 4.0 was first mentioned in a clear relationship with the advent of a fourth industrial revolution, driven by the Internet and the Internet of Things. The document (Germany’s High-Tech Strategy reorientation) described the characteristics of the industrial production of the future as follows:
* A high degree of individualization (personalization) of products with a highly flexible production;
* The early inclusion/involvement of customers and business partners in design and value creation processes;
* Connecting production and high-quality services which would lead to so-called hybrid products.

Five years later, in 2011, Dr. Kagermann, Dr. Wolfgang Wahlster of the German Research Center for Artificial Intelligence (DFKI) and Dr. Wolf-Dieter Lukas from the Federal Ministry of Research and Education presented the results of the work of the advisory group across various domains, including Industrie 4.0, which from then on became broadly known.

The business potential of the 4th industrial revolution lies not only in operational process optimization, but also in its services for a wide range of applications. The Internet of Things is therefore complemented by the so-called “Internet of Services”, because smart products offer their capabilities as intelligent services (Industrie 4.0: Mit dem Internet der Dinge auf dem Weg zur 4. industriellen Revolution, 2011) [Arcticle](https://github.com/DECONTECH/Valve_Calculation/blob/main/Industrie_4_0_Mit_dem_Internet_der_Dinge_auf_dem_Weg_zur_vierten_industriellen_Revolution_2.pdf)

## What is industry 4.0 ?
The initial goals in Industry 4.0 typically are automation, (manufacturing) process improvement and productivity/production optimization; the more mature goals are innovation and the transition to new business models and revenue sources with information and services as cornerstones.

Original defination of Industry 4.0 : The definition of Industrie 4.0 as proposed in 2011 was pretty lengthy. In a paper, entitled “Industrie 4.0 – Smart Manufacturing for the Future”, GTAI (Germany Trade and Invest) looked at the questions what is smart industry (a synonym of Industry 4.0) and what Industrie 4.0 means.

An extract: Smart industry or “INDUSTRIE 4.0” refers to the technological evolution from embedded systems to cyber-physical systems…INDUSTRIE 4.0 represents the coming fourth industrial revolution on the way to an Internet of Things(IoT), Data(Big Data, cloud etc) and Services. Decentralized intelligence helps create intelligent object networking and independent process management (Block chain method), with the interaction of the real and virtual worlds representing a crucial new aspect of the manufacturing and production process.

Latest developments (https://www.gtai.de/gtai-en/invest/industries/industrie-4-0/industrie-4-0-and-germany-162660#162662)

Industry 4.0 in practice means many things for many people and what some consider a definition of Industry 4.0, others won’t.

Industry 4.0 has been defined as “a name for the current trend of automation and data exchange in manufacturing technologies, including cyber-physical systems, the Internet of things, cloud computing and cognitive computing and creating the smart factory”.

----------------------------------------------------
----------------------------------------------------

Industry 4.0 is the digital transformation of Designing/manufacturing/production and related industries and value creation processes

Cyber-physical systems form the basis of Industry 4.0 (SMART MACHINES). They use modern control systems, have embedded software systems and dispose of an Internet address to connect and be addressed via IoT (the Internet of Things).
Cyber-physical systems create the capabilities needed for smart factories. These are the same capabilities we know from the Industrial Internet of Things like remote monitoring or track and trace. This way, products and means of production get networked and can ‘communicate’, enabling new ways of production, value creation, and real-time optimization.

Industry 4.0 has been defined as “a name for the current trend of automation and data exchange in manufacturing technologies, including cyber-physical systems, the Internet of things, cloud computing and cognitive computing and creating the smart factory”

Industry 4.0 is a vision that evolved from an initiative to make the German manufacturing industry more competitive (‘Industrie 4.0’) to a globally adopted term.
Industry 4.0 is often used interchangeably with the notion of the fourth industrial revolution. It is characterized by, among others,
* Even more automation than in the third industrial revolution,
* The bridging of the physical and digital world through cyber-physical systems, enabled by Industrial IoT,
* A shift from a central industrial control system to one where smart products define the production steps,
* Closed-loop data models and control systems and
* Personalization/customization of products.

The goal is to enable autonomous decision-making processes, monitor assets and processes in real-time, and enable equally real-time connected value creation networks through early involvement of stakeholders, and vertical and horizontal integration.

The fourth industrial revolution and the impact of the drivers and technologies behind Industry 4.0 have been looked at from the perspective of various sectors after the concept was launched. This has led to more ‘4.0’ terms, often based on academic work. Examples include Design 4.0 (Design and Calculation), Logistics 4.0 (logistics and transportation), Construction 4.0 (construction industry), Energy 4.0 (energy and utilities industry), and more.

At the very core Industry 4.0 includes the (partial) transfer of autonomy and autonomous decisions to cyber-physical systems and machines, leveraging information systems.

To understand Industry 4.0, it is essential to see the full value chain which includes suppliers and the origins of the materials and components needed for various forms of smart manufacturing (Enabling more direct models of personalized production, servicing, as well as customer/consumer interaction including gaining real-time data from actual product usage), the end-to-end digital supply chain (some goals of Industry 4.0 in this customer-centric sense of increasingly demanding customers who value speed, (cost) efficiencies and value-added innovative services) and the final destination of all manufacturing/production, regardless of the number of intermediary steps and players: the end customer.

In the end it involves the innovative twist of innovation and transformation of business models and processes: 
- increase profit, 
- decrease costs, 
- enhance customer experience, 
- optimize customer lifetime value and where possible customer loyalty, .
- sell more, 
- innovate to grow and remain relevant

Here we use the open source tool to make create the automation in the calculation and automation.
Calcualtion of the valve design in done using the Octave (https://en.wikipedia.org/wiki/GNU_Octave)

1. **Encoder**: This is the part of the network that compresses the input into a latent-space representation. It can be represented by an encoding function _h=f(x)_.
2. **Decoder**: This part aims to reconstruct the input from the latent space representation. It can be represented by a decoding function _r=g(h)_.

<img src="https://nathanhubens.github.io/posts/images/autoencoders/AE.png" alt="drawing" width="750"/>

This notebook show the implementation of five types of autoencoders :

* Vanilla Autoencoder
* Multilayer Autoencoder
* Convolutional Autoencoder
* Regularized Autoencoder
* Variational Autoencoder

The explanation of each (except VAE) can be found [here](https://towardsdatascience.com/deep-inside-autoencoders-7e41f319999f)
