# fzdoc
A Simple API doc server based on YAML format

## YAML example for API doc
```yaml
project: "Project Name"
version: "0.1.1"
author: "Mingcai SHEN <archsh@gmail.com>"
release: ""
categories:
    - name: ""
      discription: ""
      apis:
        - name: ""
          path: ""
          method: "GET|PUT|POST|DELETE"
          params:
            - key: ""
              type: ""
              comment: ""
              required: true
              examples: ""
          queries:
            - key: ""
              type: ""
              comment: ""
              required: true
              examples: ""
          body:
            format: "json|xml|yaml|form|raw"
            json: 
            xml: 
            yaml: 
            form: 
            raw: 
          response:
            format: "json|xml|yaml|form|raw"
        - name: ""

```