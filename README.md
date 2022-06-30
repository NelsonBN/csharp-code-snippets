# C# code snippets
Some code snippets to increase productivity writing code


## Custom code snippets in this repository
Location: `this repository` > `dist`
- [`xfact`](#custom-snippet-xfact)
- [`xffact`](#custom-snippet-xffact)


## How to add custom code snippets?


### In visual studio

1. In the **Tools** menu > **Code Snippets Manage**
![Code Snippets Manage](/media/vs-options-1.png "Code Snippets Manage")

2. Click the **Import button**.
![Code Snippets Manage](/media/vs-options-2.png "Code Snippets Manage")



## Custom code snippets

### `xfact` <a name="custom-snippet-xfact"></a>
Create a Xunit test method with pattern "Given When Then" and, "AAA"

```csharp
[Fact]
public void Given_When_Then()
{
    // Arrange


    // Act


    // Assert
    throw new System.NotImplementedException();
}
```

### `xffact` <a name="custom-snippet-xffact"></a>
Create a full Xunit test method with pattern "Given When Then", "AAA", "description" and "Trait"

```csharp
[Fact(DisplayName = "TODO: to change")]
[Trait("Category", "TODO: to change")]
public void Given_When_Then()
{
    // Arrange


    // Act


    // Assert
    throw new System.NotImplementedException();
}
```



## Most used defaults code snippets

### Constructors
- `ctor`: Create a constructor

### Properties
- `prop`: Create a property with public getter and setter
- `propg`: Create a property with public getter only
- `propfull`: Create a property with public getter and setter and private setter

### Console
- `cw`: Add a function to write to console