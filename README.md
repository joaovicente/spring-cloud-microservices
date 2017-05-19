# spring-cloud-microservices
A microservices example using Spring Cloud

<!--
@startuml
:Client:
[sentence-stats]
[word-count]
[char-count]
:Client: -.> [sentence-stats] : GET /sentence-stats/{sentence}?w=true&c=true
[sentence-stats] -.> [word-count] : GET /word-count/{sentence}
[sentence-stats] -.> [char-count] : GET /char-count/{sentence}
@enduml
-->

![alternative text](http://www.plantuml.com/plantuml/png/itBEoKpDAx7YYYu6KgbvoQcwnIM99SMnND7b-KKfkidvfNabG4voHc8HZ6C5rQEWgskdWAvFmKh1tJL4GHzLMByQng-rBxSjAIfDLKi6KnZsGWn5iXjc8488oJ0Ssf5S2zEE44BI3W00)
