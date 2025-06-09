# **Actividad-22**

## **Integrantes:**

| Integrante | Codigo | GitHub |
|------------|--------|--------|
| Chowdhury Gomez, Junal Johir | 20200092K | [JunalChowdhuryG](https://github.com/JunalChowdhuryG/Actividades-CC3S2) |
| La Torre Vasquez, Andres Sebastian | 20212100C | [Jun1el](https://github.com/Jun1el/Desarrollo-de-Software-25-1) |
| Zapata Inga, Janio Adolfo | 20212636K | [Janiopi](https://github.com/Janiopi/Actividades-CC3S2) |


## Fase 1


## Fase 2

**NetworkModuleOutput**: 

lee configuración externa del archivo network_outputs.json

**ServerFactoryModule** : 

Recibe dependencias a través del constructor
```python
# inyeccion desde constructor
self._network = NetworkModuleOutput(outputs_path)

# uso de las dependencias
"subnet_name": self._network.name,
"subnet_cidr": self._network.cidr,
```

Algunos problemas que vimos son: 

- **Dependencias Hardcodeadas**
  Ya que la clase ServerFactoryModule está directamente acoplada a NetworkModuleOutput
 
- **Testing** 
  Dificultad para crear mocks o stubs para pruebas unitarias 
## Fase 3



## Fase 4



## Fase 5
