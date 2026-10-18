# The Oracle Pain-Spot Library: Course Content Summary

The Oracle Pain-Spot Library is a unified catalog of six Oracle courses from the *Elegantly Solving Impressed Pain Spots You've Encountered Once* series on guestart.github.io. The courses are aimed at beginner and intermediate Oracle DBAs. According to the course pages, the author is a Senior Oracle DBA with 12+ years of experience and Oracle ACE Alumni status.

**Totals:** 76 lessons (20 free, 56 paid). Buying all six courses costs $56.

Each lesson is delivered in four formats: video (`.mp4`), slide deck (`.pdf`), infographic (`.png`), and a podcast app (`.html` + `.m4a`), packaged as one WinRAR `.zip` per lesson. Free lessons link directly to all four formats on the source sites. Paid lessons are sold per course on Gumroad. The companion page `index.html` lists all 76 lessons with filters.

Topic summaries are based on each course's published outline and description; lesson titles are reproduced as published.

## Course Overview

| # | Course | Lessons | Free | Paid | Price |
|---|---|:-:|:-:|:-:|:-:|
| 1 | [Oracle SQL Development](https://guestart.github.io/ESIPSYvEOAOSDlb1erb/) | 17 | 5 | 12 | $12 |
| 2 | [Oracle Performance and Tuning](https://guestart.github.io/ESIPSYvEOAOPaTlb1erb/) | 12 | 4 | 8 | $8 |
| 3 | [Oracle-Specific Features](https://guestart.github.io/ESIPSYvEOAO-SFlb1erb/) | 11 | 2 | 9 | $9 |
| 4 | [Oracle Diagnostics and DevOps](https://guestart.github.io/ESIPSYvEOAODaDOlb7erb/) | 7 | 2 | 5 | $5 |
| 5 | [Oracle Database Design and Modeling](https://guestart.github.io/ESIPSYvEOAODDaMlb1erb/) | 16 | 4 | 12 | $12 |
| 6 | [Oracle Application Development](https://guestart.github.io/ESIPSYvEOAOADlb1erb/) | 13 | 3 | 10 | $10 |
| | **Total** | **76** | **20** | **56** | **$56** |

## Course Summaries

### 1. Oracle SQL Development (17 lessons, 5 free, $12)

- Source: https://guestart.github.io/ESIPSYvEOAOSDlb1erb/
- Buy paid lessons: https://quanwenzhao.gumroad.com/l/ESIPSYvEOAOSDlb1erb

**Focus:** SQL that returns unstable or wrong results, or performs poorly. Topics include ROWNUM and Top-N pitfalls, legacy join syntax and Cartesian products, join fan-out (ORA-30926), CHAR and legacy data types, implicit conversions, function-based indexes, CTE sorting, hierarchical queries, and modern replacements for legacy constructs (FETCH FIRST, virtual columns, recursive CTEs).

| No. | Lesson | Access |
|---|---|---|
| 01 | Why Legacy Oracle SQL Joins Crash Databases? | Free |
| 02 | Why Oracle ROWNUM Greater Than One Returns Zero? | Paid |
| 03 | Replace ROWNUM With FETCH_FIRST For Speed! | Paid |
| 04 | Why Oracle SQL Top-N Queries Fail? | Free |
| 05 | Why Your SQL Results Keep Shifting? | Paid |
| 06 | Why CHAR Columns Kill Oracle Performance? | Paid |
| 07 | The Risks of Legacy Oracle Database Types! | Paid |
| 08 | Two Missing Quotes Crash Oracle Databases! | Free |
| 09 | Replace Database Triggers With Virtual Columns! | Paid |
| 10 | Why Databases Ignore Your Function-Based Index? | Paid |
| 11 | Avoiding Cartesian Chaos In Oracle SQL! | Paid |
| 12 | Fixing Oracle CTE Sorts With INLINE! | Free |
| 13 | Fixing ORA-30926 Join Key Fan-Out! | Paid |
| 14 | Why Order By Destroys Oracle Hierarchies? | Paid |
| 15 | Replace Oracle MODEL With Recursive CTEs! | Paid |
| 16 | Fixing Oracle LAST_VALUE With Inverse Sorts! | Paid |
| 17 | Faster Oracle Hierarchical Queries With START WITH! | Free |

### 2. Oracle Performance and Tuning (12 lessons, 4 free, $8)

- Source: https://guestart.github.io/ESIPSYvEOAOPaTlb1erb/
- Buy paid lessons: https://quanwenzhao.gumroad.com/l/ESIPSYvEOAOPaTlb1erb

**Focus:** reading execution plans critically and fixing index design. Topics include explain plans versus actual runtime statistics (A-Time), access versus filter predicates, optimizer cost and behavior, hard-coded hints, the DML cost of indexes, duplicate and invisible indexes, index rebuilds, ignored indexes, and column order in composite indexes.

| No. | Lesson | Access |
|---|---|---|
| 01 | The Oracle Explain Plan illusion! | Free |
| 02 | The Hidden DML Tax of Indexes! | Paid |
| 03 | Why Your Oracle Optimizer Is Lying? | Paid |
| 04 | Oracle Access versus Filter Predicates! | Free |
| 05 | Why Oracle A-Time Numbers Are Deceiving? | Paid |
| 06 | Why Oracle Optimizer Cost Is Total Fantasy? | Paid |
| 07 | Why Hard-Coded SQL Hints Fail? | Paid |
| 08 | How Duplicate Indexes Kill Oracle Performance? | Free |
| 09 | Stop Database Crashes With Invisible Indexes! | Paid |
| 10 | Why Index Rebuilding Ruins Database Performance? | Paid |
| 11 | Why Your Database Ignores Your Indexes? | Paid |
| 12 | Put Equality Columns First In Oracle Indexes! | Free |

### 3. Oracle-Specific Features (11 lessons, 2 free, $9)

- Source: https://guestart.github.io/ESIPSYvEOAO-SFlb1erb/
- Buy paid lessons: https://quanwenzhao.gumroad.com/l/ESIPSYvEOAO-SFlb1erb

**Focus:** materialized views (MVs) and virtual columns. Topics include MV log metadata mismatches, the commit overhead of MVs, force versus fast refresh, silent corruption after Data Pump restores and function changes, materialized views that Oracle ignores, ORA-54013, virtual columns and triggers, mislabeled DETERMINISTIC functions, and indexed virtual columns.

| No. | Lesson | Access |
|---|---|---|
| 01 | Fix Oracle MV Log Metadata Mismatches! | Free |
| 02 | Eliminating Materialized View Commit Tax! | Paid |
| 03 | Why Oracle Force Refresh Kills Performance? | Paid |
| 04 | Oracle Fast Refresh 1200 To 45 Seconds! | Paid |
| 05 | Silent Corruption After Data Pump Restores! | Paid |
| 06 | Why Oracle Ignores Your Materialized Views? | Free |
| 07 | Oracle Function Changes Cause Silent Corruption! | Paid |
| 08 | Solving ORA-54013 And Virtual Column Performance! | Paid |
| 09 | Oracle Virtual Column Before Trigger Failures! | Paid |
| 10 | How Mislabeled DETERMINISTIC Functions Corrupt Indexes? | Paid |
| 11 | Index Virtual Columns For 200x Faster Queries! | Paid |

### 4. Oracle Diagnostics and DevOps (7 lessons, 2 free, $5)

- Source: https://guestart.github.io/ESIPSYvEOAODaDOlb7erb/
- Buy paid lessons: https://quanwenzhao.gumroad.com/l/ESIPSYvEOAODaDOlb7erb

**Focus:** space management and online operations on live systems. Topics include shrinking high-water marks, LOB growth, the cost of online redefinition, zero-downtime redefinition of large tables, row movement that breaks applications, SET UNUSED leaving data exposed, and ORA-08106 blocking online bitmap index rebuilds.

| No. | Lesson | Access |
|---|---|---|
| 01 | Shrinking Oracle High Water Marks! | Free |
| 02 | Why Oracle Tables Lie About LOB Growth? | Paid |
| 03 | The Hidden Cost of Online Redefinition! | Paid |
| 04 | Redefining Massive Oracle Tables With Zero Downtime! | Paid |
| 05 | Why Oracle Row Movement Breaks Applications? | Paid |
| 06 | Oracle SET UNUSED Leaves Data Exposed! | Paid |
| 07 | Why ORA-08106 Blocks Online Bitmap Rebuilds? | Free |

### 5. Oracle Database Design and Modeling (16 lessons, 4 free, $12)

- Source: https://guestart.github.io/ESIPSYvEOAODDaMlb1erb/
- Buy paid lessons: https://quanwenzhao.gumroad.com/l/ESIPSYvEOAODDaMlb1erb

**Focus:** schema design and partitioning decisions. Topics include the bitmap index paradox, preserving historical data, fact table performance, star schemas, data drift, surrogate versus natural keys, unique NULL handling, indexing foreign keys, ROWID as a primary key, mixing CHAR and VARCHAR2, partition pruning (TRUNC and load-date partitioning), global index maintenance, the "power of two" myth, and when not to partition small tables.

| No. | Lesson | Access |
|---|---|---|
| 01 | The Oracle Bitmap Index Paradox! | Free |
| 02 | Why Databases Secretly Destroy Historical Truth? | Paid |
| 03 | Preventing Oracle Fact Table Performance Collapse! | Paid |
| 04 | Eliminate Data Drift With Virtual Columns! | Paid |
| 05 | Why Star Schemas Fix Slow Dashboards? | Paid |
| 06 | Why Surrogate Keys Beat Natural Keys? | Free |
| 07 | Enforcing Unique NULLs With Oracle NVL! | Paid |
| 08 | How Unindexed Foreign Keys Freeze Oracle? | Paid |
| 09 | The Oracle ROWID Primary Key Trap! | Paid |
| 10 | Mixing CHAR and VARCHAR2 Kills Oracle Performance! | Paid |
| 11 | Why TRUNC Breaks Oracle Partition Pruning? | Free |
| 12 | The Oracle Load Date Partitioning Trap! | Paid |
| 13 | Update Global Indexes Prevents Oracle Outages! | Paid |
| 14 | The Oracle Power Of Two Myth! | Paid |
| 15 | Why Partitioned Tables Still Need Indexes? | Paid |
| 16 | Stop Partitioning Small Oracle Tables! | Free |

### 6. Oracle Application Development (13 lessons, 3 free, $10)

- Source: https://guestart.github.io/ESIPSYvEOAOADlb1erb/
- Buy paid lessons: https://quanwenzhao.gumroad.com/l/ESIPSYvEOAOADlb1erb

**Focus:** transactions, locking, and sequences in application code. Topics include why Oracle does not need NOLOCK hints (MVCC), the ORA-00060 ghost lock trap, table locks and SELECT FOR UPDATE, DDL implicit commits and statement-level rollback, JDBC auto-commit, silent errors that create ghost data, identity column drift, CURRVAL with connection pools, and sequence traps (million-ID, NOCACHE, cycling).

| No. | Lesson | Access |
|---|---|---|
| 01 | Why Oracle Never Needs NOLOCK Hints? | Free |
| 02 | The Oracle ORA-00060 Ghost Lock Trap! | Paid |
| 03 | Escaping The Table Lock Trap! | Paid |
| 04 | SELECT FOR UPDATE Kills Oracle Performance! | Paid |
| 05 | Why Oracle DDL Breaks Your Rollbacks? | Free |
| 06 | The Oracle Statement Level Rollback Trap! | Paid |
| 07 | Why JDBC Auto-commit Is A Trap? | Paid |
| 08 | Why Silent Database Errors Create Ghost Data? | Paid |
| 09 | Fixing Oracle Identity Column Drift! | Free |
| 10 | Why Connection Pools Break CURRVAL? | Paid |
| 11 | The Oracle Sequence Million ID Trap! | Paid |
| 12 | Oracle NOCACHE Sequences Are a Compliance Placebo! | Paid |
| 13 | The Danger of Oracle Sequence Cycling! | Paid |
