**Chad Perry:**

Today, we're hearing from Mike Jessop, co-founder of Moo Free Chocolate, an award-winning maker of organically-certified, dairy-free and gluten-free chocolates based in the United Kingdom.

**Chad Perry:**

Now, what makes Mike's story so special is that he and his wife, who is also his co-founder, have not only brought together two of the world's best innovations in my opinion, that of chocolate and e-commerce, but because Mike's previous career was in software development, he's been able to pretty much single-handedly build out an entire custom digital infrastructure to run their unique business at a level of efficiency that simply could not have been possible with off-the-shelf tools.

**Chad Perry:**

But what's really interesting is that despite his engineering background Mike ran into the same kind of challenges that any business owner would in defining exactly what he needed at various stages along the way, along with unexpected challenges in getting there, which is what we'll be hearing about today. Mike, great to have you with us today.

**Mike Jessop:**

Hi Chad. Great to be here.

**Chad Perry:**

What I'd like to do is get into some of the details about how you've built out your digital toolkit, but first it'd be helpful to get a short backstory on how Moo Free Chocolates came into existence and what motivated you to build your own systems.

**Mike Jessop:**

Want to this is a long story, Chad. I'll give you the brief version. My wife and I started making dairy-free chocolates when we found out there was just a lack of products like Easter eggs and advent calendars on the market for kids with allergies.

**Mike Jessop:**

So, we went into food manufacturing from an IT background, not knowing anything about food manufacturing. The challenge we face is a lot of the packages we could get to track things like stock and ingredients levels, were aimed more at retailers and basic stock control, and that really doesn't work for a manufacturer.

**Mike Jessop:**

It's a much more complex process. You've got the ingredients coming in, which are converting to other products, which they're either making other products from or they're actually products that you sell, and those products can be made up of the gluten products. We were just finding the packages you could get to manage that just weren't capable, and it was really critical from stock control as well as prioritizing orders and looking after the whole company, that we needed something that did that.

**Chad Perry:**

You mentioned a couple of key areas in your business where you had built specific tools. Take me back to the beginning, I think you said it was in 2010, where you were looking at off-the-shelf systems. Did you buy of those at first? Did you try them?

**Mike Jessop:**

Well, we started off a little more simple than that. Obviously when you're starting a company you don't have the volume of orders and things aren't quite as complex as they quickly become. We actually started on spreadsheets.

**Mike Jessop:**

So, we were using Excel spreadsheets basically. But as the number of customers and the products we were making grew, those spreadsheets not only became bigger, obviously making it harder to find the data, but as more data went into them, the spreadsheets themselves we were finding were slowing down. So, I've put some pretty complicated cross-references and things in there, to give us the summary data and to show us highlighted things and things like that. But again, as the data went in and more and more data went in, the system slowed. That's when we started looking at off-the-shelf packages. We used ones that were online, so online-based ones.

**Mike Jessop:**

The main reason for that was the ones that were offline, especially at the time, you had to have something like a dedicated Windows machine or Windows Server, and that just wasn't something ... We ran all our servers, our web servers, anything that was doing anything complicated was running Linux. We couldn't find anything that would run on Linux. I wasn't happy to purchase a license for Windows Server. The cost of a Windows Serve machine, just for this internal system, which may or may not work, because obviously if you buy this software you don't know how good it's going to be. So, it wasn't worth the investment at that stage.

**Chad Perry:**

Was that something where you sat down and went, "Okay, I know I'm going to grow the business, but I just need to start somewhere."

**Mike Jessop:**

I guess probably at the time we didn't realize we were going to need anything more complicated than that, because we were trying to manufacture chocolate but we had no idea what we were doing. It was quite easy at the beginning just to keep track of what we needed on spreadsheets.

**Mike Jessop:**

So, it was probably only six months or a year down the line where we suddenly realized, "Wait a minute, this is not the best way to do this now. The spreadsheets, they're not really fit for purpose." But ironically, when we did start using the other systems, because so many people in the company, there wasn't many of us but the people in the company were used to using the spreadsheets, they used to duplicate the data.

**Mike Jessop:**

So, they would have spreadsheets giving them exactly the same data that any package we were trying to use or anything was doing. It was great to start as a backup in case the new system didn't work, but it was really annoying when we started using a new system and then you'd find that everybody had multiple copies of everything in spreadsheets as well. It's a bit pointless, especially if you're paying for the software and then you see the spreadsheets and the two things were completely out of sync with each other.

**Chad Perry:**

Yeah, and that's a pretty common challenge with adopting any kind of IT system, where you have maybe one decision maker or a few champions in the business, and then everybody else has to deal with the consequences of using that. There was the moment where you decided to go at it on your own, or how you were thinking about what it is that you need for your unique business?

**Mike Jessop:**

Well, the first thing we did, Chad, was look at systems which in retrospect seemed to be retail-based. So, simple stock control. Stock comes in, stock goes out. They did bits in between but that's pretty much what they were doing. That seemed to work at first, but obviously our manufacturing processes were getting more and more complicated, so we realized relatively quickly, probably within the first three or four months, that those systems just weren't fit for purpose in terms of the manufacturing.

**Mike Jessop:**

One of the challenges we were facing with an online system, at the time anyway, one issue was reliability of our Internet connection. This was in 2010. We were on an industrial estate, everybody was getting faster broadband around us but nobody was upgrading the industrial estate so the telecom company and things would refuse to put in new lines or anything to the industrial estate so we had a really poor Internet connection. We were finding that the more people in the office were using the system, as we grew, the slower this was getting because people were sharing that bandwidth. These systems were really inefficient. They weren't just doing basic data over the Internet, they seemed to be doing lots of calculations over the Internet for everybody.

**Mike Jessop:**

