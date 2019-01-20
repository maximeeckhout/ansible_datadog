# Ansible: Datadog
Basic Ansible Role for setting up Datadog. Get your api_key [here](https://www.datadoghq.com/lpg/?utm_source=Advertisement&utm_medium=GoogleAdsNon1stTierBrand&utm_campaign=GoogleAdsNon1stTierBrand-NonENES&utm_content=Datadog&utm_keyword=datadog&utm_matchtype=e&gclid=CjwKCAiA1ZDiBRAXEiwAIWyNCzI9nSzi93k92PREafQOONhcxRqoRaZ-Hc9pzEvtyvbvlMcM5csVRxoC0jgQAvD_BwE)

## Role Variables

api_key => set your own api_key

Example:

```
#LAMP SERVER
- hosts: LAMP
  become: true
  vars:
    - api_key: '0643a14d6101fda2f454507d23732fcc'
  roles:
    - maximeeckhout.datadog
```

