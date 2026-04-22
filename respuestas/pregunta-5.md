MATCH path = (p:Persona)-[:ESTUDIO_EN]->(u:Universidad)
RETURN relationships(path) as relaciones