# Projet : modem multi-access

Résumé
- Projet KiCad 8 couches pour modem/routeur multi-access basé sur MediaTek MT7988A.
- Fonctionnalités : PCIe Gen4, NVMe (M.2 Key M 2280), M.2 5G (Quectel RM502Q), M.2 Wi‑Fi, SFP+ (10G), RJ45 (2.5G MagJack), USB‑C, nano‑SIM + eSIM, LPDDR4X, backdrill DDR & PCIe.
- Matériau RF : Rogers RO4350B; Cuivre : 1 oz outer / 1 oz inner.
- Board size cible : 148 × 100 mm.
- Convention d'axes : coin bas‑gauche = (0,0), X → droite, Y → haut.

Contenu fourni
- KiCad project skeleton (.kicad_pro, .kicad_sch placeholders, .kicad_pcb skeleton)
- footprints/ (kicad_mod placeholders pour composants prioritaires)
- stackup.md, netclasses.csv, .kicad_dru
- BOM.csv, placement.csv
- scripts: generate_footprints.py, export_bom.sh
- Reports: ERC_DRC_Report.txt, 3D_Collision_Report.txt, DFM_notes.txt

Prochaine étape
- Ouvrir le projet dans KiCad 8, générer les footprints finaux (script generate_footprints.py peut aider), importer DXF (BPI-R4Pro-V10_DXF_TOP.dxf / _BOT.dxf) dans Edge.Cuts et Mechanical, remplacer placeholders .kicad_mod par footprints réels, exécuter ERC/DRC.