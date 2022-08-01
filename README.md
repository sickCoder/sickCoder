## `System.out.println("Hello world!");`
```
public class App 
{
    public static void main( String[] args )
    {
        new GitHubUser().printGitHubUser();
    }
}
```
```
public class GitHubUser {
	private String firstName, lastName, country;
	private String[] codingLanguages = {"Java", "C", "HTML", "CSS"};
	
	public GitHubUser() {
		firstName = "Alexandre";
		lastName = "Gibault";
		country = "France";
	}
	

	public void printGitHubUser() {
		System.out.println(firstName+" "+lastName);
		System.out.println("From : " + country);
		System.out.println("Coding languages : ");
		for (int i = 0; i < codingLanguages.length; i++)
			System.out.println("- " + codingLanguages[i]);
	}
}
```
## About me

My name is Alexandre. I'm currently a student in DevOps applications conception and development at [Simplon.co](https://en.simplon.co/). I started to code at university back to 2012. I mainly learnt Java, C and a bit of HTML and CSS.

## 📚 Learning list

1. Git and GitHub
   - Add some repos
   - Deepen Git usage skill
2. JavaScript
3. MySQL
4. NodeJs
5. JavaScrip framework
6. ORM
7. Linux CLI
8. Java
   - Swing
   - Other usefull libraries (you may suggest me some)
   - streams
9. C (Not used it since a long time)
   - Remembering how to correctly use files operations
   - Remembering structures set up
<!--
**sickCoder/sickCoder** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
