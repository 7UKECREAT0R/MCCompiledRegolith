```
NOTE:  THIS FILTER DOESN'T WORK WITH REGOLITH 0.0.11 OR UNDER!
```

### [Main Page](https://github.com/7UKECREAT0R/MCCompiled) - [Source Code](https://github.com/7UKECREAT0R/MCCompiledSource)
This repository serves as a filter for the [Regolith](https://bedrock-oss.github.io/regolith/) compiler

### Installation
1. Go to your Regolith project and run `regolith install github.com/7UKECREAT0R/MCCompiledRegolith/mc-compiled`
2. Add it to your project config like any other filter under the name `mc-compiled`!
3. u done

### config.json
Example of how your run profile should look with the MCCompiled filter installed:
```json
    "profiles": {
      "dev": {
        "export": {
          "readOnly": false,
          "target": "development"
        },
        "filters": [
          {
            "filter": "mc-compiled"
          }
        ]
      }
    }
```
