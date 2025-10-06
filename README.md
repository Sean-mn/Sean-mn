```csharp
public class Introduce
{
    public class ME
    {
        public string name = "박현민";
        public string major = "게임 서버";
    }

    public static void Main()
    {
        var me = new ME();
        Console.WriteLine($"안녕하세요. {me.Major} 개발자 {me.Name}입니다!");
    }
}
```
