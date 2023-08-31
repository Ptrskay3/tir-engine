<img src='https://s3.eu-central-1.amazonaws.com/factory.codeyard.eu/tir_git_cover.png' >
<br/>
<center>

[![Discord Badge](https://img.shields.io/badge/-@Factory-7289da?style=flat-square&labelColor=7289da&logo=discord&logoColor=white&link=https://discord.gg/codeyard-823104905141157918)](https://discord.gg/codeyard-823104905141157918) [![Twitch Badge](https://img.shields.io/badge/-@codeyard-9146FF?style=flat-square&labelColor=9146FF&logo=twitch&logoColor=white&link=https://twitch.tv/codeyard)](https://twitch.tv/codeyard) [![Youtube Badge](https://img.shields.io/badge/-@teamcodeyard-FF0000?style=flat-square&labelColor=FF0000&logo=youtube&logoColor=white&link=https://www.youtube.com/@teamcodeyard)](https://www.youtube.com/@teamcodeyard) [![Twitter Badge](https://img.shields.io/badge/-@iujlaki-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/iujlaki)](https://twitter.com/iujlaki) 

</center>
<h2> 𝐇𝐞𝐥𝐥𝐨 𝐭𝐡𝐞𝐫𝐞, coders! <img src="https://s3.eu-central-1.amazonaws.com/factory.codeyard.eu/Hi.gif" width="32px"></h2>
<p>
The T.I.R. project is an open-source community project that tries to help beginners to acquire theoretical knowledge in any field.
The project consists of several modules, <b>tir-engine</b> is responsible for communication with OpenAI.
</p>

<p>The platform developed by the <b><a href="https://factory.codeyard.eu/"> CodeYard Factory</a></b>, the hungarian developer community.</p>

<h3>API documentation</h3>
<p>
We use Postman to define REST endpoints, you can find our collection <a href="https://documenter.getpostman.com/view/795261/2s9Xy6pUdQ#ee63743c-87e3-471f-8b24-370431aea6b4">here</a>!
</p>

<h3>How to use?</h3>

```rust

use tirengine::{ GPT };

let gpt = GPT::new(String::from("VERY_SECRET_OPENAI_KEY"));

```

<h3>How to run test cases?</h3>

```bash
export OPENAI_SK = "VERY_SECRET_OPENAI_KEY"
cargo test
```

<p>loading...</p>
