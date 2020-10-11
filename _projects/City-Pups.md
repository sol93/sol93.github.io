---
title: City pups: a hypothetical UX design sprint
subtitle: A 5-day design sprint modeled using GV's sprint methodology, conducted using a prompt provided by BiteSize UX.
date: 2019-07-24 00:00:00
description: 
featured_image: CP-screen3.png
accent_color: '#4C60E6'
gallery_images:
  - GLOBE-affinity-map.png
  - persona.png
  - sitemap.jpeg
  - first-sketch.png
  - V.1.png
  - V.2.png
---

#### The design sprint prerogative

Dog owners of strong moral fiber will recommend that you adopt, don’t shop. But, adopting a dog in the city can be tricky. As any dog owner will tell you, the right dog normally chooses you. But, not everyone has quick access to a yard, and living spaces can be cramped, especially when you add a 60+ lb dog into the mix.

So, during this 5-day design sprint for Springboard’s UX Design career track, I set out to create an original solution for a hypothetical start-up called City Pups, a dog-adoption experience that could help those living in cities find the perfect pup.

Whenever I begin a design, I start with a specific intent. Research is very important to me because I aim to solve a problem. In this case I found that current adoption experiences don’t necessarily identify if a dog is a good fit for someone’s lifestyle. They do help potential owners figure out what they want their dog to look like, but not always what they may act like. Also, I believed that letting users choose between dogs that were potty-trained or not was critical.

#### My solution

I set out to make a desktop dog-adoption experience that was love at first sight. But, the UX would make users aware of the fact that their lifestyle played a significant role in what dog they should adopt, and matched a dogs personality to theirs even before they met.

The goal was to help users find their dream dog in the first try. I imagined a speed-dating scenario where users can search according to their specifications, or according to the specifications of their dream dog. And, an interactive map that shows users dogs in their area that match their needs.

#### Research findings

I found that the four most important points of consideration when adopting a dog are:

1. Love at first sight, access dog photos ❤️
2. Dog temperament 🐶
3. Energy level 🐕
4. Whether it’s potty trained 💩

These findings were gleaned from the recording of one user interview with Jennifer, and quotes from other research participants. Jennifer was a part of the user consensus, and she also brought up a unique secondary factor when adopting a dog, and that was whether the dog was a barker. Jennifer lives in a crowded apartment building the same as many other New Yorkers, and she doesn’t want to bother her neighbors.

Interestingly enough, my competitive analysis was slightly incomplete. I only found out after I finished my sprint that Petfinder had a very similar onboarding experience, though it still only matched users to dogs that displayed their preferred physical characteristics.

Petfinder also includes the very crucial question, “How important is house training?” I’m glad we thought along the same lines.

Petfinder had some delightful response options that I wish I emulated. I also loved their steps progression. Petfinder has a very similar color palette, too. It’s a great solution, but it doesn’t think big city.

![](/images/CP-petfinder.png)

This is a step in Petfinder’s onboarding. As we all know, house training your pup is one of the most important parts of dog ownership. And, it’s a very important question to ask. Some may not want the stress of dealing with accidents along the way. For those users, an older dog is more probably more preferable.

#### Ideation

Especially because this is a city-based solution, I went with an interactive map as the main interaction screen. And because I figured, who doesn’t like playing around with maps? It could be an educational resource for dog owners as well, showing them things such as shelters in their area, dog parks, dog-friendly places and veterinary clinics.

![](/images/CP-sketch1.png)

This was my initial sketch of the user flow, showing the most important screens of the UX. First, we make it about the user, and then about the dogs, then getting the two to meet.

#### My crazy 8s

Next, I was tasked with conducting Google Sprint’s crazy 8s sketching exercise to iterate the main interaction screen several more times. I found out that it’s really hard to do as just one person. And, I’ll be honest, I was very married to my idea (hypocrisy!).

![](/images/CP-crazy8s.png)

What I learned from sketching eight different iterations of the same screen was that it felt tedious until I saw it as an exercise in representing information through different visual and procedural affordances. Basically, it was eight different hows but with the same why: to let users choose the temperament and energy level of the kind of dog they want, and whether that dog is already potty trained or not.

#### Prototyping

Although I was married to my initial idea, I was grateful for having done the Crazy 8s because I took specific design instances from a few sketches and incorporated them into my final design.

Here are a few key screens:

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/CP-screen1.png,/images/CP-screen2.png,/images/CP-screen3.png
	"
%}

#### User testing

I interviewed five people: Amie Gallagher, Eunice Pereyra, Kamali Davis, Richard Ludescher, and Lisa Markov. These are all friends and family. Though, Ms. Gallagher was a friend of my mothers. All are dog lovers, and my girlfriend Eunice is actually from NYC so she can relate directly to owning a dog in the city and what makes it different from suburban dog ownership. I tested at my house, my public library, and at my friend’s house.

#### City Pups task prompt

You recently moved to the city, and after settling down decided life was a little lonely. You want a dog, a small one that you can raise yourself. You like bundles of energy that are filled with curiosity, and you don’t mind taking the time to train your little fur baby.

{% include post-components/video.html
	url = "https://www.loom.com/share/722f953de8a04ff396f68c68176a6cf8"
	full_width = true
%}

#### Findings

Users seemed to enjoy the experience. The task prompt helped them narrow their answers down, and they didn’t feel confused at all. They thought it was interesting to see an option that categorized dogs by personality such as “submissive,” “inquisitive,” or “independent.”

Here are specific findings:

1. Two users went right to “See all the pups!” and after they went through one time, I had them click the other CTA to go through the experience of narrowing down their search results.
2. For the question asking users if they preferred a dog that was already potty trained, a couple of users felt that I should have included an option called, “it doesn’t matter.”
3. Two users didn’t quickly realize they could expand each dog’s bio by clicking the downward arrow.
4. Three users wished that clicking on the location identifier on the map brought them to that dog’s bio listed on the side. Right now, only clicking the dog’s bio will bring the user to that dog’s location on the map. Allowing two-way functionality is important, and I just didn’t prototype that functionality into InVision. If I got a second round of user testing, I’d definitely do that.
5. People liked the color palette. I just took the City pups logo and re-used the purple, then took a contrasting yellow for CTA’s.
6. Two users also requested a mileage radius among the filter choices at the bottom of the map.
7. One user requested a dog’s medical history. Duly noted.
8. Last, but not least, several requested photo albums of each dog, if possible. Gotta love it.

#### For future iterations

* Under the potty training question, I’d add a third option similar to PetFinder’s, which Ms. Gallagher recommended as well disclaiming, “it doesn’t matter.”
* I’d make reading more about a dog’s bio for identifiable.
* I’d give the map two-way functionality. At the time of my test, I didn’t let users click on marks on the map to show which dog it was. It was a simple prototyping mistake.
* I’d add a mileage radius
* I’d add dog medical history
* And last but not least, more dog videos!