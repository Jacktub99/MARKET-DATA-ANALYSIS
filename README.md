----------LEGGIMI----------
MarketData è un'applicazione web che punta alla libertà di leggere le asset chart finanziarie, senza il coinvolgimento dei broker e la conseguente iniezione di spread, slippage e altro.

ISTRUZIONI ALL'USO

Prerequisites
Make sure you have the following tools installed:

Python (3.x)
Node.js (and npm)
Django
Django REST Framework
React
Tailwind CSS

Django Backend Setup
Create a Virtual Environment: Navigate to the backend directory and create a virtual environment.

cd backend
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
Install Python Dependencies: Install required packages from requirements.txt.

pip install -r requirements.txt
Apply Migrations: Navigate to the backend Django application and set up the database with initial migrations.

cd backend
python manage.py migrate
Create Superuser (Optional): Create a superuser account to access Django's admin panel if needed.

python manage.py createsuperuser
Run the Django Server: Start the development server.

python manage.py runserver

4. Access the Application
Django backend will be available at http://localhost:8000.

Quando il sito viene caricato, ci troveremo davanti alla pagina HOME, nella quale potremmo scegliere come muoverci all'interno del sito.

1) REGISTRAZIONE UTENTE, prima di tutto è consigliabile completare la registrazione attraverso la pagina apposita, per godere di un'esperienza migliore. Registrarsi infatti farà si che l'utente possa salvare i propri asset preferiti nella sezione "Preferiti",
per poter godere di un'esperienza più fluida ed immediata, visualizzando all'istante i propri asset e confrontando i prezzi che si vogliono.
2) VISUALIZZAZIONE ASSET, recarsi nella pagina "Forex" per visualizzare l'asset che vogliamo con il lasso di tempo che l'utente preferisce. Una volta inserito il codice finanziario dell'asset e inserite le date che si vogliono visualizzare, premere il tasto "ADD"
per caricare il chart dell'asset da noi scelto. Premere sul pulsante giallo "STELLA" per salvare l'asset tra i preferiti. Per trovare il codice preciso dell'asset di riferimento, basta andare su YFinance e cercare il nome dell'asset che desideriamo visualizzare,
il codice sarà visualizzabile tra parentesi tonde alla destra del nome del titolo azionario. per esempio, se volessimo visualizzare il grafico della Apple, basterà ricercare quest'ultima all'interno di YFinance e copiare il TAG tra parentesi (AAPL), e poi incollarlo
su MarketData.

Buon divertimento Traders! ;-) 
