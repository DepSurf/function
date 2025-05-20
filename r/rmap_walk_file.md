# Function: <code>rmap_walk_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cbf59)
Location: mm/rmap.c:1623
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e6af0)
Location: mm/rmap.c:1808
Inline: False
```
**Symbols:**

```
ffffffff811e6af0-ffffffff811e6d4c: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f7e90)
Location: mm/rmap.c:1807
Inline: False
```
**Symbols:**

```
ffffffff811f7e90-ffffffff811f80ec: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812033e0)
Location: mm/rmap.c:1716
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff812033e0-ffffffff81203619: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121bf20)
Location: mm/rmap.c:1801
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff8121bf20-ffffffff8121c164: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123dfb0)
Location: mm/rmap.c:1819
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff8123dfb0-ffffffff8123e1e4: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81252540)
Location: mm/rmap.c:1854
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff81252540-ffffffff8125277b: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812646d0)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff812646d0-ffffffff81264904: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81272f40)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff81272f40-ffffffff81273174: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a3f70)
Location: mm/rmap.c:1902
Inline: False
Direct callers:
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812a3f70-ffffffff812a41a4: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812af840)
Location: mm/rmap.c:1896
Inline: False
Direct callers:
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812af840-ffffffff812afa74: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b4ac0)
Location: mm/rmap.c:1919
Inline: False
Direct callers:
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812b4ac0-ffffffff812b4d3d: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f6910)
Location: mm/rmap.c:2320
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812f6910-ffffffff812f6b6a: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rmap_walk_file(struct folio *folio, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2447
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
```
**Symbols:**

```
ffffffff8135baa0-ffffffff8135be48: rmap_walk_file (STB_LOCAL)
ffffffff81e6e959-ffffffff81e6e96d: rmap_walk_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rmap_walk_file(struct folio *folio, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2461
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
```
**Symbols:**

```
ffffffff813d6760-ffffffff813d6ab3: rmap_walk_file (STB_LOCAL)
ffffffff82064829-ffffffff8206483d: rmap_walk_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rmap_walk_file(struct folio *folio, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2459
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
```
**Symbols:**

```
ffffffff8140b6d0-ffffffff8140b8a0: rmap_walk_file (STB_LOCAL)
ffffffff820e3f4d-ffffffff820e3f61: rmap_walk_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rmap_walk_file(struct folio *folio, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2618
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
```
**Symbols:**

```
ffffffff81437fc0-ffffffff81438153: rmap_walk_file (STB_LOCAL)
ffffffff821c0b7b-ffffffff821c0b8f: rmap_walk_file.cold (STB_LOCAL)
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
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff800010308c90)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffff800010308c90-ffff800010308ec8: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c05258b4)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
c05258b4-c05259dc: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d7ec0)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
c0000000003d7ec0-c0000000003d8210: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000213382)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffe000213382-ffffffe0002134d0: rmap_walk_file (STB_LOCAL)
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
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b590)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff8126b590-ffffffff8126b7c4: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125d830)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff8125d830-ffffffff8125da64: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81269330)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff81269330-ffffffff81269564: rmap_walk_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rmap_walk_file(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81278e60)
Location: mm/rmap.c:1864
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff81278e60-ffffffff81279093: rmap_walk_file (STB_LOCAL)
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
