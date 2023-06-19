# CYBORGISATION

Author: Sumeet Singh

Project: CyborgMe, CyberTheseus

Created: 6th April 2023

Author contact: kurta.kursi@gmail.com

Author website: www.sumeet-singh.com

License: GNU General Public License v3 (GPL-3)

Availability
* Website: 
* iOS Store:  
* Google Play Store:  


# What is Cyborgization?

According to references collaborated in "The Oxford Dictionary of Science Fiction" ISBN: 9780195305678

cyborgisation  (spelt cyborgization in American English) is a noun, that's linked to the word "cyborging: the process or act of making someone into a cyborg.".

* 1994 B. Stableford Les Fleurs du Mal Asimov's SF (Oct.) 125 He was playing about with brainfeed equipment […]. Not just memory boxes or neural stimulators, but mental cyborgization.
* 1996 D. Pringle, et al. Ultimate Ency. of SF 41/2 Stories dealing with the cyborgization of humans for the purpose of exploring other worlds include Arthur C. Clarke's “A Meeting With Medusa.”
* 2001 A. Reynolds Chasm City 48 The Chimerics in general had taken cyborgisation to new extremes, blending themselves and their animals with machines.


# Background

This is an Biomedical Engineering open source project. This software allows you to create a 3D humanoid/animal model and select different parts of the body to show available biomedical engineered technologies (products and research) for that location.

Cyberware is technology that attempts to create a working interface between machines/computers and the human nervous system, including the brain. Examples include Prosthetics e.g. prosthetic arms, brain-computer interfaces e.g. EEG headsets, medical instruments such as ECG heart rate readers etc., Cyberware is a term used in science fiction, however the more commonly accepted scientific term is "biomedical engineered technologies". Biomedical Engineers work alongside medical
practitioners to augment humans by adding, removing or modifying parts of the human body to create hybrid part human part tool organisms known as cyborgs.

The idea is for the safety and benefit of the entire human race to collaborate knowledge related to cyberware, that hasn't been consolidated in an unbiassed, open source, safe manner before, that often is performed in isolated research whether through educational institutes such as univeristies, biomedical firms, international institutes in foreign untranslated languages, hobby biohackers or even business not in the habbit of collaborating research.

By putting all this research together it creates a single source of truth hosted by Sabrenetics that can be easily regulated by medical boards so that knowledge presented is safe, regulated, and the users or consumers are informed of what they are viewing.

We want this to be a database that the public can find out the research that is being done on cyberware so that they may collaborate, and document safely together.  We invite the public and commerical organisations both to contribute and use for their own personal research, projects and even commerical ventures to advertise and advocate safe cyberware. The author doesn’t encourage any unsafe, unregulated, unqualified research projects. Always refer to your local governments laws on each research project.

You are able to choose different parts of the bodies such as limbs by clicking on them and a list of safe curated non advertised devices are discussed, such
as by clicking on an hand shows options for microchips that could theoretically be implanted. Users can also contribute to the project and add journal articles to the cyberware part picker software to create new enteries for cyberware.

The greater picture would be for Sabrenetics to host all users different avatars (the physical character models of users) in Sabrenetics.com to be kept in a central location that can be stored, shared, modified anytime with Sabrenetics as a governing body providing technical programming support. This ensures your research projects, personal projects, commerical products are always available to you with free support.

Feel free to fork your own copy and modify it for yourself. This can be modified commerically for business to advertise their own legal safe regulated goods as an portfolio advertisment of goods. You can use this as a generic body modification software for other scenarios not related to biomedical engineered technologies such as for fashion (observing how clothing and accessories look on a human body), or observing tattoos/piercings, etc., Any suggesstions to add or remove products are user discretion provided they are of your own opinion and not related to the author.


# USE GUIDE

The requirements of the app are below. An web application either on python or js that can a user can pick or upload different glb 3d model files. From there they can choose to add textures. The main programs purpose is that users can select individual parts of the 3d human body model and then an popup will open showing the available clothing accessories that can be purchased for that body part. E.g. if the body part selected from the 3d female glb file is the hand, then different website popups for buying rings will appear.


