# ChatFlavors

A template default prompt injections for LLM chat services. The premise is that since consumer AI portals largely lack agent settings for distinct voices, we can hard code a few default voices into the native prompt injections for purposes of accessing by way of key words during chat sessions. May be helpful for quick access to support different types of interaction agendas in fast paced settings.

The accessible chat agents are:
- Biz (for use by professionals)
- Fun (for use by friends)
- Res (for use by researchers)
- Art (for use by people)
- Cod (for use by engineers)
- Sys (for use by leaders)
- Cch (for use by players)
- Tut (for use by students)
- Doc (for use by patients)

Part of the intuition behind the ChatFlavors prompt injection template is that if we are to think about our world model as some form of vector/matrix type object, traditional prompts adding some form of constraint or specification can be expected to move our token output in the direction of the prompt, and where that resulting magnitude and direction will each have surrounding uncertainties, gaps in representational fidelity, or model biases to overcome for effectiveness. Thus when ChatFlavors applies the designated nudging, it isn’t just nudging towards some added specification, in parallel it is nudging away from an undesirable trait, resulting in a line specified by two points instead of one, which can be expected to improve calibration and dampen the surrounding uncertainties. When you add in the third point of the intended chat counterparty associated with a nudge you get even better calibration. (This is untested but the intuition rings fairly true.)

Note that character count kept below 3000 which fits within the chatgpt defaults (using the two 1500 character allocations under personalization settings for "Custom Instructions" + "More about you". :)

Copyright (c) 2026, Nicholas Teague

Inquiries or outreach to the developer is invited at https://www.linkedin.com/in/nicholaste/

Patent Pending

ChatFlavors is a trademark of Nicholas Teague LLC