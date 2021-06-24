# WOL mit Intel NIC
Wenn das Aufwecken trotz richtiger BIOS Einstellungen nicht funktoniert gibt es mehre Punkte, die überprpft/eingestellt werden müssen:
+ der Punkt **"Akt. bei Musterübereinstimmung"** – der muss **deaktiviert** werden. In englischen Treibern heißt der Punkt "**Pattern Match**"
+ **"PME aktivieren"** - **"Aktiviert"**
+ manchmal **"Energieeffizienter Ethernet"** auf **"Aus"** stellen 
<img width="400" alt="wol-01" src="https://user-images.githubusercontent.com/35377000/116542292-cc674400-a8ec-11eb-8d9f-81464400c343.png">
<img width="400" alt="wol-02" src="https://user-images.githubusercontent.com/35377000/116542755-4f889a00-a8ed-11eb-8757-447ed3dc9ac6.png">
<img width="400" alt="wol-03" src="https://user-images.githubusercontent.com/35377000/116552450-53221e00-a8f9-11eb-88f3-38fb5e26bf9d.png">
Das ganze ist Treiber-Abhängig. Es müssen nicht alle Punkte vorhabden sein und es kann trotzdem funktionieren.

Es müssen nicht unbediengt die "PRO Treiber" installiert werden
