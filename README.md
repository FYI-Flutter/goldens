A repository for golden image files that are used by tests in https://github.com/flutter/flutter.

See: https://github.com/flutter/flutter/wiki/Writing-a-golden-file-test-for-package%3Aflutter

PLEASE READ THAT WIKI PAGE BEFORE CONTRIBUTING TO THIS REPOSITORY.

IT CONTAINS RULES THAT YOU MUST FOLLOW.

## Getting diffs for golden images

If you have ImageMagick and you want to use it to show diffs of files
in this repo, add the following to your `~/.gitconfig`:

```
[diff "image"]
    command = /path/to/this/repo/diff-images.sh
```

## Obsolete files

To make it easier to land multiple PRs that change the goldens in
parallel, when we change the result of a test, rather than just
updating the golden file, we change the name of the golden file
used in the test, so that after the change we use a different
image than before the change.

This section lists the files that can now be deleted because
they have been replaced in this way:

- packages/flutter/test/material/floating_action_button_test.clip.1.png
- packages/flutter/test/widgets/text_golden.Strut.1.png
- packages/flutter/test/widgets/text_golden.Strut.2.png
- packages/flutter/test/widgets/text_golden.Strut.3.png
- packages/flutter/test/widgets/text_golden.Strut.4.png
- packages/flutter/test/widgets/text_golden.StrutForce.1.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.0.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.1.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.2.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.3.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.4.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.5.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.6.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.7.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.1.0.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.1.1.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.1.2.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.1.3.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.1.4.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.1.5.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.1.6.png
- packages/flutter/test/material/bottom_navigation_bar.shifting_transition.1.7.png
