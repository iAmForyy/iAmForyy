```java
public class iAmForyyDev extends GitHubUser {

  public iAmForyyDev(){
    super("iAmForyyDev_", "Perú", 17);
    
    this.addLanguage("Java"); 
    this.addExperience(
      "Spigot API", 
      "Configurator", 
      "Setups Creator",
      "Furious Studios",
      "Furious Community"
    );
  }
}

public abstract class GitHubUser {

  @Getter private final String username;
  @Getter private final String country;
  @Getter private final int age;

  private final Set<String> languages = new HashSet<>();
  private final Set<String> experiences = new HashSet<>();

  public GitHubUser(String username, String country, int age) {
      this.name = username;
      this.country = country;
      this.age = age;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```
![iAmForyy GitHub Stats](https://github-readme-stats.vercel.app/api?username=iAmForyy&show_icons=true&theme=tokyonight) ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=iAmForyy&theme=tokyonight)
 
