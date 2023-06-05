//Programmers: Hayden Coates. Roman Cleary
//Date: 5.26.2023 
//Program: Competition 
async function startProgram() { 
await scrollMatrixText('Start!', { r: 10, g: 255, b: 10 }, 20, true); 
await roll(0, 75, 2.05); 
setMainLed({ r: 0, g: 0, b: 90 }); 
await roll(90, 80, 1.5); await Sound.Animal.play(true); 
await roll(180, 39, 2.65); await roll(220, 50, 1.79); 
setMainLed({ r: 255, g: 0, b: 0 });
await roll(130, 40, 1.25); await roll(40, 60, 1);
await Sound.Animal.play(true);await roll(130, 50, 1.25); 
await roll(220, 40, 1.06); await roll(130, 20, 1.8); 
setMainLed({ r: 0, g: 255, b: 0 });
await delay(1);
await roll(130, 42, 1);
await delay(1);
await roll(33, 50, 1.26);
await delay(1);
await roll(350, 40, 1.45);
await delay(1);
await Sound.Animal.play(true);
await roll(30, 90, 1);
await delay(1);
setMainLed({ r: 255, g: 0, b: 255 });
await delay(1);

}

