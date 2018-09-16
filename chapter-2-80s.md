# 80s “Origins of decentralisation”

With the release of “New Directions in cryptography”, Hellman, Diffie and Merkle’s work was soon followed up by a group of researchers at MIT which produced the first public implementation of a public key encryption: RSA. Designed and developed by Ron Rivest, Adi Shamir and Len Adleman from MIT, it propelled cryptography into the limelight of engineering academia. In a short span of a few years, a small handful of cryptographers had managed to publish papers that would have otherwise been classified top secret and spark a new wave of interest in cryptography.

While Martin Hellman, Whitfield Diffie and Ralph Merkle would continue making significant contributions to the world of cryptography, their greatest work was not in their scientific achievements but rather by reviving an entire field of computer science and catalysing a whole new generation of cryptographers. Near the end of the 70s, the San Francisco Bay Area had become the world’s leading hub of technology through the presence of Apple, Intel and Hewlett Packard. After about a decade of Microsoft and Apple fighting to claim control over the personal computing market, computers had embedded themselves in modern America. This growth and adoption of computing had also manifested itself in the form of pop culture through the widespread cult following of Star Wars and spurt in science fiction culture. There was a new found sense of fascination and romanticism revolving around computers, robotics and technology. With a country that primed and ready for technology, Apple’s later record breaking IPO of $1.3 billion in 1980, would pour jet fuel on to a second technological renaissance that would set Silicon Valley up for success for the next 30 years.

Right before the break of the 80s, David Chaum, a post graduate student from Berkeley stumbled across the work of Hellman, Diffie and Merkle. Studying computer science at the time, he was one of many to come across the paper that had spread like wildfire amongst academics and engineers. While he had not specifically studied cryptography before then, he naturally took to through his natural aptitude for breaking things. With others were playing in the sun, Chaum spent most of his childhood breaking and playing with security instruments such as locks and safes. And with a wealthy family, his access to a home computer lead him to spend most of his teenage years learning how to break computer systems, digging through digital junk for sensitive information and cracking passwords. Gaining an aptitude for computer systems at an early age, he would become one of the first of the ‘computer generation’ who would have grown up such technology. And duly so, he was also one of the first to have caught the hacker paranoia bug. Having broke and exploited many seemingly ‘secure’ systems, Chaum gain a sense of cynicism and distrust about the security of most computer systems. And upon delving into the emerging field of cryptography, he immediately picked up an aspect of security and privacy that was completely overlooked: Metadata.


While Public key encryption conceptually solved the problem of key exchange to allow for securly authenticated messaging, Chaum suspected that it was only one piece of the puzzle. Instead, he believed that the open unprotected data around the messages of “who converses with who and when they converse” as a risk to privacy and confidentiality. Through these pieces of meta information, he knew that people could theoretically be identified and tracked as a result. 

Completing his graduate studies at the time, he decided to write his research paper on the “traffic analysis” problem:

How do do you keep secret the knowledge of who converses with who and when they converse?

He graduated in 1979, releasing his first major cryptography paper: “Untraceable Electronic Mail, Return Addresses, and Digital Signatures” (While initially released in 1979, it was only later published in 1981).

Citing the Hellman, Diffie and Merkle’s work of “New Directions in Cryptography” (1976), in the paper, Chaum outlines the risk of personal privacy and provides the blueprints of an anonymous mailing protocol using something known as a mix network. His protocol protected the identity of the messengers as well as the time of the message being sent.
How do Mix Networks work?
A mix network is a network made up of nodes that uses public key cryptography to authenticate messages. These nodes send information to each other to ‘mix’ up the original sender’s identity and timing of messages. The of message addresses was important as it could be used to identify the origins of messages. The timing of messages could also be used to identify messages that would correspondingly move within a network.

With a mix network, when you send a message to someone, the encrypted message would first be passed to a node where it would be batched with other messages from other senders. This batch would be then be sent between different nodes. Think of a pin ball full of messages bouncing around different nodes. In the end the message would exit out of the network and end up at the intended address with the original sender hidden. For replies to the messages, it would be sent back to the original address that would be unknown to the sender. Thus the identity of senders and order of messages would stay unknown and prevent the ability to trace and spy on messages.
 
Video explanation of Mix Networks

While designing the network, he dismissed a solution that used a single message authenticator believing that it was easily compromised, instead he insisted that: “Ideally, each participant is an authority”. The Mix Network protocol would be used to build TOR, the anonymous browser that you can use to buy drugs or hire hitmen (yes, incognito mode is not anonymous). Mixing is also used by Monero to anonymise transactions.

