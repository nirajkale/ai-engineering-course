# Syllabus for AI Engineering

## Python
### Basics
- Loops, IF, String formatting
- Working with dates (datetime package)
- Python native types:
    - lists
    - tuples
    - dicts
    - sets
    - understanding of when to use which
- functions
    - defining functions, return values, default arguments, *args and **kwargs.
    - type hints for functions using native python types
    - mutable vs immutable values
- standard python functions/ concepts: 
    - enumerate, zip, format
    - array slicing
    - try-except-finally
- OOP concepts:
    - classes, constructors
    - staticmethod, classmethod
    - dataclasses 
    - abstract classes (ABC)

### Package Manager: UV
Learn how to setup a uv project, add dependancies, export deps etc

## API Devlopment
An AI engineer should be able to write, test, containerize & deploy RESTFul APIs for a project.

### API Development concepts
- FastAPI - Hello world
- Schema Design:
    - Learn how to define Pydantic schemas
    - Use standard validation rules in Pydantic (MinLength, MaxLength etc)
    - How to write custom validation rules on a schema
- Request, Responses
    - HTTP methods: GET, PUT, DELETE, POST, PATCH & which to use when
    - path parameters, query parameters, and a JSON body
    - making endpoints `async`
- Adding simple API Key using `Depends`
- Learn FastAPI lifespan hook
- Special endpoints for:
    - file upload
    - file download
    - an endpoint that returns a streaming reponse
- pytest for endoints (keep this short)
- ORM
    - What are ORMs & why to use them?
    - SQLAlchemy 2.0 with FastAPI
    - define table/Model
    - creating & running migrations
    - altering existing Models/Schemas & running migrations
    - use ORM in existing endpoint
- running API with uvicorn
- Containerize API for deployment with docker
- run with docker



