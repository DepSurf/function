# Function: <code>compaction_defer_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811b70b0)
Location: mm/compaction.c:166
Inline: True
Inline callers:
  - mm/compaction.c:__compact_pgdat
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff811b70b0-ffffffff811b713d: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811d1cb4)
Location: mm/compaction.c:183
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:__compact_pgdat
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff811d0b50-ffffffff811d0bd6: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e1c49)
Location: mm/compaction.c:183
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff811e0b90-ffffffff811e0c16: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811eba3d)
Location: mm/compaction.c:179
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff811ea890-ffffffff811ea90d: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81201dbc)
Location: mm/compaction.c:180
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81200bf0-ffffffff81200c74: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81223182)
Location: mm/compaction.c:180
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81222010-ffffffff81222094: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812361d5)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81235060-ffffffff812350e4: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812476ab)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff812460d0-ffffffff81246159: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81255b1a)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff812545b0-ffffffff81254639: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81283550)
Location: mm/compaction.c:181
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81283550-ffffffff812835d9: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128d640)
Location: mm/compaction.c:198
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8128d640-ffffffff8128d6a3: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81292c70)
Location: mm/compaction.c:197
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81292c70-ffffffff81292cd3: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d3060)
Location: mm/compaction.c:197
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff812d3060-ffffffff812d30c0: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81331db0)
Location: mm/compaction.c:197
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81331db0-ffffffff81331e56: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a8a40)
Location: mm/compaction.c:192
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff813a8a40-ffffffff813a8ae6: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813dbc00)
Location: mm/compaction.c:191
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff813dbc00-ffffffff813dbca6: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81405b60)
Location: mm/compaction.c:191
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81405b60-ffffffff81405c06: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ed054)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffff8000102eb9d0-ffff8000102eba98: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0510eec)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
c050fa10-c050facc: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003b0c28)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
c0000000003aefe0-c0000000003af0d4: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe000201600)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffe0002004fc-ffffffe000200598: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124e16a)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8124cc00-ffffffff8124cc89: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124110a)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8123fba0-ffffffff8123fc29: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124bf0a)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8124a9a0-ffffffff8124aa29: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void compaction_defer_reset(struct zone *zone, int order, bool alloc_success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8125b837)
Location: mm/compaction.c:181
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8125a210-ffffffff8125a2a9: compaction_defer_reset (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
