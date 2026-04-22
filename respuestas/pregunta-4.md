MATCH (p:Persona)-[]->(pr:Proyecto) 
RETURN DISTINCT p.nombre, pr.nombre