<div align="center">
    <!-- Animated Header -->
    <a href="https://github.com/HardcodeCoder">
        <img alt="Hey! I'm Ashuthosh" src="./header.svg" />
    </a>
    <br />
    <a href="https://github.com/DenverCoder1/readme-typing-svg">
        <img
            src="https://readme-typing-svg.demolab.com?width=600&height=60&font=Nunito+Sans&weight=600&size=22&pause=1000&color=92E4A6&center=true&lines=Loves+Kotlin%2C+Android+Nerd%2C+still+a+POJO;Committing+to+code+byte+by+byte;Writes+getter+%26+setter+for+%24%24;a.k.a+HardcodeCoder"
            alt="Loves Kotlin, Android Nerd, still a POJO; Committing to code byte by byte; Writes getter & setter for $$; a.k.a HardcodeCoder"
        />
    </a>
    <br />
    <!-- Social Links -->
    <a href="https://github.com/HardcodeCoder?tab=repositories&sort=stargazers">
        <img
            src="https://img.shields.io/github/stars/HardcodeCoder?style=for-the-badge&logo=apachespark&labelColor=35383E&logoColor=FFFFFF&color=AAFF89"
            alt="Github Stars"
        />
    </a>
    <a href="https://github.com/HardcodeCoder?tab=followers">
        <img
            src="https://img.shields.io/github/followers/HardcodeCoder?style=for-the-badge&logo=github&labelColor=35383E&logoColor=FFFFFF&color=539BF5"
            alt="Github Followers"
        />
    </a>
    <a href="https://x.com/hardcodecoder">
        <img
            src="https://img.shields.io/badge/@HardcodeCoder-35383E?style=for-the-badge&logo=x&labelColor=35383E&logoColor=FFFFFF&color=FFF289"
            alt="Follow on X"
        />
    </a>
    <br />
    <br />
    <!-- Contributions Streak Card -->
    <a href="https://github.com/HardcodeCoder/Github-Contribution-Streak">
        <img
            src="https://github-contribution-streak.vercel.app?user=HardcodeCoder&mode=weekly&border_radius=8"
            alt="Github Contribution Streak"
        />
    </a>
</div>
<br />

```kotlin
open class IAM(
    val name: String = "Ashuthosh Patoa",
    val aka: String = "HardcodeCoder",
    val about: String = "Kotlin Lover, Android Nerd, Writes getter & setter for $$",
    val languages: Array<String> = arrayOf(
        "Kotlin",
        "Java",
        "TypeScript",
        "C#",
        "Shell",
    ),
    val editors: Array<String> = arrayOf(
        "Zed",
        "Kate",
        "Nano",
    ),
    val activities: Array<String> = arrayOf(
        "Cycling",
        "Badminton",
        "Debloating",
        "CLI Automation",
    ),
    val status: String = "Noob!",
) {
    operator fun invoke(action: IAM.() -> Unit) = this.apply(action)

    override fun toString() =
        """
        | Intro:  $name ($aka): $about
        | Langs:  ${languages.joinToString(", ")}
        | Editor: ${editors.joinToString(", ")}
        | Hobby:  ${activities.joinToString(", ")}
        | Status: $status
        """.trimMargin()
}
```