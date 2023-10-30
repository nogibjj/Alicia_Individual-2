# Alicia_Week8_Individual_2
## Project Summary: Using Rust to do Data Extraction, Transformation, Loading (ETL) and Querying Tool

The goal of this project is to do ETL on a gun dataset with the Commend tool kit created by Rut language and query it with SQLite database and apply CRUD process on data.

## Youtube Video Link 


### Components:

1. **Data Extraction:**
   - The `extract` function downloads data from a specified URL and saves it to a local file.

2. **Data Transformation and Loading:**
   - The `transform_load` function reads a CSV dataset and inserts its records into a SQLite database after performing necessary table operations. It creates a table named `ServeTimesDB` with specific columns.

3. **Database Querying:**
   - The `query` function allows users to perform SELECT, INSERT, UPDATE, and DELETE operations on the database. It logs the queries into a Markdown file named `query_log.md`.

4. **Logging:**
   - The `log_query` function appends SQL queries to a log file, facilitating tracking and analysis of executed queries.

### Preparation and Dependency Installation: 
1. open codespaces 
2. wait for codespaces to be built 
3. build: `cargo build` for dependencies installation
4. extract: `cargo run extract`
5. transform and load: `cargo run transform_load`
6. query sample: you can use `make create`, `make read`, `make update`, or `make delete` to see sample CRUD Operations
7. query your own: `cargo run query <insert own query here>`

### Check Format and Test Errors: 
1. Format code `make format`
2. Lint code `make lint`
3. Test coce `make test`

### Optimized Rust Binary
1. You can find and download the uploaded artifact by going to `actions` and clicking on the latest workflow run


## References
* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
* https://github.com/nogibjj/rust-data-engineering
* https://docs.rs/sqlite/latest/sqlite/
* https://github.com/fivethirtyeight/data