So, if you've got one person using it, it was doing lots of calculations as you viewed the data over the bandwidth, two people using it, it was using twice the data to do that same calculation. Get four or five and suddenly our Internet was grinding to the halt, or the Internet connection was very fast at all. So, you were affecting everything in the company then, so anybody browsing the Internet or anything like that was having the same problem. They were being slowed down by all this bandwidth using on really inefficient systems.

**Chad Perry:**

Right. That's really a foundational requirement that we see really in any company, in any IT system, but particularly in manufacturing and industrial settings where the whole point of using IT systems is to be more productive. So, if you're looking at adopting a system or tool, whether it's online or offline or whatever it is, if it ends up being slower or harder to use, it could be perfectly suited for your business but if it doesn't work it's not a good option.

**Mike Jessop:**

Yeah, that's exactly what was happening. There was more to it when I looked into what the issue was. One was there were lots of calculations and lots of inefficient data going over the connection for these portals, which really just should be showing you data.

**Mike Jessop:**

It should be just like browsing any webpage, and as long as the page is written efficiently that's going to be fast. But they weren't just doing that. They were doing calculations on people's local machines, sending that data backwards and forwards over the Internet before they displayed the data on the screen. So, rather than some external server doing all the work, showing you the results, individual computers were doing the work on our site and then multiple computers were doing the same calculations, sending the same data.

**Mike Jessop:**

But as I looked into it a bit further one of the other issues that was happening ... Well, one of the things was a lot of these systems were running on inefficient servers. So, they were running on things like [ASP 00:08:30] and things like that, which I don't know if ASP has improved or if it's still around now, but back then ASP wasn't the best online system to use if you were wanting speed and inefficiency. It was probably slow, cumbersome, came with massive overhead, needed lots of memory on their servers and things like that.

**Chad Perry:**

Just to clarify here, ASP is just a programming language that has been around for about 20 years. It was used heavily in the 1990s.

**Mike Jessop:**

Yeah. It was a Microsoft language that was built, and that was designed to run on their servers. I don't know for sure, but I think there was a tie in there. If you have to use their servers to run their software, obviously you can buy the software or the software's free but then you need to buy their servers. A lot of these systems have come from Windows-based platforms on local machines, and they've done the similar thing of using the online servers.

**Mike Jessop:**

For the companies providing this it was natural to carry on doing that with Windows because that was what the original software was written in, so they just probably lifted what they had on a basic Windows machine and then they stuck it onto a server machine, probably without doing much more to it other than just making that run for more people.

**Chad Perry:**

You had the luxury of identifying problems at a level of detail that most people wouldn't. But the overall problem that you were addressing was to answer this question of if this software is going to be right for me. What came next? What was your conclusion?

**Mike Jessop:**

One of the issues is when you're a small business you want to get something that's value for money so you're down the cheaper end, which is not necessarily the wrong thing to do. There's great cheaper versions, if it does all the functionality you want.

**Mike Jessop:**

The problem is when you're doing things like reference and wanting support calls to get those references, or put me in touch with somebody who uses it, you're not going to get that at that end. In fact, you're lucky if they'll talk to you real time, especially back in 2010 when you didn't have so many online chat systems. You'll send an email and they might get back to you in 48 hours. You're dead in the water when you're trying to sort that out.

**Mike Jessop:**

The other thing we were finding, we're based in the UK and a lot of them were based outside the UK. The majority of the ones that were the bigger companies, the ones that were more reliable in theory were based in America. The speed connections were slower. We needed real-time data updating super fast. The other thing that was happening was these American companies were doing maintenance regularly in the night. Of course, it was in the middle of the night in America, it was 9:00 in the morning for the UK.

**Mike Jessop:**

So, we worked out our systems were down for an hour plus while they did their nightly maintenance at midnight or 1:00 in the morning, right at our critical periods first thing in the morning. So, you need to always take that into account. If you're online, you want something that's as local as possible, something that's in your country, it's going to be faster, be more reliable in terms of maintenance, before you even start looking at is this going to work for me.

**Chad Perry:**

Yeah. These are fundamental points that you have to evaluate for whether it's going to be worth it to invest in some sort of custom system or to go with a vendor. But anybody who is starting out with any kind of product, or has a fixed set of constraints around their product such as where it's located, how many people it can support, that kind of thing.

**Chad Perry:**

But I know that a lot of small business owners don't have the resources to build their own custom systems like we're about to get into, but they've got to use something and these points have to be addressed no matter who you're working with. Even if you're doing something internally, if you're using Google Spreadsheets or Microsoft Excel or whatever it happens to be, you're still going to have to address these questions; at what point is this going to stop working from?

**Chad Perry:**

Perhaps it would work indefinitely and perhaps there are lots of workaround, some clever workarounds if you don't have a lot of money. But I know you particularly actually had to deal with this when you decided to build your own system.

**Mike Jessop:**

We tried a few of these off-the-shelf packages and none of them were functionally what we needed, or they were too slow, or they were a combination. So, I went back to the system that we knew worked, which was spreadsheets. Obviously they weren't perfect, but it was something that was going to get us by for the time. The problem with Excel spreadsheets, probably a lot of spreadsheets systems, they're single use bits of software. So, only one person at a time can be updating them.

**Mike Jessop:**

What you need as a company is you need several people accessing the data and potentially updating the data at the same time, and your good old regular spreadsheets just can't cope with that. So, ideally you need a database system and they're designed just for that, but that was going to take time if we were going to develop that.

**Mike Jessop:**

What I looked at next was basically a spreadsheet system that can be used by multiple people, and that's Google Docs. You've got Google spreadsheets, which basically are very similar to your Excel spreadsheets. They functionally do about exactly the same, with just a few other things that are just slightly different, interfaces and things like that. That's the next stage I went to. I wrote again these spreadsheets that we'd gone internally and I put them on Excel. I put the Excel things basically online.

