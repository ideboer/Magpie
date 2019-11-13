How does it respond to:

    My mother and I talked last night.
    ->  It says "Tell me more about your family"

    I said no!
    -> It says "Why so negative"

    The weather is nice.
    -> It says "Do you really think so?"

    Do you know my brother?
    -> It says "Why so negative?"

Keyword -> Response
Yes -> I'm glad you think so!
Hello -> How are you today?
Supercalifragilisticexpialidocious -> Congrats! You discovered it.

What happens when more than one keyword appears in a string? Consider the string "My mother has a dog but no cat." Explain how to prioritize in the reply method.
    When more than one keyword appears in a string, the first keyword checked for in the getResponse method is the one that is replied to. In this case, "no" is the first keywprd which is checked for, so the response is "Why so negative?". To prioritize responses, simply check for the keyword you want to prioritize first.

1. What happend when a keyword is included in another word? Consider statements like "I know all the state capitals" and "I like vegetables smothered in cheese." Explain the problem with the responses to these statements.
    When a keyword is in another word, the response still is based on the keyword. This is a problem because the chatbot should not reply to w keyword within another word, because it likely does not relate to what the user said.
