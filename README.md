# ortsoc-opinion-piece

This opinion piece is inspired by Jeff's review of the MECOP internship program, which can be found [here](https://github.com/solderq35/mecop-opinion-piece). My goal here is to be a bit more neutral in my review, but I think it is silly to claim that I am unbiased. Because the ORTSOC involves a confidentiality agreement, I will be more sparse on details, and any technical information given here is information that could already be found on the [ORTSOC website](https://web.archive.org/web/20231030164257/https://ortsoc.oregonstate.edu/students). This isn't a leak.

There are a few reasons why I am writing here. SLE reviews are never seen by other students, and Ratemyprofessor reviews can be written by anyone. Although this review is my own personal experience, I have discussed with other people, and while I won't be sharing who, I will incorporate what they have to say in this opinion piece. I am aware that this will likely be read by the ORTSOC mentors at some point (I am unsure whether they would wish to retaliate or not), and this piece has been written with that understanding. Like Jeff, I also have ADHD, so some things may come out more blunt or harsh than I intended.

Thanks to [Yeongjin](https://www.unexploitable.systems/) for helping me with a lot of this and giving me a perspective from someone highly experienced in the industry, and to the many others who were willing to give me their honest opinions.

**This is not intended to be a rant, rather just things I wish I had known before doing the capstone, and hopefully it will inform other students before they do it.** I'm not suggesting I have solutions to have all of the problems listed here either. Running a SOC with 25 students certainly is a challenge.

## Overview
The ORTSOC claims to be the nation's first cybersecurity teaching hospital. We will evalulate this claim further on. With the current tight job market, students are looking to bypass the previous experience paradox, where companies are unwilling to spend the money to train new graduates on the job. Catering to this concern, the ORTSOC offers students a lucrative deal. This is to say, students can take the course and get nine months of free work experience. ORTSOC students do **not** get paid, however the total combined salaries for the full-time mentors is around $400-500k, plus a few GTA/GRA positions for graduate students. From my understanding, most of the money goes to the administrative overhead of running the ORTSOC. This is using the publicly avaliable salary information. For students, it is work experience to put on their resume. For the ORTSOC, it is dirt cheap labor.

There was, according to someone I talked to, a dispute over if students should be paid for their ORTSOC labor. To my understanding, the idea was shot down.

This is mostly aimed towards students who are deciding if they should do this capstone or not. I can't tell you if you should take it or not: this you will have to decide for yourself. The goal here is to give information that will be helpful to someone making the decision. Overall though, I would say the quality of the program is on par with the OSU CS program as a whole. It is not exceptionally good, nor exceptionally bad, when compared to the rest of the EECS department.

I have also heard there are plans to offer a doctorate level degree. Given that the ORTSOC's director doesn't himself have a doctoral degree (his academic experience is as an English major), I am not sure how he plans to make this work. I'm not trying to be an academic elitist here. This is just what I've heard  from other faculty. 

## Positive Things
* Put experience on your resume
* Real penetration test of a client, potentially
* Guest speakers, though they are usually not announced in advance so you cannot figure out ahead of time what you would want to ask.

## Rotations

ORTSOC is a three quarter capstone program. As you might have imagined, since the program is themed after a teaching hospital, there are clinical rotations. You get assigned to a rotation, and you do that particular rotation for a few weeks. From the ORTSOC website, some of these rotations are:
1. Network Security Monitoring
2. Threat Intelligence
3. Security Engineering
4. Cybersecurity Assessments
5. Threat Hunting
6. Penetration Testing

During this time, you provide SOC services for the clients of the ORTSOC, which the ORTSOC website calls "under-served organizations across the region". You would be expected to work 10-12 hours per week. You will be asked to submit your schedule at the beginning of the term, but you don't get to sign up for shifts. This means that if you can't make it to a 7:00am shift for whatever reason, you should not leave this marked available. There is also a one hour capstone class, with required attendance.

For graduate students, there is a reading group that meets after the capstone class, with what I assume is an associated seminar. 

## Making it count for credit

To be able to take the course, you have to enroll in a special [security operations track](https://drive.google.com/file/d/10nyKXrlQfB4jdqP7oP24PeGc_RYz6EH3/view?usp=sharing). If this doesn't line up well with your current coursework, then this is very important to consider before deciding to do ORTSOC. The advisors may give you certain advice. Some of it is probably accurate, but as always make sure to verify information they give you.

## Environment

The ORTSOC is an in-person SOC. This means that anyone interested in taking the course, to my knowledge, would not be able to work remotely. This is in contrast to other SOC jobs which do allow this form of work. Additionally, if someone has to miss class, the only option is to make up the missing hours, with no option for remote work if sick. The reason for this is likely the same reason many companies are forcing their workers back to the office. It is far easier to stand over someone's shoulder and monitor what they are doing when they are working in-person. 

In terms of work environment, it is strict. Personally, I was sent an email one time for leaving seven minutes early, and I assume time spent packing up was also incorporated into this. I have heard other students have not run into this particular issue, but I can speak only from my own experiences. You also cannot get caught with your phone out, or you will lose points. If you were working on one assigned task and something more urgent came up, and you decided on your own to investigate that new issue, that would be insubordination. From my experience, the communication between mentors and students has not been the best either. Usually, communication is highly indirect, and if you were to do something wrong you wouldn't hear about this until at least a week or two afterwards. Some I have talked to question if going after students for such minutiae is harassment. I don't have sufficient experience to speak to if this is the case or not. Student communication is usually good though. Personally, all of the other students I have worked with have been wonderful. From other students, I have heard that they have often been left with little direction on how to get started, and then a mentor comes in and questions why little is getting done.

I think the main paradox of all of this is that they are trying to create an environment of trust in what the ORTSOC considers a zero-trust environment. You can only have one, and not both. In the case of the ORTSOC, distrust prevails. The reference to "zero-trust" in this case refers to my own observations of the working environment in the way that mentors treat students, and not a specific security policy of the ORTSOC.

Why is all of this a problem? Well, to run an effective SOC, or any workplace in general, you need a positive working environment. It is natural to not want to trust college students who are new to security operations, but there are consequences to such a take. 

## Is it a teaching hospital?

The short answer is probably not. For the ORTSOC to be a teaching hospital, it would need to be providing some sort of real value to its patients. While I can't get into details of specific incidents, most of what happens is security theater. If you are not sure what security theater is, consider your experience going through airport security. Does limiting the amount of liquids you can bring through the scanner offer real security, or is it just made to make people feel secure? This is mostly how the ORTSOC runs. The intentions of the ORTSOC are good, and a lot of work seems to have went into developing it, but most of the day-to-day activities seem extremely contrived. In hindsight, I wasn't able to see this, but in a college course there is an information asymmetry, and students blindly trust professors when it comes to the field they are teaching. This isn't their fault of course, because students aren't expected to be masters of the subject going in. So, if you were someone reading this and thinking "it can't *actually* be like this", just know that I was once in this situation too. To be honest, this type of person is mainly who I write for here.

Now, if this were the case, why would anyone want to purchase the services of the ORTSOC? Consider the fact that it looks better on a Cybersecurity Insurance policy when the organization has a SOC. Now consider the amount of money saved. Until, of course, there is a major incident, and the insurance company and the client is left wondering what the hell happened. This is just a hypothetical, and I am not referring to any real incident here.

Because of this, I have heard from others who have finished the ORTSOC program that when they go out and do real security operations, they are in for a serious wakeup call. A certain amount of class consciousness is necessary as well to understand. *You* are the one paying *your tuiton dollars*, and the practicum is 4-5 credit hours per term. You may even be taking out mountains of student debt. To those considering this program (as well as current students), this is critical to remember.

## If you have feedback on this opinion piece
PRs and issues welcome :)

![Drunken yeongjin](https://github.com/robert0004/ortsoc-opinion-piece/blob/main/drunkjin.jpg?raw=true)

*You, sometime in the future hopefully*
