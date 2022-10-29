### Hi there 👋 I'm PienAppel!

- 🔭 I’m currently working on my minecraft server LegendsMC
- 👯 I’m looking to collaborate on minecraft plugins and discord bots
- 😄 Pronouns: He/Him
- 📫 How to reach me: 
### My Contacts!
* My Discord: PienAppel#8473
* Email: pienappel69@gmail.com

```java
public class PienAppel extends AboutMe implements Java Developer, Python Developer, {

    @Override
        public PienAppel() {
        super("PienAppel", "Earth");

        this.addCodeLanguage("Java", "Python", "Javascript");
        this.addExperience("2 years Java", "5 years on and off Python", "4 years on and off Javascript");
     }
    
	@Override
	public void codingProgress() {
		String[] learning = {"Experienced Server Plugins / Java", "Discord Bots / Node.js", "Making fun little twitter bots / Python"};
		String tryingTo = {"Become a coding expert!"};
	}
	
} 


public abstract class AboutMe {

    @Getter private final String username;
    @Getter private final String country;
  
    private Set<String> languages = new HashSet<>();
    private Set<String> experiences = new HashSet<>();
  
    public GitHubProf(String username, String placeilive) {
        this.name = username;
        this.country = placeilive;
    }
  
    public void addCodeLanguage(String... language) {
        this.languages.addAll(language);
    }
    
    public void addExperience(String... experience) {
        this.experiences.addAll(experience);
    }
  }

```
