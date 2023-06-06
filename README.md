# 📚 Reading: Introduction to Chatbots

<p><em>Select the tabs to navigate through the content.</em></p>
<div style="margin: 1em 0%; padding: 10px 15px; border: 2px solid #A2AAAD; background: #ffffff; font-size: 100%; overflow: auto;">
    <div class="enhanceable_content tabs">
        <ul>
            <li><a href="#fragment-1">Introduction</a></li>
            <li><a href="#fragment-2">NLP, Chatbots, and LLMs</a></li>
            <li><a href="#fragment-3">Rule-Based Chatbots</a></li>
            <li><a href="#fragment-4">Interact with a Rule-Based Chatbot</a></li>
            <li><a href="#fragment-5">LLMs and Chatbots</a></li>
            <li><a href="#fragment-6">Summary</a></li>
            <li><a href="#fragment-7">Check Your Understanding</a></li>
        </ul>
        <div id="fragment-1" style="overflow: auto:;">
            <h3>Introduction</h3>
            <p>Chatbots have a rich history that dates back several decades. The concept of conversational agents emerged in the mid-20th century with Alan Turing's proposal of the "Turing Test" to evaluate machine intelligence. In the 1960s, Joseph Weizenbaum created ELIZA, the first chatbot, which used simple language processing techniques to simulate human-like conversations. Subsequent advancements in natural language processing and AI algorithms led to the development of more sophisticated chatbots like ALICE in 1995.</p>
            <p>In the early 2000s, chatbots gained popularity with the rise of the internet and messaging platforms. Companies started integrating chatbots into their websites and customer support systems to provide automated assistance.&nbsp;</p>
            <p>While primitive and advanced chatbots both rely on the foundations of linguistics and natural language processing, primitive chatbots use a rule-based approach that limits the scope of the chatbot’s usefulness. Recent advancements in AI, particularly with large-scale language models and machine learning techniques like GPT (Generative Pre-trained Transformer), have further propelled chatbot capabilities, by allowing them to be informed by Large Language Models, or LLMs.</p>
            <h4>Lesson Objectives</h4>
            <p>By the end of this lesson you will be able to&nbsp;</p>
            <ul>
                <li>Define NLP and LLMs and their role in creating chatbots</li>
                <li>Recall the rule-based techniques for creating chatbots</li>
                <li>Identify the disadvantages of rule-based chatbots</li>
            </ul>
        </div>
        <div id="fragment-2" style="overflow: auto:;">
            <h3>NLP, Chatbots, and LLMs</h3>
            <p>Natural Language Processing (NLP) is a branch of artificial intelligence that focuses on the interaction between computers and human language. It involves the ability of machines to understand, interpret, and generate human language in a way that is meaningful and contextually appropriate.&nbsp;</p>
            <p>NLP plays a critical role in the development of chatbots by enabling them to understand and respond to user queries and conversations. By applying NLP techniques, chatbots can process and analyze text input, extract relevant information, and generate appropriate responses. NLP algorithms help chatbots to interpret the nuances of human language, handle variations in phrasing, and provide contextually relevant answers. Through NLP, chatbots can engage in more natural and meaningful interactions with users, enhancing their usability and effectiveness.</p>
            <p>In the context of Natural Language Processing (NLP), LLMs stand for Large Language Models. LLMs are advanced AI models that have been pre-trained on massive amounts of text data from the internet. These models are designed to learn the statistical patterns, grammar, and semantic relationships present in human language. LLMs, such as OpenAI's GPT (Generative Pre-trained Transformer), are based on deep learning architectures and utilize transformer networks to capture the complex dependencies and contexts within language.</p>
        </div>
        <div id="fragment-3" style="overflow: auto:;">
            <h3>Rule-Based Chatbots</h3>
            <p>Rule-based chatbots have been widely used in various applications, but they come with inherent limitations.&nbsp;</p>
            <p>One practical example that is analogous to early rule based chatbots are voice prompting systems. You might be familiar with these if you have ever called your bank and been prompted to listen to the choices and select the number that matches the reason for your call on the keypad. While most users find these systems inherently annoying (because most of our problems do not fit neatly into boxes), they illustrate the simple rule based system that also motivates rule based chatbots.</p>
            <p>When you call the bank, you are prompted to return one of a few responses using your keypad:</p>
            <ul>
                <li>Press 1 to hear your balances</li>
                <li>Press 2 for mobile banking</li>
                <li>Press 3 to speak with a teller</li>
            </ul>
            <p>This simple system is useful enough to redirect a good portion of calls away from live tellers, but can still lead to frustrating wait times and a string of transfers and customers are shuffled from different representatives depending on their specific problem.</p>
            <p>As the use of online banking became more popular, the use of rule based chatbots to direct customers to different departments based on their inquiry became more common.&nbsp;</p>
            <p>While these were an improvement from the uncanny voice of the phone systems because the text based aspect hid some of the “robotic” elements of the experience. They still had a lot of limitations.&nbsp;</p>
        </div>
        <div id="fragment-4" style="overflow: auto:;">
            <h3>LLMs and Chatbots</h3>
            <p>LLMs have revolutionized NLP by enabling a wide range of language-related tasks, including text generation, translation, summarization, and sentiment analysis. They can generate coherent and contextually-relevant text based on input prompts or queries. LLMs have the ability to understand the structure and meaning of sentences, recognize word associations, and generate natural-sounding responses. By leveraging the knowledge gained from pre-training on large datasets, LLMs provide a foundation for building more sophisticated chatbots and language-based AI systems.</p>
            <p>LLMs are powerful AI models that have been trained on massive amounts of text data, enabling them to understand and generate human-like language. They form the backbone of many NLP applications, including chatbots, by providing the underlying language generation capabilities that allow for more natural and contextually appropriate conversations with users.</p>
            <p>The relationship between LLMs and modern chatbots is symbiotic. LLMs serve as the backbone for chatbot systems, providing the underlying language generation capabilities. Chatbots leverage LLMs by fine-tuning them on specific tasks and incorporating prompt engineering techniques to optimize their performance. This combination of advanced language models and prompt engineering has propelled chatbots to new levels of sophistication, enabling them to deliver personalized experiences, streamline interactions, and provide quick and accurate information.</p>
            <p>On the other hand, AI assistants are more advanced systems that utilize natural language processing and machine learning techniques to understand and respond to user queries, offering personalized assistance and performing tasks.</p>
            <h4>Let’s explore why</h4>
            <ol style="list-style-type: decimal;">
                <li>Rule-based chatbots heavily rely on predefined sets of rules and patterns to generate responses. These rules are typically designed by human experts and often lack the flexibility to handle complex and dynamic conversations. As a result, rule-based chatbots may struggle with understanding user intents that deviate from the predefined rules, leading to inaccurate or irrelevant responses. <br><em>Example: </em>You need help with something on your account, but you cannot remember your account number. If the chatbot has a rule that requires you to input an account number before filtering your inquiry, the chatbot is no longer helpful for you.</li>
                <li>Rule-based chatbots are limited in their ability to adapt to new or evolving language patterns. Since their responses are based on explicit rules, they may struggle with handling variations in phrasing, slang, or colloquial expressions. <br><em>Example:</em> Users speaking different dialects of English may need to be handled differently. With a rule-based chatbot, a different chatbot for each dialect would need to be developed. Users would have to indicate which version they want to use.</li>
                <li>They typically operate on a one-turn basis, meaning they do not have the ability to maintain context or remember previous interactions. They may fail to understand references made in earlier exchanges or fail to provide relevant responses that take into account the conversation history. This lack of contextual understanding can result in frustrating and disjointed user experiences.<br><em>Example:</em> If a user needs to access information regarding on ongoing customer service inquiry, it may be necessary to re-enter all of the relevant details at the beginning of each session.&nbsp;</li>
            </ol>
        </div>
        <div id="fragment-5" style="overflow: auto:;">
            <h3>Interact with a Rule-Based Chatbot</h3>
            <p>Remember when we mentioned one of the earlier chatbots, ELIZA? If you want to experience what it feels like to use an antique chatbot, you can visit her at her website. <a class="inline_disabled" href="https://web.njit.edu/~ronkowit/eliza.html" target="_blank">ELIZA</a> is a fun toy to play around with, but it is clear that her limitations can hinder their ability to provide accurate and relevant responses in dynamic and complex conversational scenarios.</p>
            <p>To overcome these limitations, more advanced approaches, such as large language models and LLMs are employed to develop chatbots that can handle a wider range of user inputs and deliver more human-like interactions. Interacting with Eliza will help you appreciate how much chatbots have improved over the last few decades.</p>
        </div>
        <div id="fragment-6" style="overflow: auto:;">
          <h3>LLMs and Chatbots</h3>
            <p>LLMs have revolutionized NLP by enabling a wide range of language-related tasks, including text generation, translation, summarization, and sentiment analysis. They can generate coherent and contextually-relevant text based on input prompts or queries. LLMs have the ability to understand the structure and meaning of sentences, recognize word associations, and generate natural-sounding responses. By leveraging the knowledge gained from pre-training on large datasets, LLMs provide a foundation for building more sophisticated chatbots and language-based AI systems.</p>
            <p>LLMs are powerful AI models that have been trained on massive amounts of text data, enabling them to understand and generate human-like language. They form the backbone of many NLP applications, including chatbots, by providing the underlying language generation capabilities that allow for more natural and contextually appropriate conversations with users.</p>
            <p>The relationship between LLMs and modern chatbots is symbiotic. LLMs serve as the backbone for chatbot systems, providing the underlying language generation capabilities. Chatbots leverage LLMs by fine-tuning them on specific tasks and incorporating prompt engineering techniques to optimize their performance. This combination of advanced language models and prompt engineering has propelled chatbots to new levels of sophistication, enabling them to deliver personalized experiences, streamline interactions, and provide quick and accurate information.</p>
        </div>
        <div id="fragment-7" style="overflow: auto:;">
            <h3>Summary</h3>
            <p>In this lesson, we introduced the topics of natural language processing, chatbots, and LLMs. We reviewed the history of chatbots and rule-based techniques that were used in the past. Then, we discussed how advances in machine learning and artificial intelligence have created more powerful chatbots using LLMs, such as ChatGPT.</p>
            <p>As AI technologies continue to advance, the relationship between LLMs and chatbots will remain vital. Ongoing research and development in the field of language models will drive further improvements in chatbot capabilities, fostering more natural and intelligent conversations between humans and machines.</p>
        </div>
        <div id="fragment-7" style="overflow: auto:;">
            <h3>Check Your Understanding</h3>
            <p>In this section you will be able to quiz yourself on the key takeaways from the readings. These questions will help prepare you for the other assessments in the module.&nbsp;</p>
            <p><em>Select the question to view the answer.</em></p>
            <details>
                <summary style="padding: 15px; font-size: 150%; border: 2px solid #A2AAAD;">What is the definition of a NLP and the role it plays in creating chatbots?</summary>
                <p style="margin-left: 10px;">A NLP is an acronym for Natural Language Processing, a branch of artificial intelligence that focuses on the interaction between computers and human language. Chatbots use NLPs to by enabling them to understand and respond to user queries and conversations.</p>
                <p style="margin-left: 10px;">These algorithms help chatbots to interpret the nuances of human language, handle variations in phrasing, and provide contextually relevant answers to enhance usability and effectiveness.&nbsp;</p>
            </details>
            <details>
                <summary style="padding: 15px; font-size: 150%; border: 2px solid #A2AAAD;">What is the definition of a LLM and the role it plays in creating chatbots?</summary>
                <p style="margin-left: 10px;">A LLM is an acronym for Large Language Models, an advanced AI models that have been pre-trained on massive amounts of text data from the internet. These models are designed to learn the statistical patterns, grammar, and semantic relationships present in human language.&nbsp;</p>
                <p style="margin-left: 10px;">&nbsp;LLMs serve as the backbone for chatbot systems, providing the underlying language generation capabilities. Chatbots leverage LLMs by fine-tuning them on specific tasks and incorporating prompt engineering techniques to optimize their performance.&nbsp;</p>
            </details>
            <details>
                <summary style="padding: 15px; font-size: 150%; border: 2px solid #A2AAAD;">What are the rule based techniques for creating chatbots?&nbsp;</summary>
                <p style="margin-left: 10px;">Chatbots are computer programs designed to simulate conversations with human users, providing automated responses based on predefined rules or machine learning models.</p>
                <p style="margin-left: 10px;">AI assistants are more advanced systems that utilize natural language processing and machine learning techniques to understand and respond to user queries, offering personalized assistance and performing tasks.&nbsp;</p>
            </details>
            <details>
                <summary style="padding: 15px; font-size: 150%; border: 2px solid #A2AAAD;">What are the three major disadvantages of rule based chatbots?</summary>
                <ol style="list-style-type: decimal;">
                    <li>Rule-based chatbots heavily rely on predefined sets of rules and patterns to generate responses. This means that chatbots may struggle with understanding user intents that deviate from the predefined rules, leading to inaccurate or irrelevant responses.</li>
                    <li>Secondly, rule-based chatbots are limited in their ability to adapt to new or evolving language patterns. Rule-based chatbots may quickly become outdated and fail to keep up with emerging language trends, making their responses seem unnatural or outdated to users.</li>
                    <li>Lastly, rule-based chatbots often lack the capability for advanced reasoning and context understanding. This lack of contextual understanding can result in frustrating and disjointed user experiences.</li>
                </ol>
            </details>
        </div>
    </div>
</div>