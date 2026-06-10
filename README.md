# CodePath AI301 Open Source Capstone — Kelly Olmos

## Why I Chose This Issue

I chose issue #839 "Performance: N+1 query problem in equipment category 
filtering" because it aligns with my Python experience and my goal to 
improve my backend database optimization skills. The issue is labeled 
"good first issue" and has a clear suggested fix in the description.

I'm interested in this because:
1. I've worked extensively with Python in my Applied Mathematics coursework 
   at Harvard, so I'm comfortable with the language
2. The fix is scoped to one function in one file — contained and realistic 
   for a first contribution
3. The maintainer actively labeled it `good first issue`, indicating they 
   are reviewing PRs in this area
4. I want to learn how Django handles database query optimization using 
   prefetch_related and ORM patterns

From reading the issue, I understand the current problem is that equipment 
categories are filtered in a Python loop that fires a separate database 
query on each iteration — causing N+1 queries that slow down page load. 
My contribution will optimize this to a single prefetched query, improving 
performance for all users of the equipment assignment page.

Left a comment on the issue introducing myself and I now await the maintainer's response. 
