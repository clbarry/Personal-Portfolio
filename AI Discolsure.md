**AI Use Disclosure** 

AI Used: Claude Sonnet 4.6


- I used Claude to detrmine what to add to the .gitignore file
    Prompt used: I am starting a project using HTML, CSS, and JS what do I add to a gitignore

- Claude used for color pallate planning 
    Prompts used: 
        - what is this color #162b35
        - using this as the font what is a good background color
        - I like the seafoam, is there a lighter color than seafoam
        - what about this for a background #f6f5f5
        - does the wisper teal or the almost white warm gray work better
        - what is a complimentary text color for quotes with primary text color as 162b35
        - is the contrast enough for muted teal
        - is #3d6b7a different enough from #162b35 to be noticeable
        - what color is this #3d6b7a
        - what are good colors to use for hover, visited, a link, and active possibly background
        - What is a good complemenatary contrasting color in the purple family
        - Compare these next to the default overall text 
        - these are what I have selected, I need a good contrast for the active nav 

            /* #162b35   Dark Slate Blue/Deep Teal - font color*/  
            /* #3d6b7a   Muted Teal - quote font color*/
            /* #f1faf7   Wisper Teal - Background color */
            /* #6b4f7a   Dusty Plum - link color */
            /* #7c3f7a   Deep Magenta Purple - link already visited*/
            /* #c2dfe8   Teal Wash - background color for hover*/

- I had an issue with video rendering. I used Claude as follows. 
    Prompt used: What are common reasons that a video may not display, they are hosted on youtube.



***************************************************
AI Used for Publications Page Using the Following Prompts

Prompts Used 

PROMPT #1:
For my class assignment in web development, I am creating a personal page using the following: html5, css, bootstrap, and a minimal JavaScript. The site contains three pages in different .html files, index.html, publications.html, and teaching.html. The assignment is to build one of the pages using generative AI, I have created the index.html and teaching.html files. Create the html file for the Create the publications page. I started the farmwork here. 
(publications_archive.html added here)
I want the nav bar to have buttons across the page horizontally.

List each publication in a card in IEEE format, use google scholar to gather my publications. 


PROMPT #2: 
Those are not my publications, this is my google scholar profile include each and add an image from the paper and link for each publication https://scholar.google.com/citations?user=KxZUdqwAAAAJ&hl=en

