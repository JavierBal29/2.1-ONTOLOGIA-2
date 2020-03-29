# 2.1-ONTOLOGIA-2
SEGUNDA ONTOLOGIA DE 2
ONTOLOGIA DE ESCUELA
<?xml version="1.0"?>
<rdf:RDF xmlns="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#"
     xml:base="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15"
     xmlns:owl="http://www.w3.org/2002/07/owl#"
     xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
     xmlns:xml="http://www.w3.org/XML/1998/namespace"
     xmlns:xsd="http://www.w3.org/2001/XMLSchema#"
     xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
     xmlns:untitled-ontology-15="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#">
    <owl:Ontology rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15"/>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Object Properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#ImparteClasesA -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#ImparteClasesA">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#RecibleClasesDe -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#RecibleClasesDe">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#esImpartidaPor -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#esImpartidaPor">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#esTomadapOr -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#esTomadapOr">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#imparteLaClaseDe -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#imparteLaClaseDe">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#tomaUna -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#tomaUna">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno"/>
    </owl:ObjectProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Data properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Cedula -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Cedula">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Horario -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Horario">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Nombre -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Nombre">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Num.Control -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Num.Control">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#int"/>
    </owl:DatatypeProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Classes
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Persona"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#DesEmprendedores -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#DesEmprendedores">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#IngConocimiento -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#IngConocimiento">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#IngSoftware -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#IngSoftware">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Investigación2 -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Investigación2">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Persona"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#NegociosElectronicos -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#NegociosElectronicos">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Persona -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Persona"/>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Redes -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Redes">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#SisOperativos -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#SisOperativos">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Materia"/>
    </owl:Class>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Individuals
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno1">
        <RecibleClasesDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro1"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat1"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat2"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno2">
        <RecibleClasesDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro2"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat1"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat3"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno3 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno3">
        <RecibleClasesDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro3"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat4"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat7"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno4 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno4">
        <RecibleClasesDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro4"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat4"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat5"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno5 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno5">
        <RecibleClasesDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro5"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat3"/>
        <tomaUna rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat5"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro1">
        <imparteLaClaseDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat1"/>
        <Cedula rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wshwsh</Cedula>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Carlos Rivera</Nombre>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro2">
        <imparteLaClaseDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat2"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro3 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro3">
        <imparteLaClaseDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat3"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro4 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro4">
        <imparteLaClaseDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat4"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro5 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro5">
        <imparteLaClaseDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat5"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro6 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro6">
        <imparteLaClaseDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat6"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro7 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro7">
        <imparteLaClaseDe rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat7"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat1">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#SisOperativos"/>
        <esImpartidaPor rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro1"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno1"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno3"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat2 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat2">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#NegociosElectronicos"/>
        <esImpartidaPor rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro2"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno5"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat3 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat3">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#IngSoftware"/>
        <esImpartidaPor rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro3"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno1"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno2"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat4 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat4">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Investigación2"/>
        <esImpartidaPor rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro4"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno1"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno2"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat5 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat5">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#DesEmprendedores"/>
        <esImpartidaPor rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro5"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno2"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno3"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat6 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat6">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Redes"/>
        <esImpartidaPor rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro5"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno4"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno5"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat7 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Mat7">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#IngConocimiento"/>
        <esImpartidaPor rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Maestro7"/>
        <esTomadapOr rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-15#Alumno3"/>
    </owl:NamedIndividual>
     </rdf:RDF>



<!-- Generated by the OWL API (version 4.5.9.2019-02-01T07:24:44Z) https://github.com/owlcs/owlapi -->
