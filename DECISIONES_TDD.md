# Diario TDD

## Ciclo 1

### Red
- Prueba añadida: 
    test_one_feature_is_tiny()
- Técnica de diseño de pruebas empleada: 
    TDD
- Motivo de elegir este caso:
    El test ya está escrito pero falta la implementación de la función que se quiere probar.
- Fallo observado:
    FAILED tests/test_size.py::test_one_feature_is_tiny - NotImplementedError: Implementar mediante TDD

### Green
- Código mínimo escrito:
    def classify_model_size(feature_count: int) -> str:
        return "tiny"
- Resultado de las pruebas: 
    1 passed

### Refactor
- Mejora realizada, o motivo por el que no era necesaria:
    No se necesita refactorizar todavía porque no hay duplicación ni escritura que mejorar.
---

Copiad este bloque para cada ciclo.
