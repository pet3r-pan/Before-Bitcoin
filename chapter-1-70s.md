# 70s “Public Key Cryptography”

To understand cryptocurrency and its history, we must go back into the 70s by exploring the historical and scientific significance of public key cryptography’s invention. It is at the heart of modern day cryptography, both for privacy and authentication. Not only was the invention technologically significant but the nature of the open publication led to the first real modern wave of interest into the field of cryptography. The inventors would spark a technological revolution that would be carried on into the the future, down to this very day, eventually becoming a movement that would change the world.

Before the 70s, cryptography was primarily only used by the military to secure communications. After WWII, as the United States and Allied nations such as the United kingdom reigned victorious, they led the world in cryptographic research and practice. However despite this, all research was classified by the intelligence agencies of the likes of GCHQ, the NSA, and the Russian GRU. During the period between the 1940s and 1970s, there was little publicly released cryptographic literature as knowledge was tightly controlled. In the US, it was regulated under the Munitions Act which classified cryptographic information as a military munition where public access to such information was stringently controlled by the the NSA.

There was little to no public research of cryptography before then. [This overlooks IBM’s work, which laid an important foundation for our own. Look into it: Feistel, Lucifer, his Scientific American article, DES.] It was all closed source. This was until three researchers Martin Hellman, Whitfield Diffie and Ralph Merkle, came together to invent the concept of public key cryptography. Their creation was not only of scientific significance but its open and public publication sparked a cryptographic revolution that would ripple on till this day...

So how did it happen? What drove this open publication?

First, let us follow the story of Martin Hellman.
Martin Hellman
Hellman was exposed to science at an early age by his father, a physics teacher at a New York City high school.

“My Father had books on the bookshelf that I would pull down and read about things. Including one I remember, Ganot’s Physics, an old physics text from the 1890s that he bought. Obviously it was an antique even for him. And my seventh grade science fair project came out of that. So I was interested in science, but not particularly cryptography, and I loved math too.”

Having gained a liking for science, he followed it to study electrical engineering at New York University and went on to complete his masters and doctoral degrees in electrical engineering at Stanford University (1967 and 1969). He enjoyed academia and enjoyed his time at school. Interestingly, he never studied computer science and had no involvement or understanding of cryptography during school.

He was instead, very career minded. At an early age, he had planned out his life, envisioning how he would go work in management for enterprise businesses as he believed that he would have the opportunity to travel to world while being paid to do so. Staying single until at least the age of 35 was part of his plan. Get paid a health salary. Influenced by a lower to middle family consisting of a high school teacher father and a homemaker (later teacher) mother, he sought out the concept of money, travel and luxury.

This would not pan out as a smoothly as he planned. At the age of 20, he had begun his graduate studies in information theory, a field of algorithmic mathematics… [look it up]. Hellman thought that if he had a PhD then he could counter his youth and lack of experience in management.

“If I had the PhD. it would be a way to help quell questions like ‘what can this kid do?”

Despite previous expectations of staying single until 35, in the first year of his PhD, he got married. A year later, he achieved a breakthrough and wrote his dissertation on: Learning with Finite Memory. Finishing school, he now could follow his dreams of being a high flying management executive. For a few months, he was juggling the decision to either teach or work in enterprise but decided: “No thanks, I don’t want to be poor.”

Other plans changed as well. Not only did he get married almost 15 years earlier than planned, but he and his wife decided to start a family after just a year of marriage, whereas the original plan had been to wait roughly five years. There first child was born two weeks before their second anniversary. As all his well-laid plans changed, he found himself wondering:

Early influences of Harry Feistel & Peter Elias 

So off he went to go work for IBM at the Thomas J. Watson Research Centre in New York. Hellman worked in the Pattern Recognition Department building machines that tried to recognise numbers from photographs (captcha lol). While Hellman’s work had nothing to do with cryptography, IBM had it’s own division focused on cryptographic research. From that division, he met a German researcher called Horst Feistel. Through their friendship, Feistel introduced Hellman to cryptography. They often had lunch discussing cryptographic systems and seemingly unsolvable problems. Hellman regards Feistel as one of his biggest early influences and would go on to later design the government’s data encryption standard (DES).

