How to export a closure rule from Teamcenter:

1.   Find the UID of the ClosureRule, using the query: __Closure_Rule_Objects, and find the UID using "Print Object"

![CR_UID](https://user-images.githubusercontent.com/130765090/236389582-88497bdc-686e-44bf-a344-1f76e7585067.png)

2. Then, use the **utility: tcxml_export -u=infodba -p='password' -g=dba -uid='UID of ClosureRule' -file='output filename'**
