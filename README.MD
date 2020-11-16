User requirements:
- As a user I want to create nodes with various types
- As a user I want to get notifications about nodes to receive
- As a user I don't want to wait too long while the tree will be retrieved
- As a user I want to protect by a password the whole tree a certain branch
- As a user I want to have various node types: binary, wish, text, link, 
- As a user I want to be able import XMind schemas

Technical decisions:
- Store files directly in the disk
- Use Graph database to represent relationships between nodes
- Use Elastic Search to be able use full text search