If you want to ‘learn’ more about TOR: Here is an more in-depth guide
Untraceable payments
Understanding the potential risk of unprotected metadata, he also saw financial transactions in the same light. In the increasingly digital world, Chaum believed that e-commerce would play a huge role in the world but so would the traceability of consume payments. He believed that the timing of transactions and goods purchased not only enabled the tracking of people, but allowed for the profiling of individual lifestyles, consumer choices and political leanings.

“The time of payment for every transaction made by an individual can reveal a great deal about the individual’s whereabouts, associations and lifestyle. For example, consider the payments or such things as transportation, hotels restaurants, movies, theatre, lectures, food, pharmaceutical, alcohol, books, periodicals, dues, religious and political contributions.”

In 1980, he patented a digital cash system secured by cryptography which would form the basis of cryptocurrency. Patent 4529870 outlined a protocol that was able to:
Conduct financial transactions with an ‘external system’
Exchange data with an ‘external system’
Contain an ID linking the ownership of data within the ‘external system’
Store data relating to interactions with the ‘external system’
Secure the stored data through cryptography where it could be accessed using a secret ID known to the owner
Chaum later fleshes out the concepts of anonymous payments in his paper: “Blind Signatures for Untraceable Payments” that was later released in 1982. Similar to the concept of Mix Networks, his proposed payment protocol requirement included the masking of the sender, the amount being sent and also the time of the transaction.
Stumbling onto the concept of Decentralization
Back then as a student, his work was dismissed as political and radical by his peers. Similar to Martin Hellman in the 70s at Stanford, Chaum also faced scrutiny over his work. Upon pursing his doctorate studies, his head teacher told him:

“Don’t work on this, because you can never tell the effects of a new idea on society”.
Ironically, his head teacher would turn out to be right.

Despite the pressure from his peers, Chaum decided to continue his doctoral studies. Revisiting the ideas in his first paper about Mix Networks, he decided to research the concept of trust in computer systems.

As a hacker, Chaum did not trust central authorities in computer systems as he thought they could be easily hacked. Instead he believed that systems where participants are “authorities” were harder to compromise. Researching the concept of computer systems that establish trust between parties that don’t trust each other, Chaum argues the need for decentralized services in his dissertation: “Computer Systems Established, Maintained and Trusted by Mutually Suspicious Groups” (1982),
“It is not enough that the organisation maintaining a computer system trusts it; many individuals and organisations need to trust a particular computer system…
…There are many other similar applications of computers which involve private sector records related to consumers such as those arising from credit, insurance, health care and employment relationships. Public sector record keeping, in such as areas such as tax, social security, education and military service are quite similar…

…All of these applications involve one group who owns or controls the computer system and who is particularly concerned with reliability in maintaining the operation of the system and with ensuring the survival of the data maintained by the system — they will be called “trustees”. A second group or set of groups are primarily concerned about the confidentiality of the data which relates to them that is available to the system. There may be a third group or set of groups which may overlap with the first and second groups, who are concerned about the correctness of the operation of the system…”

“Computer Systems Established, Maintained and Trusted by Mutually Suspicious Groups” (1982)

Initially led by his concerns towards communications metadata, his idea of Mix Networks was one of the first concept of a decentralized service. His concerns about meta data led him to focus on the need for anonymous payments. While Chaum was focused on personal privacy, after having looked over his work and how he presents the concept of decentralization, I personally don’t think he understood the magnitude and importance of them at that time.
He presented decentralized services as a means of solving certain conflicts of interests between consumers and businesses in certain application aspects. Rather than how it is portrayed in today’s world as a sociopolitical movement, decentralidzation in his paper was first presented as an economical solution for businesses.
Graduating in 1982, he decided to continue his research on cryptography.
Meanwhile, later that year, TIME magazine named their machineof the year: The Computer. Imagine this… 2022 Cryptocurrency of the year: Bitcoin
TIME Magazine 1982
As the decade continued, his ideas had started to mature and a vision of the future had started to form inside his head. Watching the growth of computing explode faster than anyone had ever predicted, Chaum was worried.
Chaum’s warning to the World in 1985
“Computerisation is robbing individuals of the ability to monitor and control the ways information about them is used. Already, public and private sector organisations acquire extensive personal information and exchange it amongst themselves. Individuals have no way of knowing if this information is inaccurate, outdated, or otherwise inappropriate… New and more serious dangers derive from computerised pattern recognition techniques: even a small group using them and tapping into data gathered in everyday consumer transactions could secretly conduct mass surveillance, inferring individuals’ lifestyles, activities, and associations. The automation of payment and other consumer transactions is expanding these dangers to an unprecedented extent”
“Security without Identification Card Computers to make Big Brother Obsolete” (1985)
Acknowledging Orwell’s dystopian World with the paper’s title, it talks about the dangers of user data that was building up around computing systems. Chaum warned that this continued trend of ‘computerisation’ would render society open to exploitation and mass surveillance. He also argued that “surveillance might significantly chill individual participation and expression in group and public life. The inadequate security and the accumulation of personally identifiable records, moreover, pose national vulnerabilities”.

