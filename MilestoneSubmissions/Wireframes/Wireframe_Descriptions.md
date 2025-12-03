# Wireframe Descriptions & ASCII Art

Since we are unable to upload new image files at this moment, this document provides detailed ASCII art wireframes for the key pages of the **Asteroid Detector 3000** application.

## 1. Main Dashboard (Threat List)

**Purpose:** The landing page where users see the most relevant asteroid data immediately.

```text
+---------------------------------------------------------------+
| [Logo] Asteroid Detector 3000    [Home] [History] [Fun Facts] |
|                                  [Search...] [Login]          |
+---------------------------------------------------------------+
|                                                               |
|   NEXT BIG APPROACH: APOPHIS in 120d 04h 20m                  |
|   [ REFRESH DATA ]                                            |
|                                                               |
+---------------------------------------------------------------+
| Filter: [Time Period v]   [x] High Threat Only                |
+---------------------------------------------------------------+
|                                                               |
| +---------------------+  +---------------------+              |
| | Name: 2023 DW       |  | Name: Bennu         |              |
| | Threat: [YELLOW]    |  | Threat: [RED]       |              |
| | Date: 2046-02-14    |  | Date: 2182-09-24    |              |
| | Dist: 1.2M km       |  | Dist: 500k km       |              |
| | Size: 50m           |  | Size: 490m          |              |
| | [ VIEW DETAILS ]    |  | [ VIEW DETAILS ]    |              |
| +---------------------+  +---------------------+              |
|                                                               |
| +---------------------+  +---------------------+              |
| | Name: 1999 RQ36     |  | Name: 2000 SG344    |              |
| | Threat: [GREEN]     |  | Threat: [GREEN]     |              |
| | ...                 |  | ...                 |              |
| +---------------------+  +---------------------+              |
|                                                               |
+---------------------------------------------------------------+
| (c) 2025 Woodwinds | Powered by NASA NEO API                  |
+---------------------------------------------------------------+
```

## 2. Asteroid Detail Page

**Purpose:** To display comprehensive data about a specific selected asteroid.

```text
+---------------------------------------------------------------+
| [Logo] Asteroid Detector 3000    [Home] [History] [Fun Facts] |
+---------------------------------------------------------------+
|  < Back to Dashboard                                          |
|                                                               |
|  ASTEROID: BENNU                                              |
|  "Potentially Hazardous"                                      |
|                                                               |
|  [ IMAGE OF ASTEROID ]                                        |
|                                                               |
+---------------------------------------------------------------+
|  STATS:                                                       |
|  +-------------------+  +-------------------+                 |
|  | Velocity          |  | Diameter          |                 |
|  | 28,000 km/h       |  | 490 meters        |                 |
|  | (Fast!)           |  | (= Empire State)  |                 |
|  +-------------------+  +-------------------+                 |
|  +-------------------+  +-------------------+                 |
|  | Impact Prob.      |  | Miss Distance     |                 |
|  | 0.037%            |  | 500,000 km        |                 |
|  +-------------------+  +-------------------+                 |
+---------------------------------------------------------------+
|  TRAJECTORY:                                                  |
|  [ . . . . . O . . . . . . . . . . . . . ]                    |
|  [ . . . . . . . . . . . . . . . . . . . ]                    |
|  [ . . . . . . . . . + . . . . . . . . . ]                    |
|  (Graph showing Earth (+) and Asteroid path)                  |
+---------------------------------------------------------------+
|  DID YOU KNOW?                                                |
|  Bennu is older than the solar system itself!                 |
+---------------------------------------------------------------+
```

## 3. Historical Data View

**Purpose:** To allow users to look back at past close approaches.

```text
+---------------------------------------------------------------+
| [Logo] Asteroid Detector 3000    [Home] [History] [Fun Facts] |
+---------------------------------------------------------------+
|  HISTORICAL DATA ARCHIVE                                      |
|                                                               |
|  Select Era:  [1900] ----o---------------- [2025]             |
|                                                               |
+---------------------------------------------------------------+
|  CLOSE APPROACHES PER DECADE                                  |
|  |                                                            |
|  |       [##]                                                 |
|  |  [##] [##]      [##]                                       |
|  |  [##] [##] [##] [##]                                       |
|  +-----------------------                                     |
|    1990  2000 2010 2020                                       |
+---------------------------------------------------------------+
|  PAST ENCOUNTERS:                                             |
|  -----------------------------------------------------------  |
|  | Date       | Name       | Miss Dist. | Size     |        |
|  |------------|------------|------------|----------|        |
|  | 2013-02-15 | Chelyabinsk| 29,000 km  | 20m      |        |
|  | 1908-06-30 | Tunguska   | 0 km       | 50m      |        |
|  | 2020-08-16 | 2020 QG    | 2,950 km   | 3m       |        |
|  -----------------------------------------------------------  |
+---------------------------------------------------------------+
```
