# satisfactory-planner
Contains a JSON database of buildings and parts in Satisfactory, and will use the DB to calculate child part requirements for a target parent part.


## JSON Entry Templates

Use the following as templates for new entries into the JSON database. 

For any given part, only list the immediate children ingredients for that part under ingredients.

### Building

    {
      "name": "",
      "power_draw_mw": "",
      "conveyer_inputs": "",
      "conveyer_outputs": "",
      "pipeline_inputs": "",
      "pipeline_outputs": ""
    },

### Part
    
    {
        "name": "",
        "produced_in": "",
        "qty": ,
        "prod_time_sec": ,
        "prod_per_min": ,
        "ingredients" : [
            {
                "name" : "",
                "req_amount" : 
            },
            {
                "name" : "",
                "req_amount" : 
            },
            {
                "name" : "",
                "req_amount" : 
            },
            {
                "name" : "",
                "req_amount" : 
            }
        ]
    },
    