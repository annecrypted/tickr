# tickr - tracked, visualized, done.

> *plan with your friends, celebrate the wins, roast the tough ones, and share your favourite films, books and music.*

tickr a **all-in-one second brain**, aka an app blends minimalistism and neobrutalism to act a powerful task manager, education organizer (with class timeblocking/scheduling), and application tracker for organizing your life, studies, college/job apps, and even the various types of media you're consuming, without requiring any heavy-lifting for setting everything up and get your dashboard running. 

it's a **productivity tool with the cutest user interface** (endless customization options) with every single feature one could possibly need in their early-career journey (no matter what maor / program / region) that's built specifically keeping students, early-career professionals, overcommitted multitaskers and side-quest warriors trying to do it all (without losing their minds) in mind, accompanied with a fun social twist.  
<img width="495" alt="image" src="https://github.com/user-attachments/assets/fd9500f7-39cf-45a8-882b-0c3bcca159e4" style="text-align: center" />


## <ins>brief overview of features</ins>

### ˚🛠 task dashboard  

- create tasks with:
  - custom tags for easy navigation
    - connect your subjects/organizations/projects and visualize your work efficiently
    - use categories like `#design`, `#econ101`, `#personal` 
  - urgency levels (low / medium / high)
  - due dates & deadlines
  - nested subtasks
- when you complete a task, your followers can *'like'* or *'dislike'* it
  
ps. i'm a big fan of social accountability but not a fan of pointless shaming. that’s why the like/dislike feature in taskr only applies to completed tasks. every reaction is a form of applause:
- a like means “this task was genuinely cool/impressive”
- a dislike means “that looked painful, but you got through it !! respect

