Workplan (execution summary)

T=0 (now)
- Generate footprints placeholders (done).
- Run generate_footprints.py to create initial .kicad_mod (script included).

T+12h
- Import DXF Top/Bot into PCB (Edge.Cuts/mechanical).
- Place mechanical-critical parts (SFP+, RJ45, USB-C), lock positions.

T+24–48h
- Complete MT7988A fanout pads, LPDDR footprints, M.2 socket footprints.
- Place CPU, DDR, M.2, connectors; apply netclasses and diffpair rules.
- Run ERC/DRC and 3D collision checks.
- Produce final archive and reports.

Deliverables
- KiCad project (.zip), footprints, BOM.csv, placement.csv, scripts, ERC/DRC report, 3D collision report, DFM notes.