# WBTC2015
This repository is written in the module Web Technology at Bern University of Applied Science, Bachelor in Business Information Systems 

## Exercise 2
The task for exercise two was to design RDF serializations in Turtle. 
Create a list for following statements: 
- list of accounts on the web 
- list of relationships 
- list of interests 
- list of accomplishments (work experience / education)
 
The post is based on exercise one. 

- @base <http://www.nadineneuen.ch/>
- @prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
- @prefix foaf: <http://example.org/foaf/0.1/>
- @prefix hobbies: <https://www.wikipedia.org/>

##### web accounts
<http://nadineneuen.ch/aboutme> <http://xmlns.com/foaf/0.1/accounts> <https://www.facebook.com/nadine.neuenschwander.3>
<http://nadineneuen.ch/aboutme> <http://xmlns.com/foaf/0.1/accounts> <https://www.flickr.com/photos/nadineneuen/>


##### relationships
<http://nadineneuen.ch/links> <http://xmlns.com/foaf/0.1/knows> <https://www.facebook.com/dena.sargent.79?fref=ts>
<http://nadineneuen.ch/links> <http://xmlns.com/foaf/0.1/knows> <https://www.facebook.com/genevieve.scharer?fref=ts>

##### interests
<http://nadineneuen.ch/intrested_in/hobbies> <http://xmlns.com/foaf/0.1/interests> <http://en.wikipedia.org/wiki/Skiing>
<http://nadineneuen.ch/intrested_in/hobbies> <http://xmlns.com/foaf/0.1/interests> <http://en.wikipedia.org/wiki/Squash_%28sport%29>

##### accomplishments 
<http://nadineneuen.ch/experiences/sbb> <http://xmlns.com/foaf/0.1/experiences> <https://www.sbb.ch/en/group/sbb-as-business-partner/offers-for-rus/telecom.html>

<http://nadineneuen.ch/experiences/migros> <http://xmlns.com/foaf/0.1/experiences> <http://www.migros.ch/de.html>

##### education 
<http://www.nadineneuen.ch/education/bfh> <http://xmlns.com/foaf/0.1/education> <https://www.bfh.ch/en/startseite.html>
<http://www.nadineneuen.ch/education/wmb> <http://xmlns.com/foaf/0.1/education> <http://www.bwdbern.ch/bwd-wmb/>

##### travel 
<http://www.nadineneuen.ch/travel> <http://xmlns.com/foaf/0.1/travel> <https://www.gadventures.com/trips/bangkok-to-singapore-on-a-shoestring/ATRM/2015/>

## Exercise 1 

The task for exercise one was to design IRI patterns for a dataspace on the web (own profile). As well as describing why the IRI patterns were chosen like this. The second part of the task was explaning in a short summary what "Linked Data" is, that a five year old would understand.

### Design my own IRI patterns

I have chosen the following URI because it is a combination of my given name and my lastname. I have decided to take the top-level-domain ".ch " because I feel most to related to it (as I am Swiss, and lived here since I have been born)

- http://www.nadineneuen.ch/home
- http://www.nadineneuen.ch/aboutme
- http://www.nadineneuen.ch/education
- http://www.nadineneuen.ch/education/bfh
- http://www.nadineneuen.ch/education/wmb
- http://www.nadineneuen.ch/experiences
- http://www.nadineneuen.ch/experiences/sbb
- http://www.nadineneuen.ch/experiences/migros
- http://www.nadineneuen.ch/interested_in
- http://www.nadineneuen.ch/interested_in/hobbies
- http://www.nadineneuen.ch/interested_in/it
- http://www.nadineneuen.ch/travel
- http://www.nadineneuen.ch/contactinfo
- http://www.nadineneuen.ch/links

I have definied the URIs above because I think it is covering already a lot of possible infromation. The /home page is the first page of the website. In the /aboutme section there is space for the relevant information about me and my life. The part /education and /experiences will cover my school and working background and my achievements, the different schools as well as companies I've worked for are covered with subcategories. The part /interested_in gives space for my hobbies and things which interest me (like books, newspaper articles)--> subcategories as well. The /travel section is provided for travel informations (like a blog, to share the most beautiful experiences). On the /links page there is space for further information which I like to link.


### Linked Data for a five year old

First of all I should explain you, what the World Wide Web is. So when your "Mum" is sitting in front of the computer, she is probably using the World Wide Web. The world Wide Web contains hundreds of billion pages. This pages were uploaded from people all over the world, as the name is saying. The pages contain informations, descriptions about a specific topics or even pictures/videos and graphs. At the end the World Wide Web is a network of computers, which are connected. They are sharing the uploaded information with everyone, doesn't matter where you live. You don't know what a network is? A network is a group of interconnected people. For example your school class is a network as well. In this case the computers are the network.

The pages on the world wide web is for everybody. It is very useful to share the knowledge with all the people in the world, it is a big advantage for everybody when they find a lot of information about one topic in a short time.

Let's say your "Mum" is looking for information about "Party Games", because she is organizing a Birthday Party for you. She wants to find as much information as possible. How is this working? So the people from all over the world put information on the World Wide Web with different Children Birthday Games and your Mum is finding them with one "Klick".

Now you have to imaging that computers are not thinking the same way as we do. Computers are not smart the same way as we are. A computer needs an instruction for every step. When he doesn't get any instructions he doesn't know that he has to do. For getting as much information together as possible (that your "Mum" can organize the best Birthday Party for you) the information about "Children Birthay Games" have to be linked together. Linked means connected together. Linked Data is a method to improve the infromation finding on the World Wide Web. The best informations about "Children Birthday Games" are linked together and for your "Mum" it's going to be easy, organizing your Birthday Party. Because the different infromation are linked together, they have a relationship togehter.

#### Reference List
- https://www.youtube.com/watch?v=4x_xzT5eF5Q (22.04.2015)
- http://www.w3.org/standards/semanticweb/data (22.04.2015) 


