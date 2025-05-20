# Function: <code>__inc_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ada40)
Location: mm/vmstat.c:280
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/swap_state.c:__add_to_swap_cache
```
**Symbols:**

```
ffffffff811ada40-ffffffff811ada77: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6c70)
Location: mm/vmstat.c:335
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff811c6c70-ffffffff811c6ca5: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6d90)
Location: mm/vmstat.c:335
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff811d6d90-ffffffff811d6dc5: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfbf0)
Location: mm/vmstat.c:335
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff811dfbf0-ffffffff811dfc25: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5a00)
Location: mm/vmstat.c:410
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff811f5a00-ffffffff811f5a35: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216c80)
Location: mm/vmstat.c:410
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81216c80-ffffffff81216cb5: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229b90)
Location: mm/vmstat.c:410
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81229b90-ffffffff81229bc5: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81239820)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81239820-ffffffff81239855: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247b20)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81247b20-ffffffff81247b55: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81275410)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81275410-ffffffff81275492: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127fcc0)
Location: mm/vmstat.c:418
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff8127fcc0-ffffffff8127fd42: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284e00)
Location: mm/vmstat.c:424
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81284e00-ffffffff81284e85: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c2cf0)
Location: mm/vmstat.c:456
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff812c2cf0-ffffffff812c2df1: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8131ff10)
Location: mm/vmstat.c:485
Inline: False
```
**Symbols:**

```
ffffffff8131ff10-ffffffff81320032: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81393a80)
Location: mm/vmstat.c:476
Inline: False
```
**Symbols:**

```
ffffffff81393a80-ffffffff81393ba2: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c7500)
Location: mm/vmstat.c:477
Inline: False
```
**Symbols:**

```
ffffffff813c7500-ffffffff813c7622: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1190)
Location: mm/vmstat.c:476
Inline: False
```
**Symbols:**

```
ffffffff813f1190-ffffffff813f12b2: __inc_zone_page_state (STB_GLOBAL)
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
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dc0f0)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffff8000102dc0f0-ffff8000102dc148: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0502084)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
c0502084-c05020b4: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039bce0)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
c00000000039bce0-c00000000039bd18: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f5176)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffe0001f5176-ffffffe0001f51be: __inc_zone_page_state (STB_GLOBAL)
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
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81240170)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81240170-ffffffff812401a5: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81233170)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81233170-ffffffff812331a5: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123df10)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff8123df10-ffffffff8123df45: __inc_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __inc_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d640)
Location: mm/vmstat.c:411
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff8124d640-ffffffff8124d675: __inc_zone_page_state (STB_GLOBAL)
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
