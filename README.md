# Fork the World - roles and voting app

The Fork the World hackathon has an open bounty for displaying petitions on other DAOs as well as a bounty for a way to create petitions and vote on petitions. While no code was produced, the idea here is to create a place to unify those two things. Looking to each DAO/Guild's Discord server as a source of truth, we can both have a place (meta commons site/interface) to view all petitions from DAOs that have joined, as well as serving as the basis for the voting system.

In an effort to maximize voting turnout, instead of having a web interface to vote there could be a dedicated bot to manage each DAO's votes (and interact with an Aragon product). Besides facilitating voting on any DAO that has a Discord, there's also an opportunity to enable the easy creation of DAOs for anyone that has a Discord server (this feature is just a proposal for future work, and is not presented in the wireframes below).

Wether using it for voting on paid roles, voting on role payout adjustment, checking voting history, checking paid members, checking voting members or creating petitions, the commonbot can be the easiest gateway to increase community participation in DAO governance.


---


#Screens

I have little knowledge of code and couldn't find a team to work on this with, so many elements of what's presented here may be inaccurate, impractical or just plain impossible. In any case I'm fully willing to further explore, if possible with a group, the technological impossibilities and reuse or create whatever's necessary to deliver the easiest possible process to promote individual participation in DAO communities.

https://www.figma.com/file/O3YYD4mbORgylGOMb9uOil/metacommons?node-id=0%3A1

The first 5 screens (sign-up flow) attempt to demonstrate the rough interface and high-level view of the signing up process (using Discord as source of truth)

The next 2 screens display a very simple layout for a browser interface. Title bar with connection, simple filters and search box and, below, cards showing each petition. Everything here was created with simple mobile portability in mind. The second screen is a modal/popup to show when user tries to vote on the site.

The last 3 screens are an overview of the processes of signing up, petitioning and voting. No interface was drawn of the voting and petitioning process, but most functionalities would be accessed via bot commands and are much simpler to implement than layouts.

Also not done (it's a lot, I know): all authentications, associations between DAOs and Discord, and actual contract interactions. This is only the things my design eyes can see.


Thanks for your time.

Max (or Lucas)
