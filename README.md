# CSS `calc()` Issue in Flexbox

This repository demonstrates a common issue with using the `calc()` function in CSS, specifically within flexbox containers.  The `bug.css` file shows the incorrect implementation, resulting in unexpected layout behavior.  The corrected version is provided in `bugSolution.css`.  The problem stems from misunderstanding how `100%` is interpreted within `calc()` when used with flexbox.  Understanding the context of the percentage is critical for accurate calculations.