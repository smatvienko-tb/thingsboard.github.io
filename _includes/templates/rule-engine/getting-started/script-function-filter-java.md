We will use this script for data validation:

```bash
return typeof msg.temperature === 'undefined'
|| (msg.temperature >= -40 && msg.temperature <= 80);
```
{: .copy-code}

{% if docsPrefix == null %}
![image](https://img.thingsboard.io/user-guide/rule-engine-2-0/tutorials/getting-started/script-config-java-ce.png)
{% endif %}
{% if (docsPrefix == "pe/") or (docsPrefix contains "paas/") %}
![image](https://img.thingsboard.io/user-guide/rule-engine-2-0/tutorials/getting-started/script-config-java-pe.png)
{% endif %}