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

My name is Alexandre. I am a former university student in computer science (2012-2017). I mainly learnt Java and C. I am currently a self learner coder looking for a formation to complete my skills.

## š Learning list

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
**sickCoder/sickCoder** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