**Mike Jessop:**

It's not as straightforward as just uploading them, because you need to connect your spreadsheets together and there was some quite complicated coding involved there at a spreadsheet level. That allowed multiple people to then start using our system, and that did the job great for several months but we ran into more problems after that.

**Chad Perry:**

What did that look like? How did you know, and then what did it look like to actually transition to that? Because you don't just stop using your system and just put in a new system overnight.

**Mike Jessop:**

So, Chad, after about six months there was so much data in these spreadsheets that were cross-referencing and updating each other as data was entered in different areas, different departments. The system started grinding to a halt speed-wise. It turns out that Google spreadsheets, quite rightly so in a way, are not designed to have thousands and thousands of lines of data in multiple spreadsheets. After you get to a certain size, the whole system starts slowing down.

**Mike Jessop:**

The other thing that Google spreadsheets do is they still do quite a lot of calculations on the local machine, so that then can eat this bandwidth up again as the calculations are done. We were finding that people's screens weren't refreshing at the same time. So, somebody would enter data on one part of one spreadsheet which would be cross-referenced by another spreadsheet, and it could be sometime before anybody else actually saw those changes propagate through the spreadsheets. That was down to just sheer size of the data we had, but also it depends how fast your computer is and how fast your Internet connection is on whether you're seeing those updates.

**Mike Jessop:**

What we needed was an online system where the system, whatever it was online, the server basically was doing all the work, was doing all the calculations and was literally just showing you the data. So, your computers were doing nothing and your bandwidth was really low because literally you were just passing a bit of text over the Internet, which is something that's quite fast to do. Not fancy images and things, just like, "Here's the data you're looking for."

**Chad Perry:**

What exactly was it doing for your business?

**Mike Jessop:**

Our system at the time, which has pretty much remained the same in terms of our requirements, we had several sections. We had one called fulfillment and basically that's incoming orders, that's obviously outgoing orders. That also links into production planning. So, you've got a certain amount of stock but an order's just coming in that needs more, you need to be able to look at the plans and say is that stock already planned and if so what day can this order go out, when it's going to be ready. Or, have we not got stock planned that will cover this order and allow production then to plan in to make whatever you're short of. That's fulfillment.

**Mike Jessop:**

We have sales. Now, sales, they pretty much want to see data. They want to see things like an order's gone out, an order's been invoiced, how much value has gone out that month. They want to tweak that data to say what particular product went out, how many products went out, how much is a particular customer ordering. Any variation on money-related, customer-related products, quantity-related information. So, that's sales, fulfillment.

**Mike Jessop:**

We have warehousing. Warehousing needs to track goods in, goods out. They need to know when orders are ready so they need to know when something is shipping out. They need a bit more functionality. They will pre-pack orders onto pallets so they need to know is that order already packed or is it not packed, is it packed and sitting in the warehouse waiting to go out. You have stock issues there because if it's sitting on a pallet waiting to go to a customer, it might physically still be in your warehouse but you can't give that stock to somebody else because it's already allocated, it's already given to a customer.

**Mike Jessop:**

That all ties into really part of our system, which is basically stock allocation. We have somebody whose job it was as orders came in to allocate stock to that order. So, if it was sitting in the warehouse they could allocate straightaway a particular batch order or a particular product, a particular best before date, whatever it might be, and say, "This is for this customer's order."

**Mike Jessop:**

Equally, if there was a production process planned say in a week's time that would cover that stock, they could allocate a portion of what was expected to be made on those dates to match stock. That adds another complication, because production don't always make what they intend to make and they don't always make the numbers they intend to make.

**Mike Jessop:**

So, say we're discussing we needed a thousand of something that was going to be made next week and they only make, you get a hundred short. So, the system's got to be quite clever to track ... What's potentially going to be made and what's actually made are two different things.

**Chad Perry:**

That's a really good distinction to draw. All businesses deal with this on some level. You've got the data aspect where you have to collect data, and you have to some place to put it, and spreadsheets can be a really powerful tool to do that. But also you have to be able to use that data to be productive, and that's really what the whole industry, 4.0, digital manufacturing, is all about. We've got all these systems that are capable different kinds of information, depending on what type of business you are.

**Chad Perry:**

So, you've got productive use of that data. What exactly was it in the new system that you were thinking you would be able to get out of that? Were you looking at just saying, "Look, I want to replace exactly what we have in Google spreadsheets because that works and it's just that Google is too slow," or was there something else, was there a next step or next level that you wanted to take your business to?

**Mike Jessop:**

The first version of what I then did was based pretty much exactly on the spreadsheets. In fact, the Google spreadsheets let me make sure that the system was right and we were collecting the data correctly.

**Mike Jessop:**

It was just literally slowing down, probably sheer amount of data. One of the things we found with the off-the-shelf platforms, in fact most platforms, is they're very rigid and they're not flexible enough. So, one thing that will happen when you get people involved, it's not black and white exactly what's happened. So, you'll have people entering incorrectly, you'll have people not say making the number of products they think they were going to make, they make less. But you've also got real life.

**Mike Jessop:**

So, we were finding one of the things that happens a lot is somebody would enter data incorrectly or production didn't make the quantities they thought they were going to make. So, say production actually made a thousand but somebody mistyped and they only typed in maybe a hundred, missed a zero off the end. They said we only made a hundred of those. Obviously, physically if you look in the warehouse you can see there's 900 there, an extra 900 there. You know they're there, but you've got an order that's got to go out right now and it needs that 1,000. Those rigid systems will not let you ship something that doesn't exist.

**Mike Jessop:**

So, if it's not the system it doesn't exist, even if physically you can see that it does exist. One thing that we needed, we needed an override at that point to say, "Right, let warehouse ship this order. They've got the stock. It's there, they can see it. Yes, the system says we've now got minus 900 because there was 900 missing from data entry, but let them ship it now and then it's somebody else's job to work out why those 900 are missing at some point later."

