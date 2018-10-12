## Travis Buddy
Hey **{{author}}**, 
Please read the following log in order to understand the failure reason. 
It'll be awesome if you fix what's wrong and commit the changes accordingly


This is test branch

MKD


Jobs:

{{#jobs}}
### Display name: {{displayName}}
Scripts: {{#scripts}}
<details>
  <summary>
    <strong>
     Command: {{command}}
    </strong>
  </summary>

```
Contents: {{&contents}}
```
</details>
<br />
{{/scripts}}
{{/jobs}}
