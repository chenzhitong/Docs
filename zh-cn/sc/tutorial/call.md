# 合约调用

```c#
<<<<<<< HEAD
[AppCall]("XXXXXXXXXX")//ScriptHash
=======
[Appcall]("XXXXXXXXXX")//ScriptHash
>>>>>>> e5e43331cd35f87f336ded6b98df4277306e0359
public static extern int AnotherContract(string arg);

public static void Main()
{
    AnotherContract("Hello");    
}
```

在智能合约中，如果想调用其它已发布到区块链上的智能合约可以通过这种方式。首先通过 AppCall 和要调用的合约的脚本散列来在 C# 中添加声明。然后就可以在代码中对其进行调用了。