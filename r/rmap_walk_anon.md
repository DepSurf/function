# Function: <code>rmap_walk_anon</code>

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
In mm/rmap.c (ffffffff811cc077)
Location: mm/rmap.c:1579
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
int rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e6d50)
Location: mm/rmap.c:1755
Inline: False
```
**Symbols:**

```
ffffffff811e6d50-ffffffff811e6fb4: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f80f0)
Location: mm/rmap.c:1754
Inline: False
```
**Symbols:**

```
ffffffff811f80f0-ffffffff811f8354: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203620)
Location: mm/rmap.c:1664
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff81203620-ffffffff81203876: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121c170)
Location: mm/rmap.c:1749
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff8121c170-ffffffff8121c3d4: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123dd50)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff8123dd50-ffffffff8123dfae: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812522d0)
Location: mm/rmap.c:1802
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff812522d0-ffffffff81252535: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81264470)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff81264470-ffffffff812646c3: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81272ce0)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff81272ce0-ffffffff81272f33: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a3af0)
Location: mm/rmap.c:1850
Inline: False
Direct callers:
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812a3af0-ffffffff812a3d56: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812af5d0)
Location: mm/rmap.c:1844
Inline: False
Direct callers:
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812af5d0-ffffffff812af836: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b4d40)
Location: mm/rmap.c:1866
Inline: False
Direct callers:
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812b4d40-ffffffff812b4fce: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f66a0)
Location: mm/rmap.c:2267
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
```
**Symbols:**

```
ffffffff812f66a0-ffffffff812f690a: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rmap_walk_anon(struct folio *folio, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2399
Inline: False
Direct callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
```
**Symbols:**

```
ffffffff8135b700-ffffffff8135ba95: rmap_walk_anon (STB_LOCAL)
ffffffff81e6e944-ffffffff81e6e959: rmap_walk_anon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rmap_walk_anon(struct folio *folio, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2413
Inline: False
Direct callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
```
**Symbols:**

```
ffffffff813d6410-ffffffff813d6744: rmap_walk_anon (STB_LOCAL)
ffffffff82064814-ffffffff82064829: rmap_walk_anon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rmap_walk_anon(struct folio *folio, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2411
Inline: False
Direct callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
```
**Symbols:**

```
ffffffff8140b4e0-ffffffff8140b6be: rmap_walk_anon (STB_LOCAL)
ffffffff820e3f39-ffffffff820e3f4d: rmap_walk_anon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rmap_walk_anon(struct folio *folio, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2569
Inline: False
Direct callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
```
**Symbols:**

```
ffffffff81437df0-ffffffff81437fa6: rmap_walk_anon (STB_LOCAL)
ffffffff821c0b67-ffffffff821c0b7b: rmap_walk_anon.cold (STB_LOCAL)
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
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff800010308860)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffff800010308860-ffff800010308a80: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0525748)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
c0525748-c05258b4: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d7b60)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
c0000000003d7b60-c0000000003d7eb4: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe0002131da)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffe0002131da-ffffffe000213332: rmap_walk_anon (STB_LOCAL)
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
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b330)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff8126b330-ffffffff8126b583: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125d5d0)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff8125d5d0-ffffffff8125d823: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812690d0)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff812690d0-ffffffff81269323: rmap_walk_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rmap_walk_anon(struct page *page, struct rmap_walk_control *rwc, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81278c10)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
```
**Symbols:**

```
ffffffff81278c10-ffffffff81278e54: rmap_walk_anon (STB_LOCAL)
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
