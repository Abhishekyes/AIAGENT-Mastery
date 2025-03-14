1. api KEY
2. free now :
GO TO https://smith.langchain.com/o/8e83c559-e9c6-5300-b54f-fa41d2bb6328/' - >  SETTINGS - > API key
3. Give any project name 
4. tracing feature v2 please add
5. Invoke is needed for Langsmit see its basic chatbot
6. Metadata and feedback is also there
7.#Provide temp to form enitire prompt
        prompt=ChatPromptTemplate.from_messages(
            [
                ("system","You are an expert sales person.who sell wape(electric sigrate). Provide me answer based on the question"),
                ("user","{input}")

            ]
        )
        prompt

8.1.1 working all prompt+LLM
8.1.2 chain=prompt|llm|output_parser
8.1.3 json format+ query (chain=prompt|llm|output_parser)


### Check output parser in Langchain
 link:https://python.langchain.com/docs/introduction/:  read 4-5 pages and understand

### Langchain Document loader 
    link :https://python.langchain.com/v0.1/docs/modules/data_connection/document_loaders/
    Langcchain integration any file load use any cloud etc ...... Just look at once

### Text splitter etc 
    Main Docs  :: == >>https://python.langchain.com/v0.1/docs/integrations/platforms/


















 # Author : Abhishek
 # EMAIL : vvabhi2776@gmail.com
