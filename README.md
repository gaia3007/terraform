# terraform

# comandi principali terraform 

# 🛠️ terraform init
▶️ Quando usarlo: all'inizio di un nuovo progetto Terraform (o dopo aver aggiunto nuovi provider o moduli).

🔍 Cosa fa:
Inizializza la cartella del progetto

Scarica i provider (es. azurerm, aws, google)

Crea la cartella .terraform/

Genera (o aggiorna) il file .terraform.lock.hcl con le versioni dei provider

📦 È come dire:
"Terraform, prepara tutto quello che serve per lavorare!"

# 🔎 terraform plan
▶️ Quando usarlo: ogni volta che vuoi vedere cosa succederà prima di applicare i cambiamenti.

🔍 Cosa fa:
Legge il file main.tf (e tutti gli altri .tf)

Confronta lo stato attuale dell'infrastruttura (da terraform.tfstate) con la configurazione

Ti mostra cosa verrà creato, aggiornato o distrutto

🛡️ È sicuro:
Non fa nulla di irreversibile! Ti mostra solo un piano.

# 🚀 terraform apply
▶️ Quando usarlo: dopo plan, per applicare davvero i cambiamenti.

🔍 Cosa fa:
Usa il piano generato (o lo rigenera)

Esegue le azioni: crea, aggiorna o distrugge le risorse in Azure (o altro provider)

Aggiorna il file terraform.tfstate con lo stato reale dell’infrastruttura

🧨 È come dire:
"Terraform, fai davvero quello che abbiamo pianificato!"
