# 👨‍💻 Developer Profile

```csharp
public class DeveloperProfile
{
    public string Name { get; set; }
    public string Title { get; set; }
    public List<string> ProgrammingLanguages { get; set; }
    public List<string> Tools { get; set; }
    public string AboutMe { get; set; }

    public DeveloperProfile()
    {
        Name = "Ejder";  // Kişinin adı
        Title = "Yazılım Öğrencisi";  // Başlık
        ProgrammingLanguages = new List<string> { "C#", "JavaScript", "PHP", "Python", "CSS", "HTML" }; // Programlama dilleri
        Tools = new List<string> { "Visual Studio", "Unity", "Blender", "Android Studio" };  // Kullanılan araçlar
        AboutMe = "Ben, yazılımda gelişmek için elinden geleni yapan bir öğrenciyim.";  // Kendini tanıtma
    }
}