**Mike Jessop:**

Most off-the-shelf systems are so rigid they don't let you do that. You've got to try and correct the problems first, which leads to other issues, because if there's something that's urgent somebody will just say, "Oh yeah, here you go, 900. There's an extra 900, ship it." Sounds great in theory.

**Mike Jessop:**

Or if you think about it the other way around, if you've got 900 missing somebody needs to investigate. Where are those 900? What happened to them? And if there's 900 more, how did that happen? Because otherwise those errors are just going to keep happening in a business over and over again. You get people bypassing these rigid systems and saying, "Okay, I'm just going to fudge the numbers because they're there. There's 900 there. I don't know why there's missing. I've got 900 here and we're just going to carry on as normal."

**Mike Jessop:**

These numbers mount up and mount up until they basically go, "Wait a minute, we've got this much stock unaccounted there, we've got this much stock that shouldn't exist. Who's doing something wrong?" That was a major problem, the rigidity was actually counterproductive. You'd think it would be the opposite, but it was actually causing more problems.

**Chad Perry:**

One of the reasons that companies go down this road of building their own custom software is because of exactly that. Products tend to be built with this rigidity, it really comes down to a mismatch between the physical world and how the physical world is represented digitally.

**Chad Perry:**

This is something that anybody who adopts any kind of IT system, or specially develops their own, or customizes one that's off the shelf, you have to really have this mindset of what's going on in the physical world that we want to replicate in the digital world, or that we want to track. It's a lot more complicated in situations where you're manufacturing something, where especially with what you're doing.

**Chad Perry:**

You have these mixing tanks with mixed ingredients, and you're selling some of those ingredients but some of those things are also going into finished items. Can you give me an example related to that that really stands out?

**Mike Jessop:**

Yeah. This wasn't addressed until a much later version of the software. In fact, it wasn't really thought about. But in manufacturing, probably to some extent in retail, we need full traceability. If an ingredient comes in, where was it used, when was it used, which product is it in, which customer did they go to? Can you image if there's something wrong with some part of the process, quality control or contamination or anything like that, you have to be able to know where did those things go, recall them.

**Mike Jessop:**

Or maybe they didn't even leave the warehouse, in which case okay, we need to find them all in the warehouse and make sure they never get sent out. So, therefore traceability is really important to manufacturing and probably important to retail but it's a much easier extent, if something goes in it goes out. We have something come in, it goes into one tank, it gets mixed, it gets made into something else, it goes into another tank. So, one of the problems with traceability for us is we'll combine ingredients to make the base chocolate for example, and then we'll pump all that across and store it in big storage tanks. Then those will be pumped off into smaller storage tanks and used in production.

**Mike Jessop:**

How do you track how much of any particular batch say, even if you ignore all the ingredients that went into making it, so how do you track a particular batch of chocolate was made when it goes into a tank because it's mixed with everything else in that tank? In effect, your tank potentially has everything that was ever pumped into it sitting in the same tank, even if it's minute traces. In the real world, you have that problem as well. Okay, where did that batch go? Well, when it goes into this tank in effect it goes out to everybody and you need to come up with a way of managing that in real life and then mimicking it on the system that you use. It's a complex thing you don't really think about to begin with.

**Chad Perry:**

Yeah. Ironically, having come out of the software world, one of the most effective ways I've seen at dealing with that or backing out the representation that you need for your real-world existence, is to try to do it on pen and paper first. If you can do that and force yourself to extract that model, it becomes a lot easier to find a tool to do that for you, or to make one work like Google spreadsheets, or to even build your own.

**Mike Jessop:**

Yeah, that's exactly what we did, Chad. We had clipboards basically with paper on them. And you've got to think first how you're going to track this in the real world, like you say, but it's not necessarily going to work the first way you try it. And even inspectors know there's a limit to what you can do.

**Mike Jessop:**

You've got to just be doing something sensible that makes sense and gives you something that's relatively accurate. There's a few ways, if you just looked at the tank example. One way you could say first in, first out. So, say your tank's 4,000 kilos and each time you pump in 500 kilos of a substance you can literally let that float to the top on your sheet. You say, "Right, when did we use 500? That batch."

**Mike Jessop:**

The first batch you've put in is gone, next 500 takes the next batch you put in. That's one way of doing it, that's a really simple way. Obviously you know you've still got product mixed in there, but that allows you to have that flow of that batch through the system. Another way you can do it, which is more complicated and not necessarily the extreme you need to go to, you could look at the percentage dilution in the tank.

**Mike Jessop:**

You could do some pretty complicated maths and say as you take 500 kilos out what percentage of this particular 500 kilos you put in, compared to what was in the tank, is still left in the tank. There are ways to do it. You need to get it right on paper first, and you need to do what works for you and what works for anybody maybe doing inspections or checking that you're actually doing this. Don't even try and put it into a system first.

**Chad Perry:**

Right, right. The moral of the story is make sure that your representation stands up to the test of time and to doing business, before you even attempt to move that into the digital world?

**Mike Jessop:**

Yeah. That's exactly it. You know what we today, Chad? We carry on using those sheets. It is relatively little paperwork when they pump those things across, so we have paperwork that's not on our system yet which literally tracks that in between stage.

**Mike Jessop:**

There'll be a bit between that's manual at the minute whereby it goes into a tank. We know then what product that batch went in, but in terms of what dilution and how much is left overall and what's classed as been made with that particular ingredient, there's a paper bit there. It can be put into software, I'm just not sure if we've got it right yet. Somebody still has to do the paperwork at the end of the day.

**Mike Jessop:**

