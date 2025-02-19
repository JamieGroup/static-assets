Structured Outputs
==================

[Nov 4, 2024](https://jmatthews.uk/blog/structured-outputs/)

—

by

[jamie](https://jmatthews.uk/blog/author/jamie/)

in [Projects](https://jmatthews.uk/blog/category/projects/)

A Structured Output is a way of interacting with a large language model while ensuring that its output conforms to a specific format that you can then use in your applications.

This is achieved by creating a JSON file which contains the information about the properties you require the LLM to output.

To make this process more flexible, I’ve created a Java implementation of the most useful commands, it’s available on Github, [here](https://github.com/JamieM0/structured-outputs)
.

To use it, simply create a Structure object and add in your required properties, you can then choose to restrict the response to conform _exactly_ to your structure, or allow it to add its own properties.

For example, you can require that the LLM output a specific value, like the confidence level in its response. This can then be used to either disregard its response entirely, or use it for the originally intended purpose.

To learn more about the OpenAI implementation of Structured Outputs, click [here](https://platform.openai.com/docs/guides/structured-outputs/json-mode)
.

* * *

Comments
--------

### Leave a Reply [Cancel reply](https://jmatthews.uk/blog/structured-outputs/#respond)

Your email address will not be published. Required fields are marked \*

Comment \*

Name \* 

Email \* 

Website 

 Save my name, email, and website in this browser for the next time I comment.