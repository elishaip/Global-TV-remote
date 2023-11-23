# Global-TV-remote
Building a TV remote through the Home Assistant system

# שלט TV גלובלי
בניית שלט דרך מערכת Home Assistant

לאחר יישום הג'יט הזה - יהיה לך יכולת לבנות שלט TV וירטואלי בסמארטפון, ראה צילום מסך לדוגמא:

![Remote TV](https://github.com/elishaip/Global-TV-remote/assets/89676547/4fa9baad-7a51-4af9-9922-362b1c324984)

יש צורך להתקין תוסף בשם מחנות HACS מתוך HA, ראה צילום מסך:

![image](https://github.com/elishaip/Global-TV-remote/assets/89676547/4f71012c-b5ba-4268-a7f3-3809be95b1c9)

הוסף כרטיס חדש מסוג "Manual" ולהכניס את תוכן הקוד YAML:
{{ "יבנה" in state_attr('binary_sensor.red_alert', 'data').split(', ') }}




