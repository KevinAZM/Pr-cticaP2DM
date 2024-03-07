let FG = function(a, b, c) {
    const determi = Math.pow(b, 2) - 4 * a * c;
    if (determi < 0) {
      return 'no se encuentra ninguna solucion';
    } else {
      const pos = (-b + Math.sqrt(determi)) / (2 * a);
      const neg = (-b - Math.sqrt(determi)) / (2 * a);
      return [pos, neg];
    }
  };
  
  function valor(a, b, c, funcion) {
    return funcion(a, b, c);
  }
  const resul1 = FG(3, 4, 3);
  console.log(`Resultado 1: ${resul1}`);
  
  const resul2 = FG(0, 3, 2);
  console.log(`Resultado 2: ${resul2}`);
  
  const resul3 = FG(8, 6, 2);
  console.log(`Resultado 3: ${resul3}`);
  
  const resul4 = FG(1, 1, 1);
  console.log(`Resultado 4: ${resul4}`);

  const resul5 = FG(5, 9, 3);
  console.log(`Resultado 5: ${resul5}`);
  
  const resul6 = FG(8, 3, 3);
  console.log(`Resultado 6: ${resul6}`);
  
  const resul7 = FG(3, 5, 9);
  console.log(`Resultado 7: ${resul7}`);

const resul8 = FG(9, 4, 0);
  console.log(`Resultado 8: ${resul8}`);

  const resul9 = FG(14, 12, 11);
  console.log(`Resultado 9: ${resul9}`);

  const resul10 = FG(2, 8, -2);
  console.log(`Resultado 10: ${resul10}`);
