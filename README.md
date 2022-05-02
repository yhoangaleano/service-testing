# ServiceTesting

- En las pruebas se debe seguir el mantra de AAA

// Arrange - Prepara
// Act - Actuá
// Assert - Afirma

- Para verificar si una variable esta definida o no se usa

expect( name ).toBeDefined();
expect( name2 ).toBeUndefined();

- Para sacar el reporte de cobertura ejecutamos el siguiente comando

ng test --no-watch --code-coverage
