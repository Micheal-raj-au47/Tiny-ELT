# Tiny-ELT
Use SQL to create a schema with 4 tables: stores, store_states, train, and test in sqlite.
Inner join stores and store_states to add state information to the store information. Call the resulting table stores_with_state(look up the syntax for saving the results of a join to a table). Why does this make sense as an inner join?
Left join train and test tables individually with the stores_with_state table to create train_stores and test_stores. Why does this join need to be a left join from the perspective of predicting sales on the test set?
Transfer these two tables to duckdb. Save duckdb database files as well as parquet files
Compute grouby statistics on sales amounts on store-ids, day of week, and their combination.Save this last analytics as a table in the database and as a parquet file. You can do these calculations either on the database files or the parquet files.
