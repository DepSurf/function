# Function: <code>__swap_count</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __swap_count(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81229990)
Location: mm/swapfile.c:1331
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81229990-ffffffff812299b8: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __swap_count(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124ac50)
Location: mm/swapfile.c:1331
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8124ac50-ffffffff8124ac78: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __swap_count(struct swap_info_struct *si, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125f280)
Location: mm/swapfile.c:1348
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8125f280-ffffffff8125f2a5: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81279f30)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81279f30-ffffffff81279f6d: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81289a10)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81289a10-ffffffff81289a4d: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1485
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff812c006f-ffffffff812c0093: __swap_count.cold (STB_LOCAL)
ffffffff812bc8a0-ffffffff812bc90a: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1503
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81be8790-ffffffff81be87b5: __swap_count.cold (STB_LOCAL)
ffffffff812c83b0-ffffffff812c8435: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1502
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81bda787-ffffffff81bda7ac: __swap_count.cold (STB_LOCAL)
ffffffff812ced60-ffffffff812cede5: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813142f0)
Location: mm/swapfile.c:1471
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff813142f0-ffffffff8131435f: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137f790)
Location: mm/swapfile.c:1454
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8137f790-ffffffff8137f814: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fe2e0)
Location: mm/swapfile.c:1434
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff813fe2e0-ffffffff813fe364: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff814312c0)
Location: mm/swapfile.c:1440
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff814312c0-ffffffff8143132b: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146a6e0)
Location: mm/swapfile.c:1440
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8146a6e0-ffffffff8146a74b: __swap_count (STB_GLOBAL)
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
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010324898)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffff800010324898-ffff8000103248ec: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053c4c8)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
c053c4c8-c053c500: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fa8b0)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
c0000000003fa8b0-c0000000003fa928: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000224fee)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffe000224fee-ffffffe000225036: __swap_count (STB_GLOBAL)
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
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81281ff0)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81281ff0-ffffffff8128202d: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81273b10)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81273b10-ffffffff81273b4d: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127fe00)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff8127fe00-ffffffff8127fe3d: __swap_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __swap_count(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128fad0)
Location: mm/swapfile.c:1448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff8128fad0-ffffffff8128fb16: __swap_count (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct swap_info_struct *si</code>
</li>
<li>
<b>Param reordered. </b>
<code>si, entry</code> ➡️ <code>entry</code>
</li>
</ul>
</details>
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
