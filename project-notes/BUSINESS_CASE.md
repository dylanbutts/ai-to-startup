
# 1. The Idea 
StreakFree is a house washing company that serves cities and towns across Nova Scotia. It's made for people who want their house cleaned once or even twice a year. A full house wash includes siding, window and gutter cleaning. Most of these customers are either older homeowners who can't or won't climb a ladder, or busy families who don't have the time. Today, you can find these services through word of mouth or Facebook. You request a quote, wait for it, and then pay full price for a one-time visit, usually $350 or more for an average house. Other companies charge that much because they spend so much of their day driving between homes and setting up their gear over and over. 

StreakFree lets neighbors book the same wash day together. When a bunch of homes on one street book the same day, the crew is able to wash them all back to back with technically no driving and continuous taking down and setting up. With this model, everyone pays less: $210 per home at three homes, then all the way down to just $150 per home at ten or more. Homeowners pay StreakFree directly when they book. StreakFree runs its own crews, and its profit comes from fitting a lot more jobs into each day at a lower cost. 

# 2. Where IT creates value 
The software mainly changes two value chain activities. The first one is operations. Typical house washing businesses have a schedule that is built job by job as calls come in, so in a day a crew might have to drive around town around 5-10 times, depending on how busy they are. StreakFree's booking system groups homes by street before the schedule is even set. In our sample data, a grouped week completed 32 jobs with only 3.5 hours of driving, compared to another company with just 19 jobs and 9 hours of driving in a week. That is more revenue from the same type of crew and the same type of truck, just a different business model. 

The second is marketing and sales. Every customer has a given reason why they should be recruiting their neighbors; the more neighbours they get on board, the more the price lowers. The "Invite a neighbour" feature turns customers into the sales force, which lowers the cost of getting new customers because it doesn't require as much ad spend. 

 

# 3. Network Effects 
 StreakFree has a one-sided, same-side network effect among homeowners. The crew members are employees, not a second group of users, so it is not a two-sided platform. Every homeowner who joins a street's wash day makes the service cheaper for all the other homeowners on that street, because the crew's travel cost is spread out over more homes. A homeowner on a street will only pay $150 for a full house wash with ten bookings; on the other hand, the same homeowner could be paying $240. 

The effect is local and capped. A booking that's across town does nothing for a homeowner on "Maple Ridge Drive," and once a street gets ten booked homes, the crew's schedule is full and the price stops dropping. So StreakFree does not get any stronger simply by being big, it gets stronger street by street. This matters for the moat question, because a competitor could also possibly win one street at a time. 

A problem this model could face would be the cold start problem, an empty street doesn't give any discount, so first-time customers don't really have any reason to join. To face this problem, I would start from the customers of my existing house washing business. If I didn't own a company already, I would start with some paid advertisement and door knocking for a couple of months straight. Since I already have customers, they trust me with the service, so each customer I have could be the "founding home" on their street, with a free gutter clean for the first three neighbours they get on board. Launching one street at a time means each network starts with someone who's already on the street. 

On the website, the "Your Street" page shows this perfectly. As the person clicks houses to join, the price per home, the progress bar to the next price drop, and the street's total savings all update. The crew dashboard on the website shows the cost side: grouped streets mean more jobs and less driving for the crew. 

# 4.Can it be copied? 
The website itself isn't the advantage. It only took me a couple of hours to figure it out and set it up with the AI assistant and no coding background, so anyone who's in this class or even any washing companies could copy every page in just a couple of hours. The group discount idea is also easy to copy once a competitor company sees it. So the question is which resources behind the website would be hard to copy by a competitor. I tested three different resources/capabilities against VRIN. 

1. An existing base of local customers. Right now, I already run a house washing business with over 100 customers in the summer, and at least half of them come back to me the next year or even sometimes in the same year. This is very valuable because the whole model depends on having a first home on each street. It is rare because a new competitor starts with zero. It's hard to imitate because trust in a business that works on your house consistently makes it hard for customers to change companies. It is only partly non-substitutable because of the easy-to-replicate business model, but neighbors could coordinate a group discount themselves in a Facebook group or a chat. This passes VRIN, but only locally to HRM and surrounding areas.
   
2. Street-level booking and route data. Every booking tells StreakFree which streets book together, how much driving each route needs, and how long each house will take to clean. Over time, this lets me price and schedule better than a newcomer that has to guess. This is valuable and rare, and it can't be bought; it can only be built by physically doing the jobs. It's an advantage that gets stronger over time because each season adds more data.
   
3. Equipment and know-how. I own a house washing company, and I know how to do all the different types of work properly. This is very valuable, but it's not rare. Anybody can spend a couple thousand on the gear and can learn how to work and operate the equipment fairly easily. Considering this, it fails VRIN. 
StreakFree also doesn't have the best staying power; it's fairly weak. Switching costs are low: a homeowner can book a different washer next year with no penalty. To raise them, I would offer something like a yearly "standing wash day" for every street, so the street books once and is rebooked automatically each season. 

A well-funded rival would need a larger regional cleaning company that could copy my website and the pricing. To beat me in my area, it would still need trained crews, and it would have to win over my loyal customers street by street, which would take at least a couple of seasons. My moat is real but small and local, strong on the streets where I already have my loyal customers, but fairly weak everywhere else. The best defense is to keep door knocking and gaining loyal customers so I can have a starting point and then cover the street. 

 

# 5. Cloud and operations 
A real StreakFree would rent pretty much everything as cloud services instead of running its own servers. Things like payments, text messages and login invites would be SaaS, pre made services I pay monthly or even per use. The website and the shared booking database would run on a hosting platform, which is PaaS, I supply the app and the provider is the one that runs the servers. In this case, I wouldn't need laaS at this size, because it would mean managing the servers myself. The main risk would be depending on these providers. If the booking site were ever to go down, I would lose bookings, so I would keep a phone and text backup just in case. If a provider were to raise prices, I am partly locked in, so I would choose standard tools that would be easy to move away from and avoid building features only one provider supplies. 

 

# 6. Risks and ethics 
Neighbor's privacy. We will store all the information needed such as names, addresses and phone numbers along with the “Your Street” page that shows who has booked. That could reveal which houses will be empty on a wash day or it could even embarrass someone who doesn't want their neighbors to know their plans. The real version will show only how many homes have joined, not what houses. It will also give the homeowner the option whether they do want to display their name and address or not. 

Payment and data security. A data breach would expose customer’s addresses and any other personal information. Payment details don't matter because the payment is payed by either tap, cash or cheque. Customer payment details aren't saved or stored anywhere.   

Runoff into the environment. Washing a bunch of homes on one street in a day puts more detergent and dirty water into the storm drains. Most companies use a soft wash solution that includes sodium hypochlorite and dish soap, which can be harmful to plants, skin, and pets. StreakFree uses deionized water, we connect our deionization tank to the hose, and it’s then hooked up to a brush. This method is extremely safe and ecofriendly, considering that it’s only purified water. 


# 7. AI use
AI use: I used Claude to come up with some bullet points and key topic ideas for all six sections from my business idea, my prototype and my experience running a house washing business, and to check my course terms against the lecture slides. I took the notes and key ideas and formed them into paragraphs. I started all my points with inspiration from the points that Claude gave me.  

 

 

 
