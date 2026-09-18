\# Why I Picked This Article

\[Agentic Programming](https://martinfowler.com/bliki/AgenticProgramming.html) by Martin Fowler





Fowler uses this article to explain what “agentic programming” means. In his definition, a developer gives an LLM a task, lets it edit files and run tests, and then checks the result. He says this is different from vibe coding, where the person does not really read the generated code, and from normal IDE autocomplete, where the developer is still controlling most of the process. The main difference is whether the human actually reviews the work.



I chose this because I think this difference is important. Agentic programming and vibe coding can look almost the same. In both cases, you give the model a prompt and get code back. The real difference is whether you actually understand and review that code. Fowler also says that humans are still responsible for what the software does. I agree with that. If I cannot explain why the code works the way it does, then I probably did not really review it. I am less sure about his idea of “harness engineering.” It may become an important skill, but it could also become part of the tools themselves in the future.



## Comment by Spark Fan

Your question about whether harness engineering will become a separate skill stood out to me. Even if tools automate more of the setup, developers still need to decide which requirements and checks matter for their project. Fowler's emphasis on domain knowledge seems especially relevant here. For example, an agent could produce code that passes its tests but misses a user's actual need. I think harness engineering may become part of everyday development rather than a separate role, while choosing meaningful checks remains an important human skill.
