```mermaid


graph TD

Outlook --> Sunny
Outlook --> Overcast
Outlook --> Rain

Sunny --> Humidity
Humidity --> High
Humidity --> Normal
High --> humNO
Normal --> humYes

Overcast --> overcastYes

Rain --> Wind

Wind --> Weak
Wind --> Strong


Weak --> windYes

Strong --> windHumidity

windHumidity --> windHumidityHigh
windHumidity --> windHumidityNormal

windHumidityHigh --> windHumityNO

windHumidityNormal --> Temparature

Temparature --> Cool
Temparature --> Mild

Cool --> tempNo
Mild --> tempYes


humNO([NO])
humYes([Yes])
overcastYes([Yes])
windYes([Yes])
windHumidity[Humidity]
windHumidityHigh[High]
windHumidityNormal[Normal]
windHumityNO([NO])
tempYes([Yes])
tempNo([No])





```