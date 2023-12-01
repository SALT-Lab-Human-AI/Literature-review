### The Rise and Potential of Large Language Model Based Agents: A Survey



### Identifying the Risks of LM Agents with an LM-Emulated Sandbox

Abstract

>Recent advancesin Language Model (LM) agents and tool use,exemplified byapplicationslike ChatGPT Plugins, enable a rich set of capabilities but also amplify potential risks-suchas leaking private data or causing financial lossesIdentifying these risks is labor-intensive.necessitating implementing the tools, setting up the environment for eachtest scenariomanually,and finding risky cases.As tools and agents become more complex, the high costof testing these agents will make it increasingly diffcult to find high-stakes. long-tail risksTo address these challenges,we introduce ToolEmu: a framework that uses a LM to emulatetool execution and enables scalable testing of LM agents against a diverse range of tools andscenarios. Alongside the emulator, we develop an LM-based automatic safety evaluator thatexamines agent failures and quantifies associated risks. We test both the tool emulator andevaluator through human evaluation and fnd that 68.8% of failures identifed with ToolEmuwould be valid real-world agent failures. Using our curated initial benchmark consisting ot36 high-stakes tools and 144 test cases, we provide a quantitative risk analysis of currentLM agents and identify numerous failures with potentially severe outcomes. Notably, eventhe safest LM agent exhibits such failures 23.9% of the time according to our evaluator.underscoring the need to develop safer LM agents for real-world deployment.



### SafetyBench: Evaluating the Safety of Large Language Models with Multiple Choice Questions



