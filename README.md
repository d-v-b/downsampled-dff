# downsampled-dff
Estimating the baseline fluorescence for normalizing fluorescence timeseries can take a long time, especially if the data are sampled at a high rate. If we assume the baseline changes slowly, then we can speed up baseline estimation by smoothing and downsampling the timeseries before estimating the baseline. This notebook demonstrates such an approach.
