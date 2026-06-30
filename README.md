graph TD
    %% Objective 1 Path
    A1[Satellite Grids] --> B1[Spatiotemporal Alignment]
    A2[Weather Grids] --> B1
    A3[CPCB Ground Data] --> B1
    B1 --> C1[CNN-LSTM Engine]
    C1 --> D1[Daily Pan-India AQI Maps]

    %% Objective 2 Path
    E1[HCHO & Fire Vector Data] --> F1[Wind Vector Overlay]
    F1 --> G1[Hotspot & Source Maps]
