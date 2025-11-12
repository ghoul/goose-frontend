# Homework system frontend

For my Bachelor Degree project, I developed a **website** and **3D game** to make **homework more engaging** for students. Teachers could assign tests via the website, which students would complete through the 3D game interface.

**Here you can find a website part.**

## Admin use:

- Login
- Create or update school info

## Teachers use:

- Login
- Create test with questions and answers
- Assign test to class
- Analyse results
- Export grades to a separate file

## Students use:

- Login
- Look for homework
- Choose to either play a **game** or do a **test**
- If chooses to **play** - redirects to game window
- If chooses to do a **test** - redirects to test page
- Questions appear as **cubes** in this 3D game world
- After completing homework, grade and answers could be found back in the website
- **Leaderboard** based on points and time (for separate homework and for all homeworks)

**Gamifying homework** can significantly improve students’ motivation and focus. The "Goose" platform was designed to **boost engagement** by introducing a bit of competition and interactive gameplay.

- **Backend repository** can be found here: https://github.com/agnerau/goose-backend
- **WebGL build** for the game can be found here: https://github.com/agnerau/goose-game

## Technologies Used

- **Framework:** React.js
- **Website design:** Adobe Illustrator
- **Styling:** CSS
- **Testing:** Jest

## Usage

To run the development server locally:

```bash
npm install
npm start
```

## Visuals

### Login page

![login](./visuals/login.png)

### Admin page (schools managing)

![admin](./visuals/admin.jpg)

### Teacher main page

![teacher_panel](./visuals/teacher1.jpg)

### Homework creation page

![homework_create](./visuals/teacher2.jpg)

### Class test summary

![class_summary](./visuals/teacher3.png)

### Test review

![test_review](./visuals/teacher4.jpg)

### Test page (student)

![test_view](./visuals/student1.jpg)

### Leaderboard

![leaderbord](./visuals/student2.jpg)