“Do I really want to be traveling the world or do I want to have more time with my family?”

Deciding to settle down and take care of his family, he decided to quitleft his job at IBM and joined MIT as an assistant professor of Electronic Engineering. This move also turns out to be extremely significant to Hellman’s interest in cryptography. Joining as an Assistant Professor, he would work with Peter Elias, MIT’s Chair of Electronic Engineering until shortly before Hellman arrived in 1969. Elias was a close friend of Claude Shannon, the “Father of information theory” and had worked with him on information theory. Information theory explained the quantification, storage, and communication of information where it underpins all if not most aspects of information science from data compression, cryptography and the encoding of DNA. Similar to Feistel, Hellman became close friends with Elias where he was introduced to information theory and the work of Claude Shannon: “A Mathematical Theory of Communication” (1948), where Hellman cites being another landmark influence in his budding appreciation of cryptography along with Elias’s mentorship.

After spending two years at MIT, he left to join Stanford in 1971 where he previously completed his masters degree. It was at Stanford where he had begun to seriously pursue research in cryptography. His peers thought he was crazy in doing so as cryptography had be rarely pursued publically. “They told me I was crazy”, Hellman said. Funny thing was, he didn’t exactly disagree with their sentiment:

“How could I hope to discover anything that the National Security Agency, which is the primary American code-making, code-breaking agency, didn’t already know? And they classified everything so highly that if we came up with anything good, they’d classify it.”

However, he had already fallen down the rabbit hole and driven by his intellectual fascination, he continued research with the belief that cryptography would be at least of commercial importance in the future. He had begun to publish official cryptographic reports in 1973 and while most of it went unnoticed by other academics, a research called Whitfield Diffie reached out to him.
Whitfield Diffie
This researcher that had reached out to had similar story in having great mentors.

While Hellman was only introduced to cryptography later only after his career had started, Diffie was introduced to cryptography at the early age of 10. He father who was a history professor brought home a stack of books from the local library. A book on cryptography happened to be in the mix and soon began a love for mathematics. 

But despite his fascination with mathematics, he hated high school school and struggled through it. And while he was described to have “performed competently”, he aced the entrance exam for MIT for a Bachelors of Mathematics. During his time there, he tried to teach himself programming but thought of it was “very low class work” and instead was spent most of his time pouring over pure mathematics. And even despite his aptitude of mathematics and “never did apply himself to the degree his Father hoped”. 

Right at the about as he graduated, young men around the country were being drafted to fight in Vietnam. Machine guns and screaming Vietcong did not particularly interest Diffie, so he took at job developing software and doing other “low class work” as the other more boring yet attractive choice. At the same time, he also started to work in his spare hours ‘part time’ at MIT’s Project MAC’s Artificial Intelligence Laboratory which was run by Marvin Minsky and John McCarthy. Not long after starting, he began to spend more waking hours working at the labortory than his day job developing software.

Similar to how Hellman found a mentor in Feistel and Elias, Diffie developed a strong relationship with McCarthy, who would later go on to coin the term and invent the concept of artificial intelligence. He was dubbed as the ‘father of artificial intelligence’ and is often quoted for incredible focus on the future:

“Every aspect of learning or any other feature of intelligence can in principle be so precisely described that a machine can be made to simulate it”

Under his guidance, Diffie was exposed to his computing philosophy and developed a deep understanding of networking, electronic keys and authentication. Diffie later followed McCarthy to Stanford to join his new and later renown AI Lab (SAIL: Stanford Artificial Intelligence Laboratory). While working at Stanford, Diffie came across David Kahn’s book: ‘The Codebreakers: The Story of Secret Writing’. It summarised the entire history of cryptography from ancient Egypt to the time of its writing. Diffie described it to have ‘profoundly’ influenced him in his beliefs surrounding privacy. 

Compelled, he decided to pursue his own personal research of cryptography and left SAIL in 1973. He would spend the next year jumping around the country to meet and discuss cryptography with different experts.

“I was doing one of the things I am good at, which is digging up rare manuscripts in libraries, driving around, visiting friends at universities.”

