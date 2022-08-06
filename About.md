## Inspiration

I have been in the education space for some years and I see the need for genuine community sharing between tutors and students for positive changes students performance using technology.  This has been my personal project for some time now how tutors can share knowledge and earn token when student access their assessments within the Near Protocol ecosystem.

## What it does.

iMock is an decentralized app solution aimed to improve secondary school students(as a first case study), an Educational platform that enables learning at an easy pace, cost-effective and community based solution, providing seamless access to curated education assessment for students based on their curriculum. iMock is transparent in services and payment between authors/tutors and learners/students. User interface friendly, and on the blockchain.
    
    -  A tutor login with their near account and post their questions making a contract call and paying initial deposit of some near token(which covers gas fee and iMock storage fee)
    
    -  Students login with their near accounts, pay a token which in turns go back to the tutor (owner of the contract) they can practice the questions based on what they've learnt during the week at the end of each week making them conversant of what they learnt.

## How I built it

The contract was written in Rust/Solidity while the frontend was built with Typescript, chakra ui and firebase.  

## Challenges I ran into

I had a learning challenge working with server side database storage with smart contracts or web3 as I cannot write to the database without a user token from firebase to authenticate the user writing to the database. This remain a big challenge for me storing data with a near account login model. I am yet to resolve this. 


## What I learned

Building with Blockchain is quite an interesting journey as there is a lot to learn about web3 technology and how it works. With Blockchain I was able to full understand deployment and web3 accounts.
