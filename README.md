
<img src="img/city_emblem.png" alt="City Logo"/>

# City of Cape Town Data Science Challenge

## Problems

In this repo I have provided solutions for the three tasks relevant to the Data Scientist position.
* 2. Initial Data Transformation - joining the service request data to geospatial hex data.
* 4. Predictive Analytic Tasks Timeseries
* 4. Predictive Analytic Tasks Computer Vision

## Solutions

The resepective solutions are self-contained in Python Notebooks
* `geohex.ipynb`
* `timeseries.ipynb`
* `computer_vision.ipynb`

## Requirements

All requirements are in the `requirements.txt` file.

## Training logs
Tensorboard logs for the computer vision task are included in `lightning_logs/` and can be viewed using tensorboard.

`tensorboard --logdir lightning_logs`

## Git Log
Git was used throughout this project, with apropriate versioning and branching. Here is a copy of the Git Log.


```
commit 7b17a823a47e1be21137436d9da1bcd9cd275529
Author: Claude Formanek <formanekjc@gmail.com>
Date:   Mon Jul 7 11:35:41 2025 +0200

    Added training logs for computer vision.

commit 8fafca23cf13be91b49fd770e6ad6fc01b8c1527
Author: Claude Formanek <formanekjc@gmail.com>
Date:   Mon Jul 7 09:55:59 2025 +0200

    Added better explanations to all 3 solutions. Added README.

commit e2945aa28e317f9fe39710c55f33ac90e314e6dd
Author: Claude Formanek <formanekjc@gmail.com>
Date:   Mon Jul 7 07:57:40 2025 +0200

    Added solution to joining Geo data.

commit 1455ead58c04e00fc340aab0a56df75f389a3cca
Author: Claude Formanek <formanekjc@gmail.com>
Date:   Sun Jul 6 08:50:29 2025 +0200

    Added CV notebook for detecting pools.

commit e54570dd1ef65743f537a3cacda8c62ab5bc7573
Author: Claude Formanek <formanekjc@gmail.com>
Date:   Fri Jul 4 14:54:12 2025 +0200

    Added simple timeseries model using Prophet.

commit b5c036b823ae3480f3a75b19c0b632a4e9c985f7
Author: Claude Formanek <formanekjc@gmail.com>
Date:   Fri Jul 4 11:43:36 2025 +0200

    Created timeseries for each hex by aggregating service requests by week.

commit 303972ac463ac51450a5695d2ae51570e16d6fce
Author: Claude Formanek <formanekjc@gmail.com>
Date:   Fri Jul 4 11:02:45 2025 +0200

    Added ipython notebook for report. Included functionality to load and inspect data.

```