Later in 1974, he visited the IBM Thomas J. Watson Laboratory at Yorktown Heights to meet with the cryptography research team. At that time it was led by Horst Feistel, the Hellman’s mentor when he was still working there. During his trip to the IBM, he was referred to a researcher who they thought he would benefit meeting: Martin Hellman, a professor who was researching cryptography at Stanford.
Whitfield Diffie connects with Martin Hellman
“In the fall of 1974 Whit shows up on my doorstop. I’ll never forget that day,” — Hellman (2011)

And through a referral, Diffie agreed to visit Hellman at his house. He came in the afternoon, but stayed for dinner and left at 11pm. An hour turned into two, three then more. The short meeting expanded over hours of discussion. 

“Working in a vacuum had been taxing in a way, and finding a kindred spirit was really something,”  — Hellman (2011)

Soon after, Diffie took at job a local research group and similar to his first job, he would soon spend more time working outside the 9-5 in researching cryptography with Hellman.
Data Encryption Standard (DES)
In early 1975, the government published the its first ever public piece of cryptography:DES. A cypher designed and approved for public and commercial usage. This was pushed by the NSA, especially for financial services. The development of the cypher was commissioned in 1972 by the the National Bureau of Standards (now known as NIST, National Institute of Standards and Technology - an organisation regarded as a shell of the NSA). It took several years before IBM developed a cypher fit for the general purpose encryption. IBM named the cypher ‘Lucifer’ where it was designed by IBM’s very own Horst Feistel. While IBM produced it, NSA reduced the key size from 64 to 56 bits. This would come back to bite them.

In the beginning, Hellman and Diffie embraced the DES with open arms as a important step to bringing cryptography into public use. However as they looked closer, they became salvant critics of the cypher design, arguing how it the key size made it vulnerable to brute forcing but also how there was an need for greater transparency behind the design of the cypher. This concern arose due to feared rumours of how the NSA had installed a backdoor to the cypher design with IBM claiming the NSA altering the cypher’s substitution box without any known consultation.

This distrust of the government stemmed from the conclusion of WII as reflected by public literature such as ‘1984’. This sentiment was carried onwards into the 60s with the cuban missile crisis and governmental resistance against black and gay rights. This was exacerbated in 1972 where President Nixon was accused of bugging the Democratic National Committee Headquarters in Washington DC. To engineers and researchers, their fears were slowly but surely manifesting before their eyes as rumours of NSA controlled cyphers emerged.

With Hellman and Diffie appeared as guest speakers on radio shows and their criticisms featured in newspapers. The duo were working on research into certain cryptographic problems and which was when they were introduced to Ralph Merkle, a young 23d year old computer science student from Berkeley (Hellman was 30 years of age with Diffie only being one year older). He would become the ‘key’ to the invention of public key cryptography.
Ralph Merkle
Ralph Merkle was a computer science undergraduate at Berkeley who had no involvement with cryptography before his encounter with Hellman and Diffie. And despite no cryptographic expertise and understanding, he would go on to solve the problem underlying public key cryptography.

In his networking class: CS244, he stumbled across a cryptographic puzzle of:

How do you establish secure communications when a hostile enemy already knows everything?

Coincidentally, Hellman and Diffie had previously failed to come up with a solution and like many others, regarded it as an unsolvable problem. However with Merkle unknowing of the problem’s regarded impossibility chose to work on it as his course personal project.

“When I thought about how can you possibly establish security when everything is known to the eavesdropper, and the eavesdropper can listen in on communications, how can you possibly establish security?

So my first thought was: it doesn’t look like you can, so I’ll try and prove that it’s impossible. So I tried to prove that you couldn’t establish security, and I tried and I tried and I tried and I failed miserably.

Then I thought about it some more and I said, “Well, if I can’t prove that you can’t do it I’ll turn around and try and figure out a method to do it.” And when I tried to come up with a method for doing it, having just tried to prove you can’t do it, I knew where the cracks in my proof were, so to speak, and I knew where I could try and slide through. So I worked on those places and lo and behold it turned out it was possible. I could use the cracks in my proof to come up with a method for actually doing it, and when I figured out how to do it there was this, well, the traditional “aha moment” where I said, “Oh, yeah, that works. I can do it.”

