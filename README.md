# Function-calling-and-data-extraction-with-LLMs

[Complete](https://learn.deeplearning.ai/accomplishments/9c365db4-2d82-4c79-8022-ad22ce29df26?usp=sharing)

Developer of AI-based conversational interface designed for security tools. The company's platform attempts to synthesize data from various security knowledge sources and tap into existing security tools via APIs by leveraging open-source large language models that operate behind a customer's firewall or in the cloud, enabling enterprises to control the security software and get metrics and insights using natural language commands.

Function calling can refer to a feature in large language models (LLMs) or a programming concept:
LLMs
Function calling in LLMs allows them to choose the correct function to run from a set of options, as well as the parameters to pass to that function. This can help LLMs integrate with external systems, perform complex operations, and provide more accurate responses. For example, Google's Gemini API uses function calling to analyze function declarations and a query to determine how to use an API in response to a request. Function calling can be used to generate a single text response or support a chat session.
Programming
Function calling in programming is when a program is instructed to run a specific block of code that has been defined elsewhere. This can help make code more organized, reusable, and easier to understand. In Microsoft Learn, a function call is an expression that passes control and arguments to a function.

Function calling in OpenAI is a model feature that allows users to describe functions and their arguments in prompts using JSON. Instead of invoking the function itself, the model returns a JSON output that describes which functions should be called and what arguments to use. This feature is especially relevant for large language models (LLMs) because it allows AI models to interact with and execute external functions, going beyond basic text generation and language understanding. 

To use function calling, users need to create a custom function that includes the following information:

-- Name: The Python function name

-- Description: The function's functionality

-- Parameters: The name, type, and description of the arguments 

Function calling can help resolve issues with inconsistent and unpredictable text outputs, and it can be especially useful for working with large amounts of data.