![image](https://github.com/user-attachments/assets/f7b82ad1-7684-4c27-96b8-d3c573c78e25)


### 🛠 academic planner  
structure your entire academic journey whether you’re in school, attending a bootcamp, taking classes part-time at a community college/online or self-teaching (or a combination of those all).

- **institution-based planning**:
  - add schools, colleges, or bootcamps
  - define years, semesters, and classes
  - get a visual layout of your degree or learning path

- **subject tracker**:
  - log academic or self-taught topics
  - organize into nested tags (for example, we could have something like `math > algebra > linear equations`)
  - great for MOOCs, youtube rabbit holes, and structured study
 
  ![image](https://github.com/user-attachments/assets/0f35cec2-de4a-4ccc-bdcc-997126c95c89)


### 🛠 calendar
a montly timeblocking calendar for planning your days without skipping out on any important tasks without burnout.

- assign tasks to specific dates
- block out time for meetings, study, breaks, or deep work
- clean daily + weekly views
- (coming soon) auto-import school class schedules


### 🛠 application tracker  
no more forgotten emails or ghosted internships.

- log applications for:
  - jobs (full-time / part-time)
  - internships (paid / unpaid)
  - college admissions
  - research roles
  - volunteer work
  - bootcamps & leadership programs

- track:
  - status (applied, interview, offer, rejected, etc.)
  - deadlines & follow-up reminders
  - notes, links, and documents
 
![image](https://github.com/user-attachments/assets/01e5811c-3342-4120-a65b-b6622fdaf6f3)


### 🛠 media log  
a cross-platform media tracking app, meet letterboxd and last.fm's lovechild !! track what you’re watching, listening to, reading, playing or bingeing.

- log:
  - tv shows
  - movies
  - podcasts
  - youtube channels / series
  - books
  - documentaries

- track metadata:
  - status (watching, completed, want to watch, paused, dropped)
  - notes, ratings, genre tags
- see your full media history

![image](https://github.com/user-attachments/assets/5a07e9f9-9b36-4bc6-b96b-f16c5c24575a)
![image](https://github.com/user-attachments/assets/65833ec2-daea-4c21-82e9-07bef1ea1285)

### 🛠 user profiles
the app isn’t just about staying organized, it’s about staying connected. productivity gets easier (and more fun) when you’re doing it alongside friends. here’s how tickr makes planning a little more social with its social features:
- user authentication
- Following/followers system
- task likes/dislikes + comments
- public/private content
- activity timeline
- user discovery

![image](https://github.com/user-attachments/assets/7b8001df-dc0e-42ba-8fc9-0ab96dffdaf0)


### 🛠 responsive design (mobile-first)
tickr is built with a bold neobrutalist aesthetic that's functional, geometric, and unapologetically structured. the ui features thick borders, high contrast layouts, and vibrant category colors that are both practical and expressive. paired with a modern font stack (montserrat + poppins), the design feels organized, confident, and refreshingly different.

- light/dark mode support
- combination of pastel colors & white space
- visually appealing, bold (but not too overwhelming) yet minimal
- text and design elements work perfectly on screens of all sizes

<img width="400" alt="image" src="https://github.com/user-attachments/assets/1ecc326a-6670-497c-bf80-c8e4dd4c5670" style="text-align: center" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/89d4d4a7-c0a0-4a70-9ac9-a3857400267e" style="text-align: left" />


## <ins>tech stack</ins>

this proect started out as something i built out of frustration, mostly because i couldn’t find a single app that did *everything* i needed (or wasn’t locked behind a paywall). over time, it became more intentional. before writing any code, i sketched out how it should feel and function, starting with paper and pencil sketches, then dumping everything on the last page of my school notebooks during the time between the classes and then compiling them into a rough neverending list in my journal.

a while back, i was *absolutely swamped* with schoolwork and wanted to relax, so naturally i started browsing through my personal notion table with project ideas and decided to say "f*ck it" and picked this one up, one of the most elaborate/ambitious, but i knew i had to push through that fear of failure and give it a fair shot, so, i then ended up moving to <ins>figma</ins> for wireframes and neobrutalist mockups i kept seeing on pinterest. <ins>ibispaint</ins> and <ins>procreate</ins> were my chaotic canvas for layout doodles, while canva helped with inspo dumps and pitch slides. 

<ins>obsidian</ins> & <ins>notion</ins> became my second brain for feature notes, db schemas, and “what if…” ideas. and claude helped me debug and badge-hunt when i needed a break from yelling at vite. i made the logo in figma once and after having already grouped all my layers, realized i spelled the name of the app wrong (ok it was 3am) and had to scrap the [logo's first version](https://github.com/user-attachments/assets/9bd63b1a-fc8d-4fa6-90f5-48597df22da2) redo it entirely to the current one (send help).

anyway, here’s a look at everything i actually used to build this full-stack app. it’s still in progress, but it’s the first project i’ve taken this far (without randomly abandoning), and i’m honestly really excited about it.

- **frontend**: react + tailwind css + vite
  
  ![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61dafb)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646cff?style=for-the-badge&logo=vite&logoColor=white)
![JSX](https://img.shields.io/badge/JSX-61DAFB?style=for-the-badge&logo=react&logoColor=black)

- **styling and ui**: used tailwind, which i now treat like a design language. added custom css variables for dark mode and theming. the whole ui for this responsive (mobile-first) app follows a simple, minimalist and neobrutalist style and is blocky, and weirdly clean.
  
  ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-0ea5e9?style=for-the-badge&logo=tailwindcss&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS-264de4?style=for-the-badge&logo=css3&logoColor=white)
![Lucide React](https://img.shields.io/badge/Lucide-000000?style=for-the-badge&logo=lucide&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285f4?style=for-the-badge&logo=google&logoColor=white)

- **backend & database**: considering this is the part that always breaks before demo-ing, it's all powered by supabase, which basically handles everything from the database to auth.
data’s stored in postgres, with rls keeping user stuff private. 

  ![Supabase](https://img.shields.io/badge/Supabase-3ecf8e?style=for-the-badge&logo=supabase&logoColor=000000)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![RLS](https://img.shields.io/badge/Row%20Level%20Security-ffbf00?style=for-the-badge&logo=postgresql&logoColor=black)
![Supabase Auth](https://img.shields.io/badge/Auth-Supabase-3ecf8e?style=for-the-badge&logo=supabase&logoColor=000000)
![Edge Functions](https://img.shields.io/badge/Supabase%20Edge%20Functions-2e2e2e?style=for-the-badge&logo=supabase&logoColor=3ecf8e)

- **state and data handling**: used react hooks for state and effects (no redux, no zustand, no regrets). ts interfaces keep things in check so i don’t cry when renaming props. using mock data for testing bcs no actual users wanted to help with testing.

  ![React Hooks](https://img.shields.io/badge/React%20Hooks-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript Interfaces](https://img.shields.io/badge/Type%20Safe-3178c6?style=for-the-badge&logo=typescript&logoColor=white)
![Mock Data](https://img.shields.io/badge/Mock%20Data-F5DEB3?style=for-the-badge)

- **developer tools**: tools that are basically my siblings, those who constantly yell at me but for my (project's) future benefit. using postcss + autoprefixer made sure things don’t break in weird browsers.
  
  ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![PostCSS](https://img.shields.io/badge/PostCSS-DD3A0A?style=for-the-badge&logo=postcss&logoColor=white)
![Autoprefixer](https://img.shields.io/badge/Autoprefixer-ff6a00?style=for-the-badge)
![Date-fns](https://img.shields.io/badge/date--fns-007ACC?style=for-the-badge)




## <ins>intended audience</ins>

- students managing classes, projects, and job hunts  
- creators and learners tracking what they’re building or watching  
- neurodivergent thinkers who need structure but hate pressure  
- people who want to build good habits *with* their friends  
- anyone trying to stop forgetting things every 5 minutes


## <ins>potential future iterations</ins>

- pomodoro timers 
- public-facing dashboards & media feeds  
- google calendar & ical sync  
- widgets: stats, affirmations

## <ins>contributions</ins> (work in progress)
this project is still actively in development. things are changing fast, features are being tested, and parts of the app are constantly being improved. if you run into a bug, glitch, or something that feels off, feel free to open an issue or [let me know directly](https://anoushka.dev/contact).

feel free to fork and add anything you deem appropriate. if you have a feature idea, suggestion, a use case you think tickr should support, or something you wish the app could do, hmu! i’m open to suggestions that align with the core vision. and if you’re a designer, developer, or just someone interested in building fun tools for creative people, dm me bcs i’d love to talk.

> *ps.* *it’s frustrating that this even needs to be said, but just to be upfront: please don’t request features for tracking explicit nsfw content or ask for adult site titles to be included in the media log. tickr is meant to be a productive, safe, and inclusive space, especially for students, younger users, and people using it in academic or shared environments. adding support for explicit content would compromise that focus, introduce moderation concerns, and shift the app away from what it’s meant to be. 
it’s just **not a direction i’m interested in building toward**, and i’d appreciate not being asked again about it. thanks for understanding.*


<!-- ![image](https://github.com/user-attachments/assets/6832b741-8096-4f08-acab-5957723cd7fd)-
![image](https://github.com/user-attachments/assets/5a07e9f9-9b36-4bc6-b96b-f16c5c24575a)
![image](https://github.com/user-attachments/assets/2e47bf81-3179-41f2-b854-0115a278b0f2) -->



**credit where credit's due:**
i listened to a lot of taylor swift, sabrina carpenter, tate mcrae, olivia rodrigo, charli xcx, reneé rapp, and sophie rose while building this project. the playlist definitely kept me going. also, shoutout to cheese crackers, mini snickers bars, and carrots with peanut butter for getting me through way too many midnight coding sessions.

![Github-sponsors](https://img.shields.io/badge/sponsor-30363D?logo=GitHub-Sponsors&logoColor=#EA4AAA) ![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?logo=ko-fi&logoColor=white) 



