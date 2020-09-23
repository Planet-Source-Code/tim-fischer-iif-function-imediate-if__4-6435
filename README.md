<div align="center">

## IIF Function \(Imediate If\)


</div>

### Description

The IIF Function from Visual Basic.
 
### More Info
 
i - Boolean Expression

j - Result If i is True

k - Result If i is False

Found in Microsoft's Knowledge Base.

j - Result If i is True

k - Result If i is False


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Tim Fischer](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/tim-fischer.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |ASP \(Active Server Pages\), VbScript \(browser/client side\)

**Category**       |[System Services/ Functions](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/system-services-functions__4-23.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/tim-fischer-iif-function-imediate-if__4-6435/archive/master.zip)





### Source Code

```
Function IIf(i,j,k)
  If i Then IIf = j Else IIf = k
End Function
```

