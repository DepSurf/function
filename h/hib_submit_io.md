# Function: <code>hib_submit_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hib_submit_io(int rw, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d2920)
Location: kernel/power/swap.c:253
Inline: False
Direct callers:
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:swap_read_page
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
```
**Symbols:**

```
ffffffff810d2920-ffffffff810d2a2e: hib_submit_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d7680)
Location: kernel/power/swap.c:264
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swap_read_page
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810d7680-ffffffff810d77d7: hib_submit_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810de1f0)
Location: kernel/power/swap.c:264
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swap_read_page
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810de1f0-ffffffff810de30b: hib_submit_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810dd2e0)
Location: kernel/power/swap.c:264
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810dd2e0-ffffffff810dd3fb: hib_submit_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e5530)
Location: kernel/power/swap.c:265
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810e5530-ffffffff810e566e: hib_submit_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:265
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810eda50-ffffffff810edb73: hib_submit_io (STB_LOCAL)
ffffffff810ef51b-ffffffff810ef53d: hib_submit_io.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:265
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810f90c0-ffffffff810f91ea: hib_submit_io (STB_LOCAL)
ffffffff810fabab-ffffffff810fabcd: hib_submit_io.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:263
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff811017b0-ffffffff811018d5: hib_submit_io (STB_LOCAL)
ffffffff81103254-ffffffff81103278: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:263
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff8110dbe0-ffffffff8110dd05: hib_submit_io (STB_LOCAL)
ffffffff8110f6a4-ffffffff8110f6c8: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:263
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:mark_swapfiles
  - kernel/power/swap.c:mark_swapfiles
```
**Symbols:**

```
ffffffff81118c00-ffffffff81118d25: hib_submit_io (STB_LOCAL)
ffffffff8111a8f6-ffffffff8111a91a: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:270
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:mark_swapfiles
  - kernel/power/swap.c:mark_swapfiles
```
**Symbols:**

```
ffffffff811146d0-ffffffff811147f8: hib_submit_io (STB_LOCAL)
ffffffff81bdffea-ffffffff81be000e: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:270
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:mark_swapfiles
  - kernel/power/swap.c:mark_swapfiles
```
**Symbols:**

```
ffffffff81114e90-ffffffff81114faf: hib_submit_io (STB_LOCAL)
ffffffff81bd1ff7-ffffffff81bd201b: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:270
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:mark_swapfiles
  - kernel/power/swap.c:mark_swapfiles
```
**Symbols:**

```
ffffffff81134f30-ffffffff8113504f: hib_submit_io (STB_LOCAL)
ffffffff81caacaa-ffffffff81caacce: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:272
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:mark_swapfiles
  - kernel/power/swap.c:mark_swapfiles
```
**Symbols:**

```
ffffffff811571e0-ffffffff811572e2: hib_submit_io (STB_LOCAL)
ffffffff81e5b0e0-ffffffff81e5b102: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hib_submit_io(blk_opf_t opf, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81187f20)
Location: kernel/power/swap.c:272
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:mark_swapfiles
  - kernel/power/swap.c:mark_swapfiles
```
**Symbols:**

```
ffffffff81187f20-ffffffff81188045: hib_submit_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hib_submit_io(blk_opf_t opf, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811990b0)
Location: kernel/power/swap.c:272
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:mark_swapfiles
  - kernel/power/swap.c:mark_swapfiles
```
**Symbols:**

```
ffffffff811990b0-ffffffff811991d5: hib_submit_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hib_submit_io(blk_opf_t opf, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811a8110)
Location: kernel/power/swap.c:272
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:mark_swapfiles
  - kernel/power/swap.c:mark_swapfiles
```
**Symbols:**

```
ffffffff811a8110-ffffffff811a823a: hib_submit_io (STB_LOCAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (c03c0bbc)
Location: kernel/power/swap.c:263
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
c03c0bbc-c03c0d00: hib_submit_io (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:324
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff81105e10-ffffffff81105f53: hib_submit_io (STB_LOCAL)
ffffffff81107b85-ffffffff81107ba8: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:263
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff810f70a0-ffffffff810f71c5: hib_submit_io (STB_LOCAL)
ffffffff810f8b64-ffffffff810f8b88: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:263
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff811040b0-ffffffff811041d5: hib_submit_io (STB_LOCAL)
ffffffff81105b74-ffffffff81105b98: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void *addr, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:263
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_unmark
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:write_page
```
**Symbols:**

```
ffffffff8110f4a0-ffffffff8110f5c5: hib_submit_io (STB_LOCAL)
ffffffff81110f54-ffffffff81110f78: hib_submit_io.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, page_off, addr, hb</code> ➡️ <code>op, op_flags, page_off, addr, hb</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, op_flags, page_off, addr, hb</code> ➡️ <code>opf, page_off, addr, hb</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
