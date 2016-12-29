# json-ld-redux

Use JSON-LD as a context provider for redux action. [RFC]

# Background

As we know, redux actions are json, with a type, which is human readable.  
But what if we introduce json-ld to it, making human readable action also computer understandable? Then we can use actions easily cross project, easily parse by some agent to provide some statistic.

