# SQLite simple API

Goal of this project is to use Deno and Typescript and try to create simplest API for SQLite possible. SQLite is database in file that can sit in the same repository or initialized with the start of the app.

This project is based on my own and on the first iteration of it that is accessible in my profile. You can use it however you want.

## Hint(s)
<details>
  <summary>How to get started</summary>
  Visit [deno.land](https://deno.land/) to get Deno installed with your prefered way. After that, just create directory, file in it for example `api.ts` where you write your API and you can run it with `deno run api.ts -A` (because deno is really playing with security, -A allows all security measures to be eased, see docs for more detail).
</details>
<details>
  <summary>SQLite Library</summary>
  Use SQLite library for deno, if you could not find it, try [this link](https://deno.land/x/sqlite@v2.3.0). Import it with `import { DB } from "https://deno.land/x/sqlite/mod.ts";`
</details>

## Solution
Simplest iteration possible of this API with few endpoints for both SELECT and CREATE queries is [here](https://github.com/sqwyer/projects/tree/main/typescript/sqlite-simple-api/).

Submitted by [dergyitheron](https://github.com/dergyitheron)
