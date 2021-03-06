![Cray supersomputer - CERN](Bilder/Cray-supercomputer-CERN.jpg)

## 6. Kommentarkonventioner

1. Undvik kommentarer   
I möjligaste mån, undvik att skriva kommentarer. Lägg istället energi på att beskriva din intention i namn på metoder,  variabler och dela upp kod på ett förståeligt sätt. 

    * <a href="https://visualstudiomagazine.com/articles/2013/06/01/roc-rocks.aspx" target="_blank">Why You Shouldn't Comment (or Document) Code</a>
    * [Comments in Clean Code? Think Documentation](http://www.daedtech.com/comments-clean-code-think-documentation/)
    * [Don’t document your code. Code your documentation.](https://dev.to/raddikx/dont-document-your-code-code-your-documentation)
    * [Fighting Evil in Your Code: Comments on Comments](https://www.simple-talk.com/opinion/opinion-pieces/fighting-evil-code-comments-comments/)
    * <a href="https://www.daedtech.com/correct-way-comment-code/" target="_blank">Is There a Correct Way to Comment Your Code?</a>

    **Undantag till denna rekommendation:**
1. TODO   
Märk kod som behöver förändras med "TODO". Kommentarer skrivs enligt mönstret:  
    `[//][mellanslag][TODO:][mellanslag][Text som börjar med stor bokstav och slutar med punkt.]`

    &#x2139; EXEMPEL:
    ```csharp
    // TODO: En kommentar.
    ```
    * [SA1005: SingleLineCommentsMustBeginWithSingleSpace](http://stylecop.soyuz5.com/SA1005.html)

1. Tomma interface-implementationer eller överridningar   
Vid implementation av interface där en eller flera metoder inte behöver användas, skriv en notering om att det görs medvetet. Det gäller även när man överrider en metod vid arv.   
    &#x2139; EXEMPEL:

    ```csharp
    public override void DoSomething()
    {
        // Method intentionally left empty.
    }
    ```
    * [Methods should not be empty](https://rules.sonarsource.com/csharp/RSPEC-1186)

1. Utanför lösningens kontroll   
Använd kommentarer när du behöver förklara skeenden, flöden etc som ligger utanför lösningens kontroll och som inte på ett bra och enkelt sätt kan beskrivas i kod.

1. Vid skapande av API  
Om du skapar ett ASP.NET Web API är dokumentation en del av lösningen. Skriv kommentarer hur man konsumerar de publika metoderna.

    * [Creating Help Pages for ASP.NET Web API](https://docs.microsoft.com/en-us/aspnet/web-api/overview/getting-started-with-aspnet-web-api/creating-api-help-pages) 
    * [Swashbuckle - Swagger for WebApi 5.5.3](https://github.com/domaindrivendev/Swashbuckle)
    * [RESTful Web API Help Documentation using Swagger UI and Swashbuckle](https://www.codeproject.com/Articles/1078249/RESTful-Web-API-Help-Documentation-using-Swagger-U)
    * <a href="Show off your API with a little Swagger..." target="_blank">Show off your API with a little Swagger...</a>
   
    
***
<span style="float:left">&#x25C0; <a href="05-Layoutkonventioner.md">Layoutkonventioner</a></span>  |  <span style="float:right"><a href="07-CSharp-konventioner_och_checklista.md">C#-konventioner och checklista</a> &#x25B6;</span>
