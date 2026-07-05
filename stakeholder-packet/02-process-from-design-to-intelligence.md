# The Process From Design To Intelligence

The process starts with the design state and ends with usable intelligence. The key is to preserve source context at every step.

## 1. Start From The Design Environment

Vectorworks remains the spatial and design authority. It owns project geometry, layers, classes, records, sheets, symbols, plant records, and design context.

Graftkit does not replace Vectorworks. It reads from it, organizes the evidence, and prepares reviewed information that can later return through approved writeback paths.

## 2. Extract Every Useful Representation

A project is not understood from one export alone. The system gathers multiple views of the same design state:

- VWX metadata and live document context;
- IFC exports;
- DWG/DXF geometry;
- PDFs and sheet images;
- worksheets and schedules;
- plant and resource records;
- rendered views and presentation assets;
- cost and financial files.

Each format shows something different. The system compares them instead of trusting one file blindly.

## 3. Build Evidence Packages

Extracted facts are stored with source references:

- source file;
- page, layer, class, sheet, or worksheet;
- object or row identity;
- extraction method;
- timestamp;
- content hash;
- receipt.

This gives the team a way to review, reproduce, and correct the evidence.

## 4. Normalize The Evidence

The system turns raw evidence into consistent project concepts:

- projects;
- sites;
- design objects;
- plant assets;
- hardscape assets;
- quantities;
- materials;
- cost items;
- CSI classifications;
- IFC candidates;
- approval events.

The original source names are preserved. Graftkit adds stable identity and downstream meaning.

## 5. Serve Review Surfaces

Different users need different views:

- technical BIM/GIS review;
- cinematic 3D presentation;
- plant library review;
- financial model review;
- data quality review;
- stakeholder proof documents.

These surfaces consume the same governed evidence instead of each inventing its own truth.

## 6. Approve And Write Forward

After review gates pass, approved enrichments can be written forward:

- into reports and dashboards;
- into IFC/BIM validation packages;
- into budget and forecasting models;
- into client-facing presentation surfaces;
- eventually back toward Vectorworks through controlled MCP/IFC writeback.

Writeback is not casual. It requires validation, approval, and receipts.

## Simple Flow

Design state -> export and harvest -> evidence package -> normalized model -> review surfaces -> approved outputs -> controlled writeback.
