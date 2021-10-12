# SkylineR34-FiveM-Ready
The long awaited r34 and converted for fivem since no one wants to be nice and share this here you go! make sure to change vehicle sounds if you dont have the new r34sound. will probably release vehicle sound pack as well. Enjoy everyone..

Step 1. Remove all files out of resource lua folder so that only stream is in a folder 

Step 2. Create __resource.lua text file in the main folder so only stream has a folder delete old resource lua folder, then copy and paste the code below starting from resource manifest down to the last data_file.

Step 3. Enjoy :)


resource_manifest_version '77731fab-63ca-442c-a67b-abc70f28dfa5'
 
files {
    'vehicles.meta',
    'carvariations.meta',
    'carcols.meta',
    'handling.meta',
    'vehiclelayouts.meta',
}

data_file 'HANDLING_FILE' 'handling.meta'
data_file 'VEHICLE_METADATA_FILE' 'vehicles.meta'
data_file 'CARCOLS_FILE' 'carcols.meta'
data_file 'VEHICLE_VARIATION_FILE' 'carvariations.meta'
data_file 'VEHICLE_LAYOUTS_FILE' 'vehiclelayouts.meta'
