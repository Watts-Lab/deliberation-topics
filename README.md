# Deliberation Topics
This repository describes the tools, data, and analysis to locate a set of deliberation topics into a multidimensional parameter space describing the topics.

## Repository structure:
- **topics:** Collection of deliberation topics, each folder containing:
  - **{topic}.md**: markdown to be displayed as a discussion topic to experiment participants
  - **README.md**: documentation and metadata about the topic
  - *NOTE: Comments are not supported in {topic}.md files. Any background information should be included in the README.md.*
- **mapper:** Infrastructure for measuring topic properties
- **data:** Raw measurements from the mapper tool and from external survey data
- **map:** Statistical models and topic location predictions
