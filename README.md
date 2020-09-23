<div align="center">

## Orientation \- DataReport \- 1 line \- no API calls \- unbelieveable\!\!\!\!


</div>

### Description

This code will change the orientation of the output before rptName.Show is executed. This is only one line of code, but it will do what some of the others have done with 4 pages of code. Really!!!!!
 
### More Info
 
Changes Orientation to Portriat or to Landscape


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[John W\. Hutchison](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/john-w-hutchison.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/john-w-hutchison-orientation-datareport-1-line-no-api-calls-unbelieveable__1-11138/archive/master.zip)





### Source Code

```
'This is only one line of code. The second line is the Show Method - which you have to do anyway. The rptHistSalary is the name of the report. Put this line before the Show and the report orientation will be changed. The nice thing is you don't have to change the printer orientation back because you have only changed the orientation for the report and not the printer! Since you change the orientation by report name this will not affect other reports. For reports that you want Portriat you don't have to do anything - Portriat is the default. Also, what is nice is that you don't have to be concerned about Network issues nor about operating system issues. The orientation is all done within VB. This one line of code requires that you have Service Pack 4 installed on you computer or you will get a compile error. You can get the SP 4 from Microsoft.This is my first submission to PlanetSourceCode and I am just learning how this web site works. Hope this helps.
rptHistSalary.Orientation = rptOrientLandscape
rptHistSalary.Show 1, Me
```

