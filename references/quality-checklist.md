# QA
Inspect the actual generated output where supported. Critical failures: wrong/missing text, unreadable headline, major source subject/landmark loss or distortion, absent image-fill mask, unwanted text. Fix these regardless of score.

Suggested subjective rubric (not a measured model metric): typography integration 25; painterly rendering 20; source fidelity 20; composition 15; color/light 10; spelling/readability 10. Aim for 85/100 with no critical failure. No fabricated scores.

Targeted repair instructions:
- Flat blue title: reveal the same continuous painted scene through all letters; cream outside and within counters.
- Abrupt seam: blend the lower glyphs into the complete landscape with natural occlusion.
- Excessive occlusion: uncover distinguishing glyph strokes without removing the main subject.
- Weak paint: reinforce layered directional impasto, preserving fine landmark/face details.
- Lost scene: restore the original spatial relationships, pose, clothing, and key silhouettes.
- Incorrect copy: specify exact strings, revise only text/layout if supported; otherwise regenerate with explicit strings.
- Bad crop: extend the source naturally; avoid stretching.
- Style drift in batch: compare against closest supplied target; restore shared cream, font proportions, brushwork and hierarchy.