“Information service providers and other major interests, for example, could retain control over various information and media distribution channels while synergistically consolidating their position with sophisticated marketing techniques that rely on gathering far-reaching information about consumers”

The main body of his paper summarises a decentralized economy based on his previous research into the decentralization of messaging and payments. Despite his ideas being previously fragmented, he then knew the true importance of his ideas surrounding decentralized services. Seeing the future that the World was moving towards, he was acutely aware of the cross roads which lay before society. Chaum understood that the design of the internet’s architecture would have enduring social and political consequences. Projecting the vision of two futures, one built with current technology and one built with decentralized services, he saw that “The two approaches appear to hold quite different answers”.
“Large-scale automated transaction systems are imminent. As the initial choice for their architecture gathers economic and social momentum, it becomes increasingly difficult to reverse. Whichever approach prevails, it will likely have a profound and enduring impact on economic freedom, democracy, and our informational rights.”
So what was decentralization?
One of the most fundamental beliefs Chaum had was the right to personal privacy. With the World becoming evermore interconnected, he saw the need to protect his personal data. He saw cryptography as a means of doing so.
If you think about it cryptography is essentially the practice of protecting information against individuals that didn’t have permission to access it. Cryptography is a digital law enforced by the laws of mathematics, a force beyond the central control. No one is above it.
And when individuals are empowered to control and protect their data using cryptography, only then, true personal privacy can be realised.
Chaum saw decentralized services as means of protecting privacy. Enabled and secured using cryptography, it is something outside of central control. Hence this is why decentralized systems are trusted. He could believe in maths. He did not trust governments and companies.
Sounds like a nutcase right?…
Edward Snowden’s NSA leaks in 2013 Headline news outletsScreenshot of leaked CIA’s Documents on the US Surveillance program: PRISMLeaked CIA’s Slides on how their own software worked! I wonder if they have a CIA confluence wiki…Meta data being abused once again in 2017Facebook’s billion dollar business built on metadataMetadata captured by Facebook

Wow was David Chaum a time traveller?
No. He was no a time traveller, he just had an exceptionally clear in his vision of the future. He was right, wasn’t he?

…Well yes kinda of. While while it does seems that way, we haven’t gone down the route of decentralization. No system is ever perfect and I wonder if we would be dealing with problems of the same magnitude if the world did follow the heed of Chaum’s advice. Nonetheless, history has so far pointed towards the need for decentralized services.

After 30~ years after his paper, the world did indeed build itself around centralised services. With 2.2+ billion users on facebook, the world’s data was protected by good will. Good will did not hold up. Good will and the promise of Facebook had little power against the CIA and government. The lack of cryptographic ownership led to the abuse of data by Cambridge Analytica…
So is it too late?
While the Internet might have taken a wrong turn, nothing points to the fact that things are too late to change. That’s what history is full of: Evolutions in culture, technology and society. The world will always be moving, the question is just: Where?
If you didn’t understand the references shown in the images above, feel free to Google: 2013 Snowden US Surveillance Leaks & Facebook Cambridge Analytica
After the 80s
Chaum spent the rest of the decade researching cryptography and by 1988, he had moved to the Netherlands, starting his own research group. And after a decade of research, he would finally act on his vision of a decentralized world. He would found his company Digicash in 1990 and create ‘ecash’, the world’s first digital cash system. Gaining worldwide attention, many cryptographers interned and worked for Digicash including Hal Finney, Nick Szabo and Eric Hughes, one of the founders of cypherpunks, a movement that will be explored in the next part of this series. Digicash would experience highs and lows, rejecting a $180 million acquisition from Microsoft, only to declare bankruptcy a while later.
If you want to read more about Digicash: Read this. I personally found the story of the company tragic but yet comedic in a dark humour sort of way.

Digicash ‘98
By the end of the 80s, he had become one of the most well regarded cryptographers in the world.
Chaum was one of the people who knew where the World was going. He understood things that others didn’t. Deciding to focus on building a company, he would leave behind seeds that would ultimately bloom into the 90s cypherpunk movement.
This movement would go on to stand for the liberty, and fight against the governmental injustices of the 90s. Do you remember what the head teacher said to Chaum back when he was still a student at Berkeley?
“Don’t work on this, because you can never tell the effects of a new idea on society”.
David Chaum enjoying himself