So, if you're tracking it on paper, writing it down as it happens, if you're not writing it down somebody's still got to be typing that into a system. The amount of work involved at the input stage, it's probably quicker to write it actually than somebody in production to type it in, because literally you won't have the computer system production environment because they're just going to get covered in chocolate.

**Mike Jessop:**

So, they would have to leave their production environment with their paperwork and then duplicate their paperwork onto a digital system. We just duplicate. Let's keep it on paper until we can find an electronic way of having this real time.

**Chad Perry:**

Yeah. That's the second moral of the story. Sometimes it's not only okay, but it's actually preferable, to have some sort of hybrid manual-digital process to record and make sure that that data works to help you stay more productive.

**Mike Jessop:**

I would definitely recommend that. Don't think that everything has to go digital. We're all about ethics and not wasting paper and stuff, we don't want to waste paper, but they're going to use paper to make the notes of what happened anyway even if they're going to put it in the digital system. So, until we get to the stage where you can of course put your fancy electronic systems and have Internet and WiFi throughout production ... Which doesn't work very well when you've got lots of heavy duty machinery running, the WiFi can be lost among the interference completely from those machines. They're not going to be able to do it straightaway, electronically, in real time anyway so you've got to be realistic about what you can and can't achieve.

**Chad Perry:**

Let's keep going on this journey. You decided that you wanted to replace the Google spreadsheet solution, so you initially built your own system, which I believe you told me it took me it took about a year to replicate what you said in Google spreadsheets. Take me through very quickly what you did in the interim to make sure that that continued to work during the transition period. At six months, you had the system overloaded and it started to crash. Then you decided you wanted to build a custom system. If that takes a year, what happens during that year?

**Mike Jessop:**

Okay. There's two issues when you do that. You've got to have consistency. People can't wait for a new system no matter how long it takes. So, even a couple of weeks they need to carry on using the old system. When you eventually do have a new system you need that crossover of security to know your new system's working correctly, so you need to keep on using the old system for a bit. What we had to do though, because our system was grinding into the sheer amount of data, this is the Google Docs version, I just had to go simple.

**Mike Jessop:**

Basically, I just created a new set of those spreadsheets about every three months and we started them fresh with no data. It was the amount of data that was really causing the problem. That works, but then you end up with several versions of these spreadsheets, so if you wanted to look at something that happened say six months ago you'd have to go back to the previous spreadsheet set. So, you couldn't do a general search over the entire set of data without knowing which particular version of that data you would need. But it worked. It worked for that year. We should set it up with about, I don't know, 12 different copies of the database containing data from several different months.

**Chad Perry:**

That's a good example of an interim solution that a business owner could take, where you know that you're going to have to face the music a year, year and a half from now, but if you can buy yourself time sometimes that is the absolute best option, of course, than having some sort of disruption in your business. Because you really had no other option.

**Mike Jessop:**

No. Something I know from my IT background, never rely on the new software to A; be on time, and B; to work correctly. There's always going to be bugs in any new IT system, you can't avoid it.

**Chad Perry:**

Absolutely.

**Mike Jessop:**

It's not until people start heavily using it that you find them. Sometimes then you don't find them straightaway. So, you need to use your two systems in parallel at some stage as the new one comes online, but that has a danger as well. We went back to people, as I was saying, people still had these Microsoft Office Excel spreadsheets on the go, even though we had Google Docs.

**Mike Jessop:**

Well, when we got to the new system and we were testing them side by side and I said, "Right, now we're going to take the plunge and switch over completely to the new system," some people still didn't trust it, and they were still using not only the Google Docs, they still had their spreadsheets as well. So, at some point you've got to take the plunge, but you'll be surprised when you find out how many people haven't taken the plunge when you start find these secret spreadsheets and things hidden away.

**Chad Perry:**

Yeah. I mean, so often we can think that we have a good beat on what's going on, but that's a perfect way to put it is that there are secret spreadsheets out there. Because people want to be productive, they want to do their job, and if you saddle them with something that doesn't help them do that, or worse, makes it harder for them to do that, then they're absolutely going to look for alternatives and I don't blame them.

**Mike Jessop:**

The problem we had, the mentality we had is ... There was a few things. One is the spreadsheets were what they were used to, so they knew how to use them so they trusted that they could use that better than the new system. The other thing was they didn't trust the new system, but also, anytime there was anything wrong in the new system it was instantly, "It's not working, there's a bug." I could tell you now, 99.9% of the time it was data entry problems.

**Mike Jessop:**

There wasn't a bug, there was nothing wrong with the new system. To start with there was a few little niggles, but they were minor. It was people entering data incorrectly that were causing the problems but then people jumped to the assumption, "The new system's not working. I have to go back to my spreadsheets." That doesn't work because when you've got a really efficient online, whatever system you're using, the system that's really electronic, running from databases, keeping track of everything real time, you can never keep a spreadsheet updated to the same effect.

**Mike Jessop:**

Some staff were relying on their spreadsheets, some staff were using the system, and the two different systems were showing different numbers. That was either because data hadn't been copied across from the system to their spreadsheet, or either on their spreadsheet or on the system somebody had entered data incorrectly. You've got to get everybody using the same thing. That's the only way you find out what's going on with them, whether it's the data that's wrong or if people are using it wrong, or if indeed you do have some underlying issue in whatever software you're using.

**Chad Perry:**

You mentioned something last time we spoke about using what's called EDI. EDI is a very old, I think it dates back to the 70s maybe, maybe even before that, way of two systems talking to each other. So, there was this concept of before the Internet these big companies wanted to be able to be more efficient, they wanted to send their orders electronically to each other and have things go back and forth, like refunds and payment information and all of that.

**Chad Perry:**

So, you've got different ways of bringing in orders. What I want to know about, because what I think is relevant to potentially a lot of small business owners out there who want to work with suppliers, who want to work with larger buyers, is that there might be constraints around how they expect you to deal with them. What was your first experience with trying to get your system linked up to those buyers, and what prompted you to go down the road of using EDI?

