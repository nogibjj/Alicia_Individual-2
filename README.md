# Alicia_Week8_Individual_2
## Project Summary: Using Rust to do Data Extraction, Transformation, Loading (ETL) and Querying Tool

The goal of this project is to do ETL on a gun dataset with the Commend tool kit created by Rut language and query it with SQLite database and apply CRUD process on data.

## Youtube Video Link 


### Components:

1. **Data Extraction:**
   - The `extract` exact dataset from website.

2. **Data Transformation and Loading:**
   - The `transform_load` read the CSV file and create a table ini SQLite.

3. **CRUD**
   - The `query` performs CREATE, INSERT, UPDATE, and DELETE queries on the database. 

4. **Log**
   - The `log_query` logs the queries into a markdown file.

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
