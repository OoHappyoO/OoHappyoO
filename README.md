 <h2 align="center">Hi there 👋</h2>

```kt
import java.time.LocalDate

typealias L = ProgrammingLanguage

object Happy {

    var name = "Happy"

    private val gender: String

    val birthdate = LocalDate.of(2008, 1, 25)

    fun age(): Int = LocalDate.now().year - birthdate.year

    val lang = mutableListOf(
            L.CPP,
            L.JAVA,
            L.KOTLIN
    )

    val links = mutableMapOf(
            "Github" to "https://github.com/OoHappyoO",
            "bilibili" to "https://space.bilibili.com/391643233",
            "Luogu" to "https://www.luogu.com.cn/user/191252",
            "Personal Website ( Unavailable )" to "https://happy.gg"
    )

    val ids = mutableMapOf(
            "QQ" to "1799842825",
            "WeChat" to "HappyWasBanned",
            "Minecraft Java Edition" to "OoHappyoO"
    )

    val achievements = mutableMapOf(
            LocalDate.of(2020, 11, 7) to "CSP-J 1=",
            LocalDate.of(2023, 11, 18) to "NOIP 1=",
            LocalDate.of(2024, 10, 26) to "CSP-S 1="
    )
}
```

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=OoHappyoO)
