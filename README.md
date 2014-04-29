BitSolve: An open source incentivized decentralized free-market peer-2-
peer architecture that harnesses the computational power of the world in
order to solve complex and/or large-scale biological problems while
providing real-time monetary compensation in bitcoin to anyone with a
CPU.
The computational resources required to solve biological problems are
hard to over-estimate. Since the 1990s, bioinformatics and computational
biology have emerged as crucial elements in solving problems in virtually
every field of biology. Such needs are predicted to increase as dataset
generation explodes due to technologies such as next-generation
sequencing, high-throughput proteomics, metabolomics and epigenomics.
Furthermore, scientists are beginning to appreciate holistic approaches in
modeling biological systems such as whole cell, and organ level dynamics
via integrating several datasets from multiple sub-cellular technologies that
utilize computationally intensive algorithms.
There is an enormous amount of computation power that is currently
inaccessible to the life scientist. This power is available not in laboratories
or institutions, but rather in personal computers in homes and hands
(smart phones, tablets) that belong to people all around the world. These
computers are often idle or are underperforming because of
computationally trivial activities such as web browsing, checking e-mail or
typing into a word processor. There would be an exponential boost in
computation power available to life scientists if such CPU power could be
harnessed for solving biological problems. Furthermore, as each individual
would upgrade their hardware for their own private use, this would free
scientists from this task, freeing them to focus on hypothesis testing and
the scientific questions at hand.
BitSolve would enable any scientist in any part of the world to ask
sophisticated questions from an ever more increasing dataset without ever
having to worry about updating hardware or statistical software. Distributed
computational architectures are not entirely novel, not even for biological
analysis. However, previous systems have had one major flaw: they have
relied on the voluntary donation of computation resources by individuals at
home. As individuals have had zero monetary incentive to lend their
power, many of them have been reluctant to do so.
We propose a system called BitSolve that provides a direct monetary
incentive to anyone in the world with a computational unit and an internet
connection, where individuals get paid directly and immediately for
devoting their computer's CPU time over the internet. Such a system could
have additional benefits as well. For instance, it would allow individuals
and scientists to bid for a CPU power/price that would drive down the price
of computation power in a free market environment. This would encourage
third world citizens to participate in the network due to their relatively lower
electricity costs. BitSolve will thus enable truly global participation on an
even competitive plane, where the mere ownership of a device with a
computational unit will simultaneously be a revenue source for the owner,
and a cheap and ample computational source for researchers.
How does it work?
The architecture would be a piece of software that anyone could download.
The software would be coded in a cross-platform programming language
such as C++, Java, QT etc, so that it could be run on most desktops,
laptops, smart phones, and tablets. Once the software is run, the user's
computational unit becomes part of a network of computers running the
same software. Anyone running the software can choose to become a
“CPU giver” or a “CPU requester.” It is important to note that, nowhere
during the process is there a need for entering any personal information,
making this a relatively friction free adoption technology.
A CPU giver:
A CPU giver is someone whom has downloaded the software and agrees
on renting out their CPU for a certain time on an agreed upon price. A
“CPU giver” would ask for a certain price for example x BTC/min or at a
market price. The software would determine the market price of the “CPU
giver” after running a test on the CPU to estimate the available resources
and then strike a price based on the real-time market exchange. The “CPU
giver” could then leave the computational unit, which, if selected in the
market, would conduct parts of an analysis, broadcast the completion of
analysis, and after receiving confirmation from the network of true
completion, would receive funds from the CPU requester that would
directly be transferred to the CPU giver's wallet. All of this would happen
automatically and without the need for a third party.
A CPU requester:
A CPU requester is someone who is seeking computational power in the
network and has funds in bitcoin allotted for the required analysis. The
CPU requester would have a statistical algorithm to be conducted with a
certain dataset. After choosing the dataset and copying the R script to the
software, the CPU requester then chooses the price that they are willing to
pay for the analysis. “CPU givers” that have fast CPUs would ask for a
high price, and those with slower CPUs would ask for a lower one. In other
words, if CPU requesters wants the analysis conducted in a small amount
of time, they would pay a higher price, whereas, they would bid for a lower
price if the analysis can be run in a longer period of time.
The software would also include a real time CPU/price exchange market
that would serve as a reference for bidding. Once the price is chosen, the
information is broadcasted across the network and CPU givers are chosen
automatically (corresponding with asking prices). The request is then
processed and the parts of the data are analyzed securely. Once the
analysis is complete, the network using existing Bitcoin proof-of-work
algorithm verifies the completion, and the payment of bitcoin is made from
the CPU requester to the CPU giver. The results are then returned to the
requester and operation is complete.
Can you describe the software?
The software would have four main components
1. R Statistical package (http://www.r-project.org/): R is the open source,
statistical engine that would be the interface for the analyst to
program their analysis. R is also the most widely used and rapidly
evolving statistical platform used by life scientists due in part to its
open source and thus free nature.
2. MutliThreader:Java based open source interpreter that converts the R
program into smaller portions that can be sent to separate
computers in the network to conduct the analysis and also handles
the peer-2-peer communication.
3. A Bitcoin (http://bitcoin.org/en/) (open-source) client that would handle
the real-time financial transactions.
4. Java based open source exchange system and handles the bidding for
CPU by price for the CPU requester and the bidding of CPU by price
for the CPU giver.
5. Java based open source allocation for integrating other types of
computation not applicable to R for future expansion.
* Note the specific software requirements are not mandatory but use the
framework of what is possible in 2013. We also acknowledge that some
parts of the systems can be implemented with software such as
mastercoin (open-source) and colored coins(open-source). The two
essential parts would be a bitcoin client and R statistical software.
Why Peer-2-peer and not distributed? Is there a difference?
Past architectures that have sought to harness the computational power of
personal computers have been distributed from one to many, as in one
laboratory aims to distribute their software to many individuals to conduct
their analysis exclusively and specifically.(Pande Lab, Stanford). A peer-2-
peer united open source system, would entail that any one that uses the
free software can act as a CPU “giver” as well as a CPU “requester”. More
importantly, because the entire process does not require personal
information, the bidding process for CPU time would be free of
considerations regarding project scope or vocational seniority. Due to this
“freedom,” a graduate student in Boston, could program his personalized
analysis of black hole dynamics to run on super computers in Stanford by
bidding a higher price, while on the same market a precocious 15 year old
in Korea, could bid a lower price to have his father's farm optimization
algorithm run on slower and thus cheaper smart phones in Nepal.
The diversity in juxtapositions is intentional and should highlight that
although this paper discusses the benefits with the life scientist in mind,
the implementation does not limit, and to a certain degree, demands
context and identity free analysis. This provision is primarily meant to
ensure swift and diverse advancement of the software and to have enough
CPU 'requesters' to implicate free market dynamics that will lower the
prices and thus ensure highest value for CPU speed per hour/price. It may
be useful to note this will be the first time CPU speed/price will self
stabilize on a global level to an optimal value that will be devoid of price
inflation due to taxes associated with local governments and geographical
distance to the CPU manufacturer etc.
Peer-2-peer is extremely robust. Since previous distributed systems have
had one governing computational node that does all its CPU requesting,
they have been vulnerable to attacks and other security risks. Since this
system is peer-2-peer, anonymous, and decentralized, there would never
be a target to attack in the first place, ensuring security and robustness.
Taking the system down would only be attainable by compromising the
Internet in its entirety.
Can you explain how the monetary compensation works?
Bitcoin is a revolutionary technology. It is a completely decentralized, peer-
2-peer, open source, Internet currency/asset. Bitcoin uses peer-to-peer
technology to operate with no central authority or banks. The network
collectively carries out the managing of transactions and the issuing of
bitcoins.
Bitcoin's unique and groundbreaking properties make new applications for
financial transactions that were virtually non-existent with legacy
technologies now possible. This project would not be possible if monetary
compensation of CPU givers entailed entering personal data, bank
information etc. This would carry significant friction for scaling and in some
countries wouldn't be possible even in theory because of high numbers of
unbanked individuals and archaic financial systems.
The only friction in this model is where anyone requesting a CPU would
first need to exchange their local currency into bitcoin, which can be done
in several online bitcoin exchanges that accept a plethora of local
currencies. Since the ratio of CPU givers to CPU requesters is expected to
be very high, this is unlikely to cause major problems in scaling now or in
the future. CPU givers would only be required to download the software
and run it in order to start accepting monetary compensation. It is also
useful to note that the bitcoin network itself may be used as a source for
computational power, although this would carry with it limited diversity in
the type of computation possible.

