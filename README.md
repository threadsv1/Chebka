# Content Aggregator for devs
5/20/2022
4 pages


## Chebka

### Team:
#### Team members:
Saif Gaida
Majd Mednini
Cohort #16
#### Roles:
##### Back-end:
 Saif is responsible for Integration of user-facing elements developed by front-end developer with server side logic, and trying to introduce security methods
 
##### Front-end:
 Majd is responsible for developing new user-facing features, determining the structure and design of web pages, building reusable codes, optimizing page loading times, and using a variety of markup languages to create the web pages.

#### Roles Overview:
The roles have been chosen as such as Majd has more experience in front-end development and he feels more comfortable with tools used in the front-end, while Saif is generally more interested in backend side development  and with the problem at hand specifically because everyone wants the algorithm to “bless” them. 
Both developers will be writing unit tests, debugging,  integrating libraries as needed and overseeing deployment if the development  reaches that stage

#### Technologies:

Libraries: Django~=3.2.7  - requests~=2.26.0 - bs4~=0.0.1 -Scrapy~=2.6.2 - requests-html~=0.10.0
Languages: Python - HTML - CSS - JavaScript
Platform: AWS
Frameworks: Django
Hardware: AWS EC2 / AWS S3 
Resources: Geeksforgeeks - w3schools - djangoproject - developer mozilla - realpython - cpske github
IDE: Visual Studio Code
Alternatives: Django can be substituted with flask and scrapy already replaced beautiful soup  being the most popular popular web scraping library, also great for scraping RSS feeds  also sql might be replaced with mongo 

#### Challenge:
“Chebka” will try to bring the most relevant, hottest content  in a single web page, easy to navigate, energy and attention saving, because there is just “Too Much choice” ; however due to overwhelming  amounts of content we have to acknowledge that without a machine learning model imbricated within the django framework  Personalization levels will be a little off-putting, so Chebka will not tackle the personalization  the targeted users are primarily software developers who want to be served the latest news and tutorials pertaining to their stacks
For now the only impediment for chebka is the language boundary  

#### Risks:
An apparent technical risk is traffic congestion, so a strict bandwidth limit is to be set, and the algorithm can only handle so many  resources, so a rotation has to be made primarily
A non technical risk is a a somewhat of a moral hazard towards publishers where they might not grant us rights to publish their content for profit in a later stage
Spreading poor content is another problem but measures can be taken to prevent that

#### Infrastructure:
Branching strategy: since we are an army of two and Chebka doesn’t have many features in this early stage, we think that we would not even reside to branching so Trunk based committing is the name of the game
Deployment: Blue-Green Deployment
Testing: factory_boy (factory_boy provides custom Factory subclasses for various ORMs, adding dedicated features.)
Data population: faker
Deployment:  nginx and Gunicorn
- the Django project is ought to be developed first with the core features such as web scraping and views and models, then the front end and linking it to the main django application

#### Existing Solutions:
Similar solutions:
Flipboard : gathers news from known and trusted sites and has broad categories of content we intend to include a broad range of topics for every user also and with a better graphic interface
alltop:  ui design is uninspiring and off putting so we try  to keep away from that
news google: great overall on web and especially mobile