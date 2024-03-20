# IDS721 Individual Project 01 - Static Website using Zola hosted on Vercel, Netlify, AWS Amplify, AWS S3, or others.

![Job Status](https://gitlab.com/divyasharma0795/ds655_ids721_miniproject01/badges/main/pipeline.svg)

Vercel Website Link: [https://divyasharma.vercel.app/](https://divyasharma.vercel.app/)

The static Zola website can be found at the [Project Website](https://ids721-miniproject01-divyasharma0795-a094ba4b748189a3597541e8c4.gitlab.io/)

Video Dem0: [Link]()

## Description
Creating a static website using [Zola](https://www.getzola.org/) - the theme used for this project is [hephaestus](https://www.getzola.org/themes/hephaestus/). The website serves as my personal profile, showcasing basic information, education, work experience, skills, and projects.

The website is hosted on [Vercel](https://vercel.com), a cloud platform for static sites and Serverless Functions. Vercel provides continuous deployment (CD), where every push to the main branch triggers a new deployment of the site. The build command `zola build` is used to build the site, and the output directory is set to `public`, where Zola generates the site files.

Vercel is integrated with GitLab, and the site is automatically built and deployed whenever changes are pushed to the GitLab repository. This integration provides a seamless workflow for continuous integration (CI) and continuous deployment (CD).




## Visuals

-   Starting Page

![1](<Images/Screenshot%202024-01-31%20at%2002-15-14%20Divya%20Sharma%20Profile.png>)

-   About me

![2](<Images/Screenshot%202024-01-31%20at%2002-15-41%20Divya%20Sharma%20Profile.png>)

-   Education

![3](<Images/Screenshot%202024-01-31%20at%2002-17-13%20Divya%20Sharma%20Profile.png>)

-   Skills

![4](<Images/Screenshot%202024-01-31%20at%2002-18-08%20Divya%20Sharma%20Profile.png>)

-   Projects

![5](<Images/Screenshot%202024-01-31%20at%2002-18-28%20Divya%20Sharma%20Profile.png>)

-   Work Experience

![6](<Images/Screenshot%202024-01-31%20at%2002-18-57%20Divya%20Sharma%20Profile.png>)


## Installation

1. Clone the repository

```
git clone https://gitlab.com/DivyaSharma0795/ds655_ids721_miniproject01.git
cd ds655_ids721_miniproject01
```

2. Install Zola
Follow the [official Zola installation guide](https://www.getzola.org/documentation/getting-started/installation/).

3. Run the development server:
```
zola serve
```

4. Visit http://127.0.0.1:1111/ in your web browser to preview and edit the site locally.

5. Update the `config.toml` file with your personal information

6. Add or modify content in the `content` directory to reflect your profile details

7. Customize the theme and styles as needed. Explore the [Hephaestus theme documentation](https://www.getzola.org/themes/hephaestus/) for customization options and theme-specific features.

8. Connecting to Vercel
   - Create an account on [Vercel](https://vercel.com)
   - Install the Vercel CLI by running `npm install -g vercel`
   - Run `vercel login` to log in to your Vercel account
   - Run `vercel` to deploy the site to Vercel
 


## Authors and acknowledgment
Thanks to [Bryant Conquest](https://bryantconquest.com/) for the useful template


## License
The website content is licenced by [ CC BY-NC-SA 4.0 Deed](https://creativecommons.org/licenses/by-nc-sa/4.0/)