**Mike Jessop:**

Okay. Orders come in, and still come in to this day, in several different formats. You've got people phoning orders in, you've got email orders, you've got online orders coming in. Until recently we still got some fax orders, but I think thankfully that's stopped now. We didn't have a fax machine, we had a special online system set up which would convert any fax into an email.

**Mike Jessop:**

So, we didn't invest in a fax machine, thank God. But then you've got the bigger companies that use this EDI system. EDI is a bit like an advanced fax system but it's electronic. Basically it does a lot of confirming. So, an order will come in from a big customer, say a supermarket. The system then will send some messages internally backwards and forwards saying basically, "Here's the order. Have you got it?" And then the system will automatically reply and say, "Yeah, got it, I understand it all," or, "No, I'm missing a bit, send it again."

**Mike Jessop:**

It makes sure that nothing's lost. Like a fax system, somebody might be out of ink or something like that, you might not get part of the order. The system checks all that. But you've still got your order then sitting on this electronic app form which is completely independent to anything else, and for us it still is. I wouldn't suggest trying to integrate your EDI with your system, because if you think about all the other ways you get orders, via the Internet, via telephones, via emails, somebody's got to copy that data across into your system anyway, that order.

**Mike Jessop:**

So, you may as well just copy that data across internally onto your internal system as well. You'll still need to do a few things on EDI. You'll need to say, "Yes, I'm fulfilling this order, this order's gone out," or, "Here's the invoice for this order." That still has to go across EDI, but don't try and integrate that with your internal system. There's no point because of all the other ways [inaudible 00:35:57].

**Chad Perry:**

Are you using EDI in a separate tool? Did you build that tool, and was that a requirement of working with some sort of new, larger customer that you wanted to work with?

**Mike Jessop:**

Basically you're forced to use EDI. A lot of the big customers will only send orders and invoices and everything else related to those, all your invoices go to them through EDI. You don't have any choice. But when you get an EDI system, there's some that are very expensive. For somebody like us which is, I don't know, we've probably got half a dozen, just over, people that use EDI, you don't need this big, fancy, complicated system.

**Mike Jessop:**

If you're a major manufacturer sending out millions of orders every year, yeah, maybe you'll need one of the big fancy, expensive things. But for your average manufacturer look online. There'll be some nice, cheap, affordable online systems that you log into to check your EDI on a daily basis or an hourly basis. Do everything through that and don't try and get too complicated with that.

**Chad Perry:**

That's what you guys did?

**Mike Jessop:**

That's exactly what we did, and that's what we still do. We work with a relatively little company rather than one of these big multinational people, because they're not set up for our level these big people and they'll charge you ... The fees, they'll be ridiculous. The fee per month will be more than probably the amount of all the orders you would get in through the system anyway, or a good chunk of your profit from those anyway. So, you need to look at how much is this costing me relative to how much money I'm actually making through these orders.

**Chad Perry:**

Right. Yeah. This is a great example of taking bits and pieces of systems or small tools out there and weaving them together into something larger and more useful that suits you. In this case, you may have had more familiarity with EDI than the average person, but your solution was still the same. You're not going to go out and build your own EDI system because that problem has been solved and it's been solved thoroughly. As you put it, there are tools out there that are made for smaller businesses, where it might not be worth it to have that tool completely integrated into your system. And that's fine, you could operate like that indefinitely, if it makes sense financially.

**Mike Jessop:**

Yeah. That's experience right. The only thing would be scale. If you did get into hundreds of thousands or millions of orders a year, then yeah, you've got to have some pretty hot system. But then you've probably got the money to afford those systems if that's the kind of volume of orders you're shipping.

**Chad Perry:**

Right. And that kind of thing doesn't really tend to happen overnight anyway, so you can scale people, you can scale, essentially replicate a human logging into a system and clicking through, and you could basically brute force an integration instead of integrating them at the database level.

**Mike Jessop:**

Yeah. Can I just say one thing though? I probably wouldn't ever go to that level. One thing you must always remember with any system like this is people can often do it better, but often the reason is they're slower.

**Mike Jessop:**

So, you get an IT system or computer system or whatever to do it for you. Don't forget about that. Always look at the cost. Whether it be cost of time or whether it be cost of money or both, don't go, "Okay, I'm going to pay an inordinate sum of money to get this integrated with my system and it's only going to save me this many minutes a day, which, if I take somebody's salary into account it's going to cost me pennies."

**Mike Jessop:**

Do the maths, and do expect the IT costs, especially if it's custom-built software, to be much more than you think it's going to be when you begin. Often, little bits like that, get a person to do it, part of your job. Especially for a small business you'll probably find it's a much cheaper and more efficient way of doing things.

**Chad Perry:**

Yeah, great advice. All right, so on that note I think that there's one last thing that we want to explore. I really wish we could go into more detail about a lot of this stuff. At what point you went down the road of setting up an e-commerce, and if there were multiple iterations of that, and where you are now.

**Mike Jessop:**

We had an e-commerce presence from day one. We were from a web development background when we started our company, so from day one we had a really good website as a manufacturer. You would find at the time we launched that most manufacturers even, A; didn't have a website, or if they did it was either just one page or you couldn't even find it at all in a search engine.

**Mike Jessop:**

So, that was crucial to us, and that got us a lot of business immediately really from the start because people could find we were making these products and selling these products all around the world so we were shipping overseas. But one thing we were good at is we wrote those systems, we wrote those e-commerce systems, and at the time we started there wasn't really good off-the-shelf package like there is now you've got lots of options for good e-commerce platforms. So, we were basically running off our e-commerce systems that we'd wrote for retail, and we were using that so that customers could actually place orders for wholesale stock. The problem still though with that is the bigger boys, the multiples and things, are not going to use your personal online system.

