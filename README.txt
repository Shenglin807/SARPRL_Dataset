(1) The description of request_dataset: 
The name of each dataset includes four parts (spatial distribution of parcels, the number of passenger requests, the number of parcel requests, the index)
For example, "CS(North)_76_24_0" means that the first dataset about "CS(North)", including 76 passenger requests and 24 parcel requests.
The description of the columns in the request dataset:
    "tpep_pickup_datetime": the submission time of the request.
    "PULocationID": the request origin taxi zone.
    "DOLocationID": the request destination taxi zone.
    "type_code": 1- passenger request; 0 - parcel request.
    "time": the submission time of the request (convert to minute).
    "length": the travel distance between origin and destination.

(2) The description of road_network_data: 
"taxi_zone_map_manhattan":  Taxi zone map - Manhattan
"taxi_zones_node_pairs": The correspondence between taxi zones and road network nodes
"edge": Information of the road network edges.
"node": Information of the road network nodes.
"adjacency_matrix_edge_no": Adjacency Matrix of Manhattan Road Network.