That happened very rapidly. It was all one night of staying up late and thinking and then realizing “Oh, my gosh, I can do this thing. It seems very counterintuitive but I can actually figure out a key. I can establish a cryptographic key over an open communications line even if the enemy, the interloper, the eavesdropper knows everything”.

With no theoretical or historical knowledge about cryptography, he unknowingly solved the puzzle. He had written and solve the problem over mostly one night and soon after, shared his work. The head teacher of his networking class however could not understand it and told him to find something better to do.

He submitted his work to CACM, a computer science journal and was rejected as well. However, this time, he was rejected as the editor of though the contents of his paper was “…not in the main stream of present cryptography thinking…." and posed a security risk to the publication as cryptographic materials were heavily regulated. Despite coming to two dead ends, his luck would turn as when he shared with Peter Blatman, a researcher at Berkeley. He recognised the value of his work and knew of Hellman and Diffie who were working on similar cryptographic problems. Not long after, Diffie had invited Blatman out to a cryptography meetup at Stanford. And during the car ride to the meetup, Blatman brief mentioned the problem that Merkle had been working on and solved. 

Apparently Diffie had been obsessing over the same problem for years and upon hearing about how some young computer science student had potentially solved the problem, he dismissed such a possibility — erupting into an outburst. However once Diffie was calm, it at the very gained his attention. Just before the conference, Hellman and Diffie submitted a paper which explored the applications of public key encryption under the assumption that it was possible. The had recently researched the feasibilities of such technology and were in search of a solution. Diffie gave Blatman a copy to give to Merkle and upon his return, caught up with him.

“There are these guys at Stanford who talk just like you.”

After reading Diffie’s paper, Merkle sent over his work on the concept of public key cryptography that would later become known as ‘Merkle’s Puzzles’. Upon reading his work, Hellman and Diffie had completely shifted their way of thinking. Despite Merkle’s youth and complete lack of cryptographic knowledge, his creativity had solved the public key distribution problem. The 23 year old managed to achieve what was thought seemingly impossible.

Re-designing Merkle’s work, Hellman and Diffie found his solution inefficient. And through this iteration, the duo’s deep cryptographic understanding had produced a much more efficient solution to the key distribution problem. Soon their concepts would be formulated into a paper that would be known as: ‘New Directions in Cryptography’. Following their collaboration, Merkle left for Stanford, taking up Hellman’s invitation to work under him as a PhD student.

In November 1976, the paper: ‘New Directions in Cryptography’ was released. 

It discussed fundamental problems of symmetric key cryptography, explored its weaknesses in authenticating communication and presented the concept of public key cryptography. While Merkle was credited for his independent work, the communication protocol was named: the Diffie-Hellman key exchange. Only in 1977 when public key encryption was patented, did Merkle become officially credited as one of the three inventors. 

Diffie reflected on Merkle as “possibly the most inventive character in the public-key saga”. 

“The system has since become known as Diffie–Hellman key exchange. While that system was first described in a paper by Diffie and me, it is a public key distribution system, a concept developed by Merkle, and hence should be called ‘Diffie–Hellman–Merkle key exchange’ if names are to be associated with it. I hope this pulpit might help in that endeavour to recognise Merkle’s equal contribution to the invention of public key cryptography.” - Martin Hellman

At the end of the paper, they had written about their purposes and intents with their research: To inspire others to work in cryptography and democratise the a field of knowledge which has historically been monopolised by the government. For the first time, the public had ‘open source’ access to powerful encryption research. This single paper would spark a whole new wave of public research and single handedly break the monopoly on cryptographic knowledge.

It was later revealed that Hellman, Diffie and Merkle were not the first inventors of public key cryptography. A form of it was initially created actually implemented by Great Britain’s intelligence agency (GCHQ). Despite NSA access, it was classified and remained in the dark. 

Now, imagine if these three never published public key encryption... Our world potentially might be very different. 

Hellman, Diffie and Merkle’s publication managed to incite a new wave of innovation that would last for decades whereas governmental agencies kept their findings behind closed doors, stunting innovation. This contrast and highlights the importance of open source collaboration within cryptography and other sciences. 

Fittingly, the first line of the paper began: 

“We stand today on the brink of a revolution in cryptography” 

https://conservancy.umn.edu/bitstream/handle/11299/107353/oh375mh.pdf
