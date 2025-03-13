# Moana Pay-Per-Area Pricing Model

## Overview

This document outlines the Pay-Per-Area pricing model for Moana's geospatial data platform, specializing in providing geospatial data for the Pacific Islands region. The model scales pricing based on area size, data type, and resolution quality.

All pricing in Fijian Dollars (FJD)

## Supported Data Types

- **Vector Data**: Shapefiles and MapInfo format
- **Raster Data**: GeoTIFFs
- **Point Cloud Data**: Airplane and Aerodrone LiDAR (.las and .laz files)

## Pricing Framework

### 1. Area-Based Tiers

| Coverage Area | Price Per km² | Volume Discount |
|---------------|---------------|----------------|
| Small (1-10 km²) | $X | Standard Rate |
| Medium (11-100 km²) | $X - 10% | 10% Discount |
| Large (101-1000 km²) | $X - 20% | 20% Discount |
| Enterprise (1000+ km²) | $X - 30% | 30% Discount |

### 2. Data Type Multipliers

| Data Type | Price Multiplier | Rationale |
|-----------|------------------|-----------|
| Vector Data | 1.0× | Baseline pricing |
| Raster Data | 1.2-1.5× | Varies by resolution and complexity |
| LiDAR Point Cloud | 2.0-3.0× | Higher due to data size and processing requirements |

### 3. Resolution/Quality Factors

| Quality Level | Multiplier | Description |
|---------------|------------|-------------|
| Standard | 1.0× | Basic resolution suitable for general analysis |
| High | 1.5× | Enhanced resolution for detailed mapping |
| Premium | 2.0× | Highest available resolution for specialized applications |

## Pricing Formula

```
Final Price = Base Rate × Area Size × Data Type Multiplier × Resolution Factor
```

### Example Calculation

For a 50 km² area of high-resolution LiDAR data:
- Base Rate: $X - 10% (Medium tier)
- Area: 50 km²
- Data Type: LiDAR (2.5× multiplier)
- Resolution: High (1.5× multiplier)
- Final Price: ($X - 10%) × 50 × 2.5 × 1.5

## Additional Considerations

### Regional Factors

- Remote island coverage may include accessibility premiums
- Multi-island packages offer discounted rates for contiguous coverage

### Custom Processing

- Additional fees may apply for custom processing requirements
- Specialized formats or projections available upon request

## Review Schedule

Pricing structure to be reviewed quarterly to ensure competitiveness and alignment with data acquisition costs.
