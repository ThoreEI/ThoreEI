# 💫 About Me:
```Java
public class Profile {
    private static final String NAME = "Thore";
    private static final LocalDate BIRTH_DATE = LocalDate.of(1998,12, 5);
    private int age;

    public Profile() {
        this.age = Period.between(BIRTH_DATE, LocalDate.now()).getYears();
        whoAmI();
    }

    private void whoAmI() {
        System.out.printf("""
                        Hey! My name is %s, I'm %d years old and crazy about technology.
                        The diversity of computer science drives me to keep going.
                        'If there is only one solution, get a second opinion' - Timothy High
                        In addition to wise sentences, I love dull humor.
                        'What is the biggest lie in the entire universe?'
                        'I have read and agree to the Terms & Conditions.'
                        \s""",
                Profile.NAME, this.age);
    }

    public void age() {
        this.age += 1; // A computer freak doesn't age, he levels up
    }
```

# 💻 Tech Stack
![LINUX](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)


<!-- ## 🌐 Socials
-->
<!-- ### ✍️ Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=vetical&theme=radical) -->