PROMPT #3: 
This paper is missing. Mahsan Nourani, Lien Nguyen, Carey Barry, Qingchu Jin, and Melanie Tory. 2026. The HEART Interface: Visualizing Risk Score Uncertainty in the Cardiothoracic ICU. In Proceedings of the 31st International Conference on Intelligent User Interfaces (IUI '26). Association for Computing Machinery, New York, NY, USA, 1019–1036. https://doi.org/10.1145/3742413.3789109

PROMPT #4: 
add a small logo for each of the links at the top: linkedIn, Google Scholar, ORCID, Instagram, and GitHub

PROMPT #5: 
Keep them with the color theme

PROMPT #6:
Create a section at the top for a featured works and add the HEART paper there

PROMPT #7: 
Here are the publications with all the authors 	Nourani M, Nguyen L, Barry C, Jin Q, Tory M. The HEART Interface: Visualizing Risk Score Uncertainty in the Cardiothoracic ICU. In: Proceedings of the 31st International Conference on Intelligent User Interfaces. IUI ’26. Association for Computing Machinery; 2026:1019-1036. doi:10.1145/3742413.3789109
	Rolls, Joanne MEHP, MPAS, PA-C; Showstark, Mary MPAS, PA-C, FAWM; Najmabadi, Shahpar PhD, MPH; Loder, Rayne MHS, PA-C; Barry, Carey MHS, PA-C; Honda, Trenton PhD. Gender Minority Physician Assistant/Associate Applicants and Likelihood of Matriculation: A Retrospective Analysis. The Journal of Physician Assistant Education 36(2):p 113-119, June 2025. | DOI: 10.1097/JPA.0000000000000647
	Broughton A, Landry A, Showstark M, Barry CL, Najmabadi S, Rolls J, Honda T. Military Veteran Matriculation in US Physician Associate/Assistant Programs. The Journal of Physician Assistant Education. 2024;35(2):156. doi:10.1097/JPA.0000000000000568
	Najmabadi S, Valentin V, Rolls J, Showstark M, Elrod L, Barry C, Broughton A, Bessette M, Honda T. Non-native English-speaking applicants and the likelihood of physician assistant program matriculation. Medical Education Online. 2024;29(1):2312713. doi:10.1080/10872981.2024.2312713
	Barry CL, Coombs J, Buchs S, Kim S, Grant T, Henry T, Parente J, Spackman J. Professionalism in Physician Assistant Education as a Predictor of Future Licensing Board Disciplinary Actions. The Journal of Physician Assistant Education. 2023;34(4):278. doi:10.1097/JPA.0000000000000515
	Ryujin D, Dalton D, Yole-Lobe M, DiBiase M, Phelps P, Madden A, Clark J, Barry CL, Rodriguez JE, Honda T. Implicit Association Test Alone Is Not Sufficient to Increase Underrepresented Minority Representation in Physician Assistant Programs. The Journal of Physician Assistant Education. 2023;34(4):295. doi:10.1097/JPA.0000000000000523
	Showstark M, Bessette M, Barry CL, Najmabadi S, Rolls J, Hamilton C, Valentin VL, Quella A, Honda T. PA applicant U.S. citizenship status and likelihood of program matriculation. BMC Med Educ. 2022;22(1):887. doi:10.1186/s12909-022-03947-x
	Min EA, Lie D, Barry C, Moloney-Johns A, Hibbard ST, Ritsema TS, D’Aquila M, Honda T. Validation of a Novel Statistical Method to Identify Aberrant Patient Logging: A Multi-Institutional Study. The Journal of Physician Assistant Education. 2022;33(3):192. doi:10.1097/JPA.0000000000000437
	Barry CL. Surgical Wound Infections. PA Clinics. 2021;6(2):295-307. doi:10.1016/j.cpha.2020.11.003
	Barry CL. Immunohematology and Transfusion Medicine. Physician Assistant Clinics. 2019;4(3):591-607. doi:10.1016/j.cpha.2019.02.009
	Honda T, Barry C, Buchs SR, Garbas BL, Hibbard ST, McLellan A, Riethle T, Swanchak LE. Considerations Around Predicting Physician Assistant National Certifying Exam Scores From PACKRAT®: A Multiprogram Study. The Journal of Physician Assistant Education. 2019;30(2):86-92. doi:10.1097/JPA.0000000000000256

PROMPT #8:
The styling needs to be mostly in the CSS file, create a separate css code for this page. Here is some key information that I used to style the other pages in addition to boot strap. Keep the styling you created but update the color pallate  

```css
:root {
    /*--colors--*/
    --primary-font-color: #1b323d;    /* dfines primary font color*/
    --quote-font-color: #3d6b7a;      /* dfines quote font color*/
    --link-color: #2e7d9a;            /* dfines link font color*/
    --link-visited: #7c3f7a;          /* dfines link font color for a link already visited*/
    --hover-backgrnd: #c2dfe8;        /* dfines background color for hover*/
    --active-backgrnd: #1a5c73;       /* dfines background color for active nav*/
    --active-font-color: #f1faf7;     /* dfines text color for active nav*/
    --site-background-color: #f1faf7; /* dfines site backbroud color*/      

    /*--fonts--*/
    --heading-font: Georgia;        /* defines heading font family*/
    --text-font: Lucida, serif;    /* defines text font family*/       
}

body {
    background-color: var(--site-background-color);
}

/************ Style Based on state *************/
a:link {color: var(--link-color);}
a:visited {color: var(--link-visited)}
a:hover {background: var(--hover-backgrnd);}
a:active {
    background-color: var(--active-backgrnd);
    color: var(--active-font-color); 
}

/****************** FONTS *********************/
h1 {
    font-family: var(--heading-font);
    color: var(--primary-font-color);
    font-weight: bold;
}

h2, h3, h4, h5, h6, p, li {
    font-family: var(--text-font);
    color: var(--primary-font-color);
}

.quotes {
    font-style: italic;
    color: var(--quote-font-color);
}

```
*************** DONE GEN AI Portion **************************

