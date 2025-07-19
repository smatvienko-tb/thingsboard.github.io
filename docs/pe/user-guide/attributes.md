---
layout: docwithnav-pe
assignees:
- ashvayka
title: Working with IoT device attributes
description: IoT device management using ThingsBoard attributes feature 
server-side-attrs-ui:
    0:
        image: https://img.thingsboard.io/user-guide/attributes/add-server-side-pe-src.png
        title: 'Select Device Group. Click on the particular device row to open device details. Select "Attributes" tab. Choose "Server attributes" scope. Click "+" Icon.'
    1:
        image: https://img.thingsboard.io/user-guide/attributes/add-server-side-pe2-src.png
        title: 'Input new attribute name. Select attribute value type and input attribute value.'
    2:
        image: https://img.thingsboard.io/user-guide/attributes/add-server-side-pe3-src.png
        title: 'Sort using "Last update time" to quickly locate the newly created attribute.'

shared-attrs-ui:
    0:
        image: https://img.thingsboard.io/user-guide/attributes/add-shared-pe-src.png
        title: 'Select Device Group. Click on the particular device row to open device details. Select "Attributes" tab. Choose "Shared attributes" scope. Click "+" Icon.'
    1:
        image: https://img.thingsboard.io/user-guide/attributes/add-shared-pe2-src.png
        title: 'Input new attribute name. Select attribute value type and input attribute value.'
    2:
        image: https://img.thingsboard.io/user-guide/attributes/add-shared-pe3-src.png
        title: 'Observe the new attribute.'

---

{% assign docsPrefix = "pe/" %}
{% include get-hosts-name.html docsPrefix=docsPrefix %}
{% include docs/user-guide/attributes.md %}