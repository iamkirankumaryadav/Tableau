# Tableau

### `Terms`

`Row` | `Observation` 

`Column` | `Field`

### `Dimensions`  
- `Qualitative` values like `Names`, `Dates`, `Category` or `Geographical` Data.
-  `Dimension` values never change.
-  `Dimensions` are used to `categorize`, `segment`, and `reveal` the details in your data.
-  `Dimensions` affect the `level` of detail in the view. 
-  `Dimensions` are `independent` variables.

### `Measures`  
- `Quantitative` values like `Quantity`, `Currency`, `Profit` or `Revenue`
- `Measure` values changes on the basis of dimension selected or any filters applied.
- `Measures` can be `aggregated`
- `Tableau` applies an `aggregation` to the measure by default.
-  `Measures` are `dependent` variables.

### `Green (Continuous) vs Blue (Discrete)`
- `Discrete Dimension` or `Continuous Measure` are `most` common.
- `Continuous Dimension` or `Discrete Measure` are `less` common.
- `Green` measures and dimensions are `continuous`
- `Blue` measures and dimensions are `discrete`
- `Continuous` field values are treated as an `infinite`
- `Continuous` fields add `axes` to the view.
- `Discrete` values are treated as `finite` 
- `Discrete` fields add `headers` to the view.

### `Data types`
![Data Type](Image/DataType.png)

### `Features`
- Speed.
- User friendly.
- Beautiful and interactive dashboard.
- Direct connection.
- Easy publishing and sharing.
- Available for both `Windows` and `MacOS`

### `Live` vs `Extract`

`Live` 
- Connected to real time or live current data.
- Connected to server or big data.
- `Icon` : Single cylinder.

`Extract` 
- Takes a snapshot ( subset or entire dataset ) of data.
- `Static` data which do not requires any refresh or real time connection with server.
- `Icon` : Dual Cylinder.

### `Evaluate`

- Verify that `Tableau` has correctly assigned data types, and they can make changes on the `Data Source` page if it is wrong.
- They can also rename misspelled fields, split the field value in separate field.
- Any changes made in Tableau are not written to native data source (Original data).
- Changes are instead stored as `metadata` in a Tableau file called a Tableau Data Source `.tds`
