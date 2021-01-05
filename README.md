# Large CSV to JSON Stream Example

This example project shows how you can take the process of downloading a 1.59GB CSV file, transform the content to JSON, and return the content, all using end to end streaming.

### Running the Project

Download the project, import into Anypoint Studio, and run. To test, either browse to `http://localhost:8081/large-csv-test` or run the following terminal command:

```bash
curl http://localhost:8081/large-csv-test
```

You should immediately start seeing transformed JSON objects despite the fact that the 1.59GB file is still beingi downloaded.
