Group Members: Min Paing, Anthony Velikov

1) I choose Within a Github action that runs whenever code is pushed 

Integrating automated tests within a GitHub Action that runs on every code push make sure continuous integration and early bug detection. This approach prevents broken code from being merged into the main branch by automatically validating new changes especially when working with multiple contributors, and allows developers to identify and fix issues immediately rather than waiting until the end of the development cycle.


3) Navigation mode runs a full page load: it clears the cache, loads the page from scratch, and measures metrics. It’s best for assessing performance as users first arrive, while Snapshot mode takes a snapshot of the page in its current state without reloading or recording network activity. It’s ideal for catching static issues.

4) a) Optimize Images
Large JPEG and PNG files slow down load times. Serve properly sized, compressed images to save up to 617 KiB.

b) Minimize Main-Thread Work (≈5.0 s)
Reduce the time spent parsing, compiling, and executing JavaScript. Deliver smaller JS payloads to speed up the main thread.
c) Reduce JavaScript Execution Time
Cut down on script evaluation and parsing by code-splitting, tree-shaking unused code, and deferring non-critical scripts. This will lower your Total Blocking Time.