1. Backend: Python
* Django: A lightweight web framework for Python that allows you to handle HTTP requests and build APIs.
* NumPy: A library for handling numerical operations, useful for geometric transformations.
* Three.js: A JavaScript library for rendering 3D graphics in the browser. You can use it to display and manipulate the 3D models.
* PyGLTF to handle GLB files and perform necessary operations like loading and manipulating the 3D models.

2. Frontend: JavaScript
* Three.js: As mentioned above, this library will handle the rendering and manipulation of 3D models in the browser.
* React.js: A popular JavaScript library for building user interfaces. You can use it to create dynamic and interactive components of your application.
* Redux: A state management library that can help you manage the state of your application, especially when dealing with multiple models on the field.
*   Implement functionality for users to pick or upload GLB files and display them in the browser.

3. Database: AWS S3 or AliBaba Cloud
* A Relational database that holds users saved data.
* Depending on safety, regulations and jurisdiction of customer data will use a mix of AWS S3 Buckets or AliBaba Cloud

4. Importing and grouping of meshes and textures:
* You can use server-side file handling in Python to manage the uploaded files and store them in specific folders.
* On the frontend, you can use JavaScript to load the meshes and textures and group them as needed using Three.js.
*   Add a file upload component in the frontend to allow users to upload GLB files.
*   Implement the necessary logic in the backend to handle the file upload, store the files in a specific folder, and return the file path or identifier to the frontend.
*   Implement a texture mapping feature using Three.js to allow users to add textures to the 3D models.
*   Create a UI element in the frontend where users can select textures and apply them to different parts of the model.
*   Implement the necessary logic in the backend to handle texture mapping operations and apply textures to the 3D models.

5. Export/Share options:
* You can provide export options using Three.js's built-in export functionalities to export the modified models in different formats such as GLB or OBJ.
* Sharing options can be implemented using standard web technologies like sharing links or generating unique URLs for each model.

6. Photo modeling:
* For converting a photo into a 3D model, you may need additional libraries or services specifically designed for this purpose. You can explore options like using machine learning models or utilizing photogrammetry techniques.

7. External APIs:
* For integrating with external websites, you can use standard web technologies like HTML and JavaScript to create clickable links that redirect users to the desired websites.
* Implement an API endpoint that accepts file uploads.
* Django can be used to create APIs to expose the functionality of your application as web services that can be integrated with third-party applications.


# DATA SAFETY

Consider this the Wikipedia of Cyberware knowledge where a organisation Sabrenetics manages the central knowledge store and acts as unbiassed as possible to ensure that every researcher and research is given equal opportunity through being educated on digital journalism, to contribute to, and that their works are protected unless directly challenged. This prevents a edit war scenario in which multiple entities modify documentation at will, without consulting others.

Terms and conditions come from the source location the main repository of CYBORGISATION will be held which is on Sabrenetics.com. 
Safeguards will be put in place by Sabrenetics such as;

Softlocks
* User account registration with verified email, regulated with anti bot protection systems e.g. capture
* digital journalism tutorial for newcomers
* max posts allowed per day timeouts
* fact checking journals before submission, 
* warnings with educational resources for discipline 
* etc., 

Hardlocks
* Banning users who break terms and conditions such as conducing illicit use of site
* etc.,



# ROADMAP

* Create/Save/Store Avatars - TBA
* Body dimension proportion manipulation - weight, height - TBA
* Transform the model with geometric options e.g. adding verticies, limbs etc., - TBA 
* Adding Meshs of non humanoids e.g. Pet's (dogs) - TBD
* Allow importing and grouping of meshs and textures from specific folders - TBA
* Allow linking of external websites to various parts of body - TBA
* Exporting 3D model to different formats - TBA
* Importing 3D model from different formats - TBA
* Photo modelling - Software accepts a photo of yourself, picture or model and converts into the software and converts to a model.
* Multiple models on field - Can add muliple models to field.
* API's - We aim to create API's to make the cyberware avatar avaialble for integrating with third party applications e.g. Social Media, Metaverse, Scientific, Gaming, etc.,
* CyberTheseus - The theoertical aspects of how much the cyberware augmented to model effects body function. This will scale in from human to transhuman. With color ranges showing research articles of various effects documented on the human body. The various effects of studied polymers, voltage, magnetism on the body. Electrogram simulations increase and decrease based on proportions of implants used. How much humanity departs with more implants. How close you are from Transhumanism.

  
  





