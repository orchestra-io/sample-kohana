# Kohana PHP Framework, version 3.2 

## Running on Orchestra

Kohana will run on Orchestra easily with 2 minor changes to the bootstrap file. The first is to change the cache_dir to use the system temp directory with `sys_get_temp_dir()`. You will also need to decide what to do with application logging. You can either use `sys_get_temp_dir()` again, or use an external logging service.
