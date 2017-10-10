# d:swarm scripts

a collection of useful commandline scripts for working with d:swarm

 * [generate_dswarm_projects_overviews.sh](generate_dswarm_projects_overviews.sh): generates various d:swarm projects overviews (i.e. different serializations (CSV, JSON, line-delimited JSON)) from d:swarm projects in a folder that have been exported with help of the [d:swarm tools](https://github.com/dswarm/dswarm-tools) (requires [jq](https://stedolan.github.io/jq/) and [json2csv](https://github.com/jehiah/json2csv))
   * following fields are available:
     * _uuid_: project identifier
     * _name_: Project name
     * _input_data_model_uuid_: input data model identifier
     * _input_data_model_name_: input data model name
     * _input_schema_uuid_: input schema identifier
     * _input_schema_name_: input schema name
     * _output_data_model_uuid_: output data model identifier
     * _output_data_model_name_: output data model name
     * _output_schema_uuid_: output schema identifier
     * _output_schema_name_: output schema name
     * _mappings_count_: number of the mappings that are contained in the project
     * _mappings_: names of the mappings that are contained in the project

