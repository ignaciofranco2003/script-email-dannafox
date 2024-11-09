	py -m venv .venv

        .venv\Scripts\activate
	
 	pip install -r req.txt

        deactivate

- llamar a la funcion con una id de campaña (solo se pueden generar reportes de campañas finalizadas)

	generate_campaign_report(campania_id)

VER EJEMPLO "asignar_id.py"
