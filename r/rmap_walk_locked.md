# Function: <code>rmap_walk_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e9400)
Location: mm/rmap.c:1862
Inline: True
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff811e9400-ffffffff811e9431: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811fa750)
Location: mm/rmap.c:1861
Inline: True
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff811fa750-ffffffff811fa781: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81205430)
Location: mm/rmap.c:1769
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff81205430-ffffffff81205461: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121e3e0)
Location: mm/rmap.c:1854
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff8121e3e0-ffffffff8121e411: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812402a0)
Location: mm/rmap.c:1872
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff812402a0-ffffffff812402d1: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812549a0)
Location: mm/rmap.c:1907
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff812549a0-ffffffff812549d1: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81266c50)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff81266c50-ffffffff81266c81: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81275570)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff81275570-ffffffff812755a1: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a69bc)
Location: mm/rmap.c:1955
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
Direct callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
**Symbols:**

```
ffffffff812a6a60-ffffffff812a6a91: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b1e5c)
Location: mm/rmap.c:1949
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812b1f00-ffffffff812b1f31: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b752c)
Location: mm/rmap.c:1973
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812b75d0-ffffffff812b7601: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f9c9c)
Location: mm/rmap.c:2374
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812f9ce0-ffffffff812f9d11: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rmap_walk_locked(struct folio *folio, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135f5d7)
Location: mm/rmap.c:2511
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff8135ff80-ffffffff8135ffb6: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rmap_walk_locked(struct folio *folio, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813da41f)
Location: mm/rmap.c:2525
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff813daed0-ffffffff813daf06: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rmap_walk_locked(struct folio *folio, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140eb5e)
Location: mm/rmap.c:2523
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff8140f610-ffffffff8140f646: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rmap_walk_locked(struct folio *folio, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8143b51e)
Location: mm/rmap.c:2682
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff8143c020-ffffffff8143c056: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff80001030b4a0)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffff80001030b4a0-ffff80001030b508: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0527924)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
c0527924-c0527968: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003db5f0)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
c0000000003db5f0-c0000000003db648: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000214e56)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffe000214e56-ffffffe000214eb4: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126dbc0)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff8126dbc0-ffffffff8126dbf1: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125fbf0)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff8125fbf0-ffffffff8125fc21: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b960)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff8126b960-ffffffff8126b991: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rmap_walk_locked(struct page *page, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8127b2f0)
Location: mm/rmap.c:1917
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap
  - mm/migrate.c:remove_migration_ptes
```
**Symbols:**

```
ffffffff8127b2f0-ffffffff8127b321: rmap_walk_locked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