**Mike Jessop:**

So, again you've got to look at how much you're going to invest if you're going to get that system created yourself because only the little customers tend to use that. It is more cost-effective usually than a person on the phone, taking a small order that may only be worth a hundred pounds or something like that. If you look at their time it might be like this is costing me £15 for somebody to process this order. When the order and somebody's put it on the pallet and is shipping it out, it's going to need more paperwork. It's much more efficient if a system does those smaller orders.

**Chad Perry:**

At what point did you move on from your old system? Because I know that you have something now built on Shopify. What was the transition point and what was the reasoning for that?

**Mike Jessop:**

Okay, so the development for this went backwards. We started off with a custom system, processing credit cards, taking payments. It tended to just be retailers would use the system, because any wholesaler would tend to probably send their order through on an email or phone up, and again they wouldn't be using the system. So, it's for your low value orders which are bigger than just an end consumer buying a couple of chocolate bars, but not big enough really for anybody to spend a lot of time processing the order just because the return on the order wasn't big enough.

**Mike Jessop:**

We started off that way because there wasn't any system around, but over the years when we get to 2020 there's a lot of really good online retail systems. They have basic stock control, which you could use for your resale side, built into them. They're very portable. They've got lots of apps and things you can add into there to give you that functionality. So, we went backwards. We created our own system initially, and now we're actually put everything over onto Shopify now. We moved our final system over a few weeks ago onto a version on Shopify sites.

**Chad Perry:**

Was that a pretty smooth process? Because I know you said that you had essentially gutted parts of it to make customizations. What was the reasoning behind that?

**Mike Jessop:**

Okay, from an IT background and from a web development background, I looked at what the basic package was that we got. It can be slow, it maybe isn't quite what you like, it doesn't display the data.

**Mike Jessop:**

Sometimes it doesn't display things in the best things to sell them. Our consumer-facing site, for example, we need to encourage you to be interested in looking at a product before you'll even consider buying it, and if you're not showing that information correctly or you're not making it really easy to add to your shopping cart, or if you've added it to the shopping cart but then you can't the shopping cart, you lose the customer, you lose the order. What I did was I basically pulled a lot of that code apart, wrote my own custom apps in there, and made those things clearer and made them work more smoothly.

**Mike Jessop:**

It's not that the basic package is not good, it's just the basic package isn't great. We want great, we don't want good. You could start off on that basic package by all means, but if the sales just aren't coming through in the way you'd expect then do consider that you might need some customization put into that.

**Chad Perry:**

Yeah. If you weren't able to do that yourself and you were facing having to pay somebody else to do that, your priorities might be a little bit different. But it sounds like your main priority would be is it going to increase conversions or increase the willingness of a customer to buy?

**Mike Jessop:**

Yeah. If you're actually selling something, your key is you want to sell as much as possible. So, anything you do should be looking at is this going to sell more, is it selling more, and is that cost of what everyone invested in having this added worth the return I'm now getting on increased orders? One thing is people need to be able to find your site on a search engine. That's all SEO. Search engine optimization. You might need that tweaking. You can do a lot of that yourself, but you might need somebody to five you some pointers to what exactly that means and what you should be doing. Shopify will allow you to that, but you really need to know what you're doing to make the best use of it.

**Mike Jessop:**

Then the next thing is there are a lot of people out there, companies and private individuals, especially on a well-known platform like Shopify, that will actually do these modifications for you. I've never used one myself. I think they're affordable, I don't think they're crazy prices. On top of that, you've got a lot of plug-ins you can buy, pay on a monthly basis. If you get a plug-in you'll get a trial usually. If it seems to be working, go onto a monthly subscription, and then if you find it's not what you want at least you've only paid a few monthly subscriptions and not actually bought it outright.

**Chad Perry:**

The most important thing there being understanding what it is that you need, what's going to have the highest payoff so that you can at least some sort of return no matter what your price point is.

**Mike Jessop:**

Yeah, that's right. One of the first critical thing you will need is the site looks like professional, it needs to look enticing, and it needs to look something that people are familiar with. You can do all this yourself, but if you're no good at it you might want to get somebody to just create you that look. There are a lot of off-the-shelf ones, but maybe just tweaking it a little bit if you think it's not quite right. Ask people's opinion. Don't just ask your family members, they might tell you it's great.

**Mike Jessop:**

You need to find somebody who's [inaudible 00:45:49] objective. So, either a family member who's going to give you an honest opinion, or for existing customers and things like that get their honest feedback. Don't just go on any one person's feedback, take everything into account and use your own opinion as well. But do listen to them. You're going to get people differing on their views, but you need to work out what's the crux to what's wrong on my side, what needs doing, or is it okay.

**Chad Perry:**

Now, you mentioned earlier that wholesalers are not really that likely to buy on your original retail site, but you have in fact recently released a new wholesale e-commerce portal. So, what's going on there?

**Mike Jessop:**

Okay. That's facing at retailers though. Retailers can now buy direct from us from our factories. The main reason we did that was, there were two reasons. One is the bigger wholesalers often didn't carry enough stock so they were selling out a lot of product and then customers were unable to ... They were putting an order in and then their order was arriving but there would be items missing. And we actually got customers phoning us up thinking we'd got manufacturing problems because their wholesaler was always out of stock of particular things. We hadn't, it was just that the manufacturers were under stocking.

**Mike Jessop:**

A lot of these wholesalers, as well as the multiples, they have automated systems that keep track of stock and sales and they order accordingly. Even if there's a manual processor, an individual doing that, they will look at the sales data. So, you can imagine that if you don't have enough stock to sell something you won't sell it, therefore your deep data seems to show that it doesn't sell very well. This is an issue with their system as well. They think they don't get many sales, but actually they could have turned away thousands of sales that they didn't get because they didn't have the stock.

