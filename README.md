# transform-accents
This library transforms all accented characters into unaccented ones 

# Usage
````Typescript
import { transformAccents } from "https://deno.land/x/transform_accents/mod.ts";

const transformText: string = transformAccents('Aéùè');

console.log(transformText); //Aeue
````