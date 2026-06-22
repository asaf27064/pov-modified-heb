# gears_baseline

Clean (unpatched) copies of the upstream Gears files we overlay Hebrew code onto, for the version in BASELINE_VERSION.txt. The auto-update Action diffs new upstream against these (upstream prunes old zips, so we can't fetch them anymore).

When the overlay is re-patched for a new Gears version, refresh these files from that clean version and update BASELINE_VERSION.txt.