**Mike Jessop:**

So, we wanted retailers to be able to get that stock at any time so they can come straight to us, they can get absolutely anything at any time. In fact, on that system we don't even track stock. We never have anything on there that says we've only got two boxes of this left. Because we're a manufacturer we can make that almost instantly if we need to. So, everything's always in stock. The only things that will vanish are say seasonal where obviously there's a finite limit, and as soon as it's all gone we just take it off the site. We don't try and do any sophisticated stock control on there.

**Mike Jessop:**

Our internal system tracks that that stocks being sold on the Internet or however it's done. But we don't try and use that retail e-commerce system to track that because, A; we'd have a disjointed system because our internal systems are tracking it anyway, and B; it misleads customers, because it might look like you've only got so many left but actually the next day you might be making another thousand.

**Mike Jessop:**

The last thing that happens is when you get somebody looking after those systems they often forget to update the stock numbers. An e-commerce will often look like you're out of stock of something just because somebody's forgot to put some stock on or not noticed it's gone out of stock. They've typed the wrong number in and before you know it you're not selling something just because your site's saying you're out of stock and you're not.

**Mike Jessop:**

So, if you're a manufacturer, try and turn that system if you can cope with manufacturing extra things. By all means let your customer know. If it's going to be a couple of days to make that product for them let them know, because there's nothing worse than being a customer and wondering where your order is. Let them know. Say, "Look, we're out of stock. It'll be back in a few days. Are you okay to wait?" It's just about customer-

**Chad Perry:**

Yeah. That falls firmly in the category of making it easier for customers to buy from you. I tend to think of the digital transformation, the whole digital journey, in terms of where you're making substantial changes to your business in terms of productivity. The most obvious one for a lot of people, a lot of manufacturers I think start with, "Well, I need to see my production data. I need to know what's most profitable, what's losing money, and just be more productive in general."

**Chad Perry:**

But there are also other aspects to that, like making it easier for suppliers to serve you, and then on the front end of your business you want to make it easier for money to come into your business and the best way to do that is to make it easier for customers to buy from you. And all of these little ways that you've just mentioned, depending on how customers or expecting to interact with your business.

**Mike Jessop:**

Yeah. That's your primary concern, is don't let your system slow down. Going back to what we said initially with these systems tracking what stock do we have in the warehouse and somebody's not put the data in correctly. You don't want to stop an order going out if that stock literally you can see it, it's there. Ship it. I don't want to slow this down.

**Mike Jessop:**

The same thing happens on e-commerce. You don't want people not to be able to buy something just because somebody's forgotten to mark that an item's back in stock. Especially when it's busy, that's when that's more likely to happen, people just don't notice or don't have time to notice that that's still out of stock. And they're so busy trying to fulfill the orders that you can actually lose orders as well.

**Mike Jessop:**

It's much easier to employ or throw a few more staff members at something when it gets busy to cope with extra orders. There's nothing worse than losing orders when you have the stock to shift, it's just a matter of somebody's forgotten to press the right button.

**Chad Perry:**

Yeah. That's a pointed lesson. Don't lose track of the reason that you're digitizing or adopting tools in the first place. It is to ensure that you can sell and be more productive and deliver on your promises.

**Mike Jessop:**

That's exactly what you need to be thinking of. Return on investment all the time. Is the money that I'm investing in this system worth the return I'm getting from the system?

**Chad Perry:**

Yeah, yeah. So much easier said than done, right, when you're in it day to day?

**Mike Jessop:**

Oh absolutely, yeah. You need somebody looking at the overview of this and keep analyzing it because it might change. You might think something's not efficient at one point and it becomes efficient later. Or it might switch the other way round. Something might be efficient to begin with and then you're actually, "Wait a minute. This is better done manually on paper at this stage, at least while we put something else in place that works better."

**Chad Perry:**

Yeah. I agree. Well, Mike, I think that's a good place to wrap up. Thank you so much for everything that you've shared with us. I would leave our listeners with two more questions. One is, if there's one thing that you can share that our listeners should know about or should be thinking about that you think is the most important thing when going down this road, the digital journey. Then also how to get in touch with you if they want to.

**Mike Jessop:**

Okay. I want to give two points of advice. One we've just mentioned. Return on the investment. Always look at how much something's going to cost you compared to what it's going to save you or what it's going to make you. And if it's an IT system you're having custom-made for you and you get a price for that system, just bear in mind it'll never be that price, it'll never be available on the day it's supposed to be, it'll never work straightaway. So, remember all that.

**Mike Jessop:**

That leads onto my second bit of advice, which is you learn more from your mistakes or other people's mistakes than anything else. You are going to make these mistakes, you are going to invest in something that probably worth that amount of money, or you needed it on a particular day and it didn't arrive. It's going to happen. When it does happen, just try and work out how or why it happened and either build that into the next time and go, "Okay, I know this isn't going to be available on this day." If it is great, but just assume it's not and just learn from those issues.

**Mike Jessop:**

Finally, if you want to get in touch with me, if you go online and find our website moofreechocolates.com. If you just use that same URL and send it to mike@moofreechocolates.com, I'll be happy to try and help with any basic questions you might have. I won't be doing development, I've moved on from that, but I could probably give you a few pointers.

**Chad Perry:**

Yeah. That would be mike@moofreechocolates.com, like moo as in the cow, milk free, so free, chocolates.com.

**Mike Jessop:**

That's right, yeah. If you can't quite get that right, if you're unsure if you're typing, just look up our website. Just look for Moo Free. You'll find our website. Stick my name in front of the URL @moofreechocolates.com and away you go.

**Chad Perry:**

All right, Mike, thank you so much.

**Mike Jessop:**

Thanks very much, Chad. Thanks for putting up with me.