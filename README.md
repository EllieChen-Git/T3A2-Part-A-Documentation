# MERN Project - Robbie, Nina & Ellie

---

#### Important Links

- **Trello Board for Project Management**: https://trello.com/b/0v9PguSo/mern-project-russian-revolution

- **Google Docs with client**: https://docs.google.com/document/d/1LWC1A3N7JIlHHCPTpEeogDa_6byR3AqY/edit

- **Google Docs - Russian Revolution team**: https://docs.google.com/document/d/19f4QnUG-G3cZPQmdLW-udaeRMoFxDCpGZkuhnMKHdYY/edit#heading=h.utms68xn1b3s

---

## R1 Website Description

#### Purpose

The purpose of our software is to allow for the accurate manual image annotation of property features within apartment floor plans. This will allow for the future use for our client to develop the project to incorporate computer vision and to more effectively evaluate apartment pricing.

---

#### Functionality/Features

**1. Image Annotation** - Users will be able to tag certain features of an image using one or more tags. The data will automatically be saved to the database every time a user modifies a tag. The user will be able to indicate when the annotation of an image is finished through saving the amended image(all the tags are placed). After this, the user will be unable to modify their tags.

**2. Tag Management and Search** - Users will be able to search from existing tags, create new tags and modify tags through the use of image annotation. Tags are globally accessible to users across the system.

**3. Annotation Review** - Users will be able to review annotation results and mark annotations as incorrect, requesting re-annotation.

**4. Role-based authentication** - Users have access to different elements of the application based on their roles (admin or regular users) and basic Access Control Lists (ACLs).

**5. Image Flow Management** - Users will be able to organise images hierarchically through the system (e.g. Project->Building->Floor).

**6. Image Metadata Management** - Users will upload a CVS document, which contains metadata of an image (including image URLs). They will also be able to add additional metadata to this document through adding key and value pairs to the database.

---

#### [Draft] Potential Future Features for Application

```
1. Building has a drop-down list of levels attached to the side.
2. Have different sizes images based on new, work in program or complete status.
3. For tags, differentiate features based on if they positively or negatively affect the price.
4. Users should be able to edit their own profiles (first name, last name and so on).
5. Image Navigation  - Users will be able to zoom in and out the image and to drag it.
```

---

#### Target Audience

The target audience for our application is our client Skychute and professionals within the real estate industry. Another group of our target audience is other developers who are interested in image annotation techniques.

---

#### Tech Stack

**APPLICATION AND DATA**

- **JavaScript**: A high-level, just-in-time compiled, multi-paradigm programming language that conforms to the ECMAScript specification.
- **React**: A JavaScript library for building user interfaces.
- **MongoDB**: A cross-platform document-oriented (non-relational) database program.
- **Express**: A web application framework for Node.js
- **Node**: An open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside of a browse
- **Amazon S3**: A service offered by Amazon Web Services that provides object storage through a web service interface.
- **Amazon IAM**: A service provided by Amazon to manage access to AWS services and resources securely.
- **SASS**: A style sheet language.
- **HTML5**: A software solution stack that defines the properties and behaviours of web page content by implementing a markup-based pattern to it.
- **CSS3**: A style sheet language used for describing the presentation of a document written in a markup language like HTML

**UTILITIES**

- **BALSAMIQ**: A mockup tool for wireframing.

- **Trello**: A web-based Kanban-style list-making application
- **Pinterest**: A tool to store images for ideas of mood board.

**DEVELOPER OPERATIONS**

- **GITHUB**: A platform for source control.
- **GIT**: a free and open version control system
- **Heroku**: a platform for deploying our application
- **JEST**: a testing framework

**BUSINESS TOOLS**

- **Slack**: A cloud-based proprietary instant messaging platform for communication within team and with client.
- **Google Docs**: A tool for documentation collaboration.

---

## R2 Dataflow Diagram

---

## R3 Application Architecture Diagram

---

## R4 User Stories

**ALL USERS**

- **Angel**: As a user, I would like to sign-up for an account, so I can log into my account on the website later.
- **Jurra**: As a user, I would like to log into my existing account, so I can use the functionalities provided by the website.
- **Tom**: As a user, I would like to browse the website on my mobile, computer and my tablet, so I can use this application on different devices.
- **Ellie**: As a user, I would like to sign-out from the website, so my account is more secure.

**ADMINS**

- **Nina**: As the CEO of Skychute, I would like to organise images in a certain way, so it is easier for our company to maintain the data.
- **Mark**: As a developer at Skychute, I would like to grant some users admin access, so we can have more admin users to manage our projects.
- **Robbie**: As a Project Manager at Skychute, I would like to assign projects and buildings to regular users, so users can tag the features on the floor plan images.
- **Elliot**: As a Project Manager at a construction company, I would like to add, view, update and delete projects.
- **Wayne**: As a Project Manager at Skychute, I would like to add, view, update and delete buildings.
- **Alex**: As a Project Manager at a construction company, I would like to add, view, update and delete apartments.
- **Prad**: As a Project Manager at Skychute, I would like to upload floor plan images and apartment information (csv files) to apartments.
- **Ragan**: As a Project Manager at Skychute, I would like to review tagged floor plans submitted by regular users, so I can manage the project progress.
- **Dale**: As a Project Manager at Skychute, I would like to have the ability to reverse the status tagged floor plans (from ‘completed’ back to ‘editable’), so users can edit it again.

**Regular Users**

- **Luke**: As a Property Valuer, I would like to tag the property features on the floor plans, so I can better evaluate the property price.
- **Chelsea**: As a Real Estate Agent, I would like to create, read, remove and delete tags, so I can manage the tags as I wish.
- **Max**: As a Real Estate Agent, I would like to save the tagged plans multiple times before submission, so I can go on a coffee break and come back to the image I am working on.

## R5 Wireframes

- Refer to **WireframesThursday.bmpr**: We only finished the 'admin' part at the moment. Will continue with 'regular users' tomorrow.

## R6 Screenshots of Trello board

---

<!-- ### Other Groups Repo

E-Learning (Mark & Jurra): https://github.com/Mark-Ball/T3A2_PartA

Olive Farm (Tom, Elliot & Prad): https://github.com/thomasalfonso/T3A2PA -->
