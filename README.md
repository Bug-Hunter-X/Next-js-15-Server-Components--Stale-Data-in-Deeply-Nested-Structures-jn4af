# Next.js 15 Server Component Data Race Condition

This repository demonstrates a potential issue in Next.js 15's server components when dealing with deeply nested asynchronous data fetching operations.  The bug showcases how asynchronous calls may lead to stale data being used in rendering, causing inconsistencies.

The `serverComponentBug.js` file contains the problematic code.  `serverComponentSolution.js` illustrates a solution to handle data fetching efficiently and avoid race conditions.