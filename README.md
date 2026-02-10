# GraphRag

A project for building and querying knowledge graphs using LangChain, LLMs, and Neo4j.

## Overview

GraphRag demonstrates how to extract structured knowledge graphs from unstructured text using large language models (LLMs) and then query them using natural language through Cypher queries.

## Features

- **Text-to-Graph Conversion**: Transform natural language text into structured knowledge graphs with nodes and relationships
- **LLM-Powered Extraction**: Use GPT-4o to intelligently extract entities and relationships from documents
- **Graph Database Integration**: Store and manage knowledge graphs in Neo4j
- **Natural Language Querying**: Ask questions in plain English and get answers from the knowledge graph
- **Cypher Query Generation**: Automatically generate Cypher queries from natural language questions

## Tech Stack

- **LangChain**: Framework for building with language models
- **Neo4j**: Graph database for storing and querying knowledge graphs
- **OpenAI GPT-4o**: LLM for knowledge extraction and question answering
- **Python 3.13+**: Core programming language

## Getting Started

### Prerequisites

- Python 3.13 or higher
- Neo4j database instance
- OpenAI API key (for GPT-4o access)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/aayushmaanhooda/GraphRag.git
cd GraphRag
