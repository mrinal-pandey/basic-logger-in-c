# basic-logger-in-c
A basic logger written for C

To use the logger
1. Clone the repository
2. Add it to your project
3. Change the `log_file_path` to point to the location where you want your log file, relative to home directory

You're good to go!

<h3>Log tags</h3>

The logger has three type of tags
<ul>
<li>ERROR_TAG</li>
<li>WARNING_TAG</li>
<li>INFO_TAG</li>
</ul>

<h3>Log functions</h3>

The three functions available are
<ul>
<li>init_logger()</li>
<li>logger(char* TAG, char* MESSAGE)</li>
<li>cleanup_logger()</li>
</ul>
