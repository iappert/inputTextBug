# inputTextBug
Minimal set up for reproducing rider bug.

Rider reports a bug when analyzing file "Views/ValidatableInputText.razor". 

Report issue:
```
<InputText>\Views\ValidatableInputText.razor (2 errors)
  <InputText>\Views\ValidatableInputText.razor:106 Argument type 'System.Linq.Expressions.Expression<System.Func<string>>' is not assignable to parameter type 'System.Linq.Expressions.Expression<System.Func<TValue>>'
  <InputText>\Views\ValidatableInputText.razor:136 Argument type 'string' is not assignable to parameter type 'TValue'
```

Expected behavior:
no issue
