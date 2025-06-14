sequenceDiagram
    participant Sat as Satellite/Data Provider
    participant Bay as Data Distributor (Bayanat AI)
    participant Acad as Academic Partner (KU)
    participant Tech as Technical Team (From KU)
    participant Field as Archaeological Field Team (Under Dubai Culture & ARTS Authority)
    participant Culture as Dubai Culture & ARTS Authority
    Sat->>Bay: Acquire multispectral & SAR imagery
    Bay->>Acad: Deliver imagery data for Saruq Al-Hadid Archaeological Site
    note over Acad: Reference previous excavation reports
    rect rgb(235, 245, 255)
    note over Acad: Sandbox (Data Processing & Model Development)
    Acad->>Acad: Preprocessing (Calibration, Filtering, Geocoding)
    Acad->>Acad: Image Processing (PCA, Spectral Indices)
    Acad->>Acad: Geospatial Analysis (DEM, Slope Maps, GIS Data)
    Acad->>Acad: Machine Learning (CNNs, Clustering)
    Acad->>Acad: Train & fine-tune models
    Acad->>Acad: Compare with previous excavation data
    end
    Acad->>Tech: Provide predicted excavation targets
    Tech->>Field: Collaborate on-site validation
    note over Field: KU performs validation using geophysical techniques
    Field->>Culture: Validate predictions & plan excavations
    Culture->>Acad: Provide feedback for model refinement
    Acad->>Acad: Fine-tune model with new field and geophysical data
