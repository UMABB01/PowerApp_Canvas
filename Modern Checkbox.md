# Reset Modern Checkbox
>There is no reset option in Modern Checkbox

>Add double updateContext to button onSelect

Powerfx:
```
UpdateContext({NotifyCheckReset_Context : true});
UpdateContext({NotifyCheckReset_Context : false});
```
> On Checked of Checkbox

//Whether its in gallery or multi selections
The default would be "false"

> Add the Context with OR

Powerfx:
```
false Or NotifyCheckReset_Context
```
