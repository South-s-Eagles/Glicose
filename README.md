# Glicose
Algoritmo para simulação de nível de glicose

# Script para o banco de dados

CREATE DATABASE IF NOT EXISTS glicose;

USE glicose;

CREATE TABLE IF NOT EXISTS resultados_coleta_glicose (
    tempo INT PRIMARY KEY,
    nivel_glicose FLOAT,
    status_glicose VARCHAR(20)
);

