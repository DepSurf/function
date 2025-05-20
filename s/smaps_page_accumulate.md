# Function: <code>smaps_page_accumulate</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81356cf0)
Location: fs/proc/task_mmu.c:435
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff81356cf0-ffffffff81356d8c: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136f2c0)
Location: fs/proc/task_mmu.c:436
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff8136f2c0-ffffffff8136f35f: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b6990)
Location: fs/proc/task_mmu.c:406
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff813b6990-ffffffff813b6a2f: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c8030)
Location: fs/proc/task_mmu.c:406
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff813c8030-ffffffff813c80cf: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813cf060)
Location: fs/proc/task_mmu.c:403
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff813cf060-ffffffff813cf10b: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff814202f0)
Location: fs/proc/task_mmu.c:406
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff814202f0-ffffffff8142039b: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff814991a0)
Location: fs/proc/task_mmu.c:416
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff814991a0-ffffffff81499368: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152d560)
Location: fs/proc/task_mmu.c:427
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff8152d560-ffffffff8152d724: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81565980)
Location: fs/proc/task_mmu.c:424
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff81565980-ffffffff81565b57: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159cfc0)
Location: fs/proc/task_mmu.c:413
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff8159cfc0-ffffffff8159d191: smaps_page_accumulate (STB_LOCAL)
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
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff8000104388f0)
Location: fs/proc/task_mmu.c:436
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffff8000104388f0-ffff800010438a38: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c0600810)
Location: fs/proc/task_mmu.c:436
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
c0600810-c060094c: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c00000000054b970)
Location: fs/proc/task_mmu.c:436
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
c00000000054b970-c00000000054ba98: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffe0002d2c9a)
Location: fs/proc/task_mmu.c:436
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffe0002d2c9a-ffffffe0002d2d86: smaps_page_accumulate (STB_LOCAL)
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
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813678a0)
Location: fs/proc/task_mmu.c:436
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff813678a0-ffffffff8136793f: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81358540)
Location: fs/proc/task_mmu.c:436
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff81358540-ffffffff813585df: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81365370)
Location: fs/proc/task_mmu.c:436
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff81365370-ffffffff8136540f: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void smaps_page_accumulate(struct mem_size_stats *mss, struct page *page, long unsigned int size, long unsigned int pss, bool dirty, bool locked, bool private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81378a50)
Location: fs/proc/task_mmu.c:436
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
**Symbols:**

```
ffffffff81378a50-ffffffff81378aef: smaps_page_accumulate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
