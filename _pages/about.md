---
permalink: /
title: "CryptoChashitsu - The cryptography tea room"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

### Updates!
I have been working as a Research Fellow at Microsoft Research Bangalore working in cryptography, mainly MPC and secure hardware (SGX), and compilers. I have been the major contributor of <a href = "https://github.com/mpc-msri/EzPC">crypTFlow</a> project and we have recently written <a href = "https://eprint.iacr.org/2019/1049.pdf">this</a> paper on our work.

I am applying for PhD programs in cryptography in Fall of 2019.

I am Mayank, a senior year undergraduate student majoring in Computer Science and Engineering from Indian Institute of Technology, Banaras Hindu University, Varanasi, India. Have been drinking the crypto elixir for more than 1.5 years now. Recently, I have been involved in homomorphic encryption and it's practical intersection with database management systems and machine learning. I have also worked extensively on packing methods for somewhat homomorphic schemes that enable us to pack input data to a valid and distinct element from the plaintext domain. Apart from this, these summers I worked at TokyoTech on Proof-of-Stake cryptocurrencies as well as hybrid and modular cryptocurrency frameworks like <a href = "https://github.com/ScorexFoundation/Scorex">Scorex</a>. As far as public key encryption and integer factorization is concerned, I have done some implementations and studied through this domain passing through the Number Field Sieve (used for solving integer factorization and discrete logarithm problems) algorithm as well. 

As a part of my Bachelor Thesis supervised by Prof. K. K. Shukla, I am working on a secure online learning protocol with encrypted querying.

Having worked with both cryptography and machine learning, building a system that facilitates both learning and prediction on encrypted datasets is the idea that most intrigues me. With present Ring-LWE based homomorphic schemes, the task of training even "just good or average" models becomes really time consuming far from being practical. Though recently Microsoft Research published their idea of performing prediction over encrypted queries using pre-trained model called CryptoNets. There are some other good and efficient solutions to secure machine learning like using secret sharing and other multi-party computation ideas. I have been working with a project called OpenMined, which envisions the same hope for the future of machine learning. I am working on creating implementations (major contributor) of core-cryptographic functions for the project and building Python APIs (check out my GitHub for the repos <a href = "https://github.com/OpenMined/PyAono">PyAono</a>, <a href = "https://github.com/OpenMined/PyBV">PyBV</a>, <a href = "https://github.com/OpenMined/PyYashe">PyYashe</a>) for the same. I have also been involved in the research that we are conducting inside this project pondering over the cryptographic challenges that we have to overcome as we proceed. Anyone who is interested in the project, please contact me and check out my GitHub.

A word of appreciation from Andrew Trask about my work can be found <a href = "https://github.com/mayank0403/mayank0403.github.io/blob/master/files/OpenMined.pdf">here</a>.

### News!

I am taking the laboratory classes of sophomore students for the course of Artificial Intelligence.

We are hosting the annual coding festival - <a href = "http://codefest.tech/">Codefest</a>, of the <a href = "http://www.iitbhu.ac.in/cse/">Department of Computer Science and Engineering, IIT (BHU), Varanasi</a> from 22-24th September 2017. I have personally set up 5-10 questions spanning cryptographic principles and cryptocurrency protocols for Capture the Flag event. Please register before the event starts on 22nd September 00:00 IST. Awesome challenging crypto single-sentence-answer questions waiting for you there.

Interested in reading about zkSNARKS? Check this awesome blog <a href = "https://media.consensys.net/introduction-to-zksnarks-with-examples-3283b554fc3b">post</a> out, along with <a href = "https://blog.ethereum.org/2016/12/05/zksnarks-in-a-nutshell/">this</a>!

Check out this <a href = "https://www.youtube.com/watch?v=jKKafEBx5P4">demo</a> of PyAono's first release. This tutorial uses a pruned space for sampling uniformly and lacks a cryptographically secure PRNG, which we will implement soon, for the sake of presentation. I have used a naive packing method in the tutorial. If an array of integers in passed, then the matrix can compute on this whole batch in one go instead of using a single integer once and then filling up the whole matrix with this integer or placing the integer at first place followed by 0s. Please check out the API description of the <a href = "https://github.com/OpenMined/PyAono">PyAono</a> repo for details about the functions.

Interesting post by a project colleague on using MPC for machine learning - <a href = "https://mortendahl.github.io/2017/04/17/private-deep-learning-with-mpc/">here</a>!

Check out my <a href = "https://mayank0403.github.io/files/twinscoin.pdf">presentation</a> on TwinsCoin - a modular cryptocurrency framework, originally authored by Alexander Chepurnoy, my colleague from TokyoTech project, presented by me at TokyoTech.
