# Function: <code>__dec_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811adae0)
Location: mm/vmstat.c:302
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_replace_page
  - mm/swap_state.c:__delete_from_swap_cache
```
**Symbols:**

```
ffffffff811adae0-ffffffff811adb17: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6da0)
Location: mm/vmstat.c:379
Inline: False
```
**Symbols:**

```
ffffffff811c6da0-ffffffff811c6dd5: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6ec0)
Location: mm/vmstat.c:379
Inline: False
```
**Symbols:**

```
ffffffff811d6ec0-ffffffff811d6ef5: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfd20)
Location: mm/vmstat.c:379
Inline: False
```
**Symbols:**

```
ffffffff811dfd20-ffffffff811dfd55: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5b30)
Location: mm/vmstat.c:454
Inline: False
```
**Symbols:**

```
ffffffff811f5b30-ffffffff811f5b65: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216db0)
Location: mm/vmstat.c:454
Inline: False
```
**Symbols:**

```
ffffffff81216db0-ffffffff81216de5: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229cc0)
Location: mm/vmstat.c:454
Inline: False
```
**Symbols:**

```
ffffffff81229cc0-ffffffff81229cf5: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81239950)
Location: mm/vmstat.c:455
Inline: False
```
**Symbols:**

```
ffffffff81239950-ffffffff81239985: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247c50)
Location: mm/vmstat.c:455
Inline: False
```
**Symbols:**

```
ffffffff81247c50-ffffffff81247c85: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81274e10)
Location: mm/vmstat.c:455
Inline: False
```
**Symbols:**

```
ffffffff81274e10-ffffffff81274e96: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127f670)
Location: mm/vmstat.c:464
Inline: False
```
**Symbols:**

```
ffffffff8127f670-ffffffff8127f6f6: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812847e0)
Location: mm/vmstat.c:470
Inline: False
```
**Symbols:**

```
ffffffff812847e0-ffffffff81284866: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c3750)
Location: mm/vmstat.c:516
Inline: False
```
**Symbols:**

```
ffffffff812c3750-ffffffff812c3853: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81320b30)
Location: mm/vmstat.c:545
Inline: False
```
**Symbols:**

```
ffffffff81320b30-ffffffff81320c54: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394a00)
Location: mm/vmstat.c:532
Inline: False
```
**Symbols:**

```
ffffffff81394a00-ffffffff81394b24: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c6780)
Location: mm/vmstat.c:533
Inline: False
```
**Symbols:**

```
ffffffff813c6780-ffffffff813c68a4: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1cc0)
Location: mm/vmstat.c:532
Inline: False
```
**Symbols:**

```
ffffffff813f1cc0-ffffffff813f1de4: __dec_zone_page_state (STB_GLOBAL)
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
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dc340)
Location: mm/vmstat.c:455
Inline: False
```
**Symbols:**

```
ffff8000102dc340-ffff8000102dc398: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0502310)
Location: mm/vmstat.c:455
Inline: True
Inline callers:
  - mm/vmstat.c:dec_zone_page_state
```
**Symbols:**

```
c05022c4-c05022f4: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039c04c)
Location: mm/vmstat.c:455
Inline: True
Inline callers:
  - mm/vmstat.c:dec_zone_page_state
```
**Symbols:**

```
c00000000039bfe0-c00000000039c018: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f549a)
Location: mm/vmstat.c:455
Inline: True
Inline callers:
  - mm/vmstat.c:dec_zone_page_state
```
**Symbols:**

```
ffffffe0001f5432-ffffffe0001f547a: __dec_zone_page_state (STB_GLOBAL)
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
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812402a0)
Location: mm/vmstat.c:455
Inline: False
```
**Symbols:**

```
ffffffff812402a0-ffffffff812402d5: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812332a0)
Location: mm/vmstat.c:455
Inline: False
```
**Symbols:**

```
ffffffff812332a0-ffffffff812332d5: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123e040)
Location: mm/vmstat.c:455
Inline: False
```
**Symbols:**

```
ffffffff8123e040-ffffffff8123e075: __dec_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dec_zone_page_state(struct page *page, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d770)
Location: mm/vmstat.c:455
Inline: False
```
**Symbols:**

```
ffffffff8124d770-ffffffff8124d7a5: __dec_zone_page_state (STB_GLOBAL)
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
