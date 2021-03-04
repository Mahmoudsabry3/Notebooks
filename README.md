


## Data
- Taxi Data
    - NYC, Washington DC, Porto, Chicago, Boston
    - processed data is in './data/taxi'
- Bike Data
    - NYC, Washington DC, Chicago
    - processed data is in './data/bike'
- Environment PH Data
    - Midwest, Northeast, Pacific, South, Southwest, West
    - processed data is in './data/environment'

## Usage

Please check the data and scripts/preprocessing, training and testing for more details.

First, construct folders named models, outputs, test_data

### Data Preprocessing
This part is used to generate the sequential data for training.
```
python preprocess.py --filename=/A/B.npz --cluster_file=/cluster/A/cluster_B --save_filename=B_seq.npz
```
A can be replaced by the task (taxi, bike, environment), B can be replaced by the city (e.g., nyc, dc)


