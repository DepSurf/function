# Function: <code>alloc_migration_target</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *alloc_migration_target(struct page *page, long unsigned int private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ed360)
Location: mm/migrate.c:1579
Inline: False
```
**Symbols:**

```
ffffffff812ed360-ffffffff812ed4b3: alloc_migration_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *alloc_migration_target(struct page *page, long unsigned int private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f3700)
Location: mm/migrate.c:1561
Inline: False
```
**Symbols:**

```
ffffffff812f3700-ffffffff812f3853: alloc_migration_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *alloc_migration_target(struct page *page, long unsigned int private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1605
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_demote_page
```
**Symbols:**

```
ffffffff81cc2536-ffffffff81cc254f: alloc_migration_target.cold (STB_LOCAL)
ffffffff8133dc50-ffffffff8133de27: alloc_migration_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *alloc_migration_target(struct page *page, long unsigned int private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1538
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_demote_page
```
**Symbols:**

```
ffffffff81e74b31-ffffffff81e74b4a: alloc_migration_target.cold (STB_LOCAL)
ffffffff813b1640-ffffffff813b18d3: alloc_migration_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *alloc_migration_target(struct page *page, long unsigned int private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1645
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_demote_page
  - mm/vmscan.c:alloc_demote_page
```
**Symbols:**

```
ffffffff820679e9-ffffffff82067a02: alloc_migration_target.cold (STB_LOCAL)
ffffffff814329b0-ffffffff81432bc2: alloc_migration_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct folio *alloc_migration_target(struct folio *src, long unsigned int private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1979
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_demote_folio
  - mm/vmscan.c:alloc_demote_folio
```
**Symbols:**

```
ffffffff820e72dd-ffffffff820e72f8: alloc_migration_target.cold (STB_LOCAL)
ffffffff81467360-ffffffff8146752d: alloc_migration_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct folio *alloc_migration_target(struct folio *src, long unsigned int private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:2003
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_demote_folio
  - mm/vmscan.c:alloc_demote_folio
```
**Symbols:**

```
ffffffff821c3eb8-ffffffff821c3ed0: alloc_migration_target.cold (STB_LOCAL)
ffffffff814965a0-ffffffff81496772: alloc_migration_target (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *src</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct folio *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
