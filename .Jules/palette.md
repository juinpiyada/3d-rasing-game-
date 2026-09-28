## 2026-09-28 - [WebGL Focus Management]
**Learning:** In WebGL/Canvas games, UI overlays like 'Game Over' screens can strand keyboard users because focus remains on the document body or canvas, making interactable elements inaccessible via immediate keyboard navigation.
**Action:** Always auto-focus primary action buttons (like 'Try Again' or 'Continue') when game-over or menu overlays appear, and blur them upon dismissal to prevent accidental re-triggering.
