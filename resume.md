# Karina Shik
### Web-developer


Contact info:
* myemail@gmail.com
* linkedin.com/in/name-surname


## Summary


### Personal info

An energetic and imaginative junior web developer who is able to work alongside other talented IT professionals in creating websites
to the very highest standards.

Experience in Design and Development of GUI using C# Win Forms. Moderate knowledge in Unity. Good hands-on experience and knowledge of HTML and CSS.


### Skills

C#, HTML5, CSS3


### Code examples (latest)

```c#
public int[,] RandGeneration(int row, int col)
{
    Random random = new Random();
    int[,] arr = new int[row, col];

    for (int i = 0; i < row; i++)
    {
        for (int j = 0; j < col; j++)
        {
            arr[i, j] = random.Next(8, 400);
        }
    }
    return arr;
}
public void SequenceToFile(string path, string binary_sequence)
{
    using (StreamWriter file = new StreamWriter($"{path}", false, System.Text.Encoding.Default))
    {
        file.WriteLine(binary_sequence);
    }
}
public string SequenceFromFile(string path)
{
    try
    {
        using (StreamReader file = new StreamReader(path))
        {
            return file.ReadToEnd();
        }
    }
    catch (Exception excpt)
    {
        return excpt.Message;
    }
}
```


### Experience

Web developer: LEGAT.BY, May 2019 - March 2020


### Education

Web developer: BSU, 2017 - 2021


### English

Spoken English
