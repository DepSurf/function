# Function: <code>memory_failure_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81201a60)
Location: mm/memory-failure.c:1341
Inline: False
```
**Symbols:**

```
ffffffff81201a60-ffffffff81201b0e: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812261a0)
Location: mm/memory-failure.c:1311
Inline: False
```
**Symbols:**

```
ffffffff812261a0-ffffffff8122624e: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81238770)
Location: mm/memory-failure.c:1307
Inline: False
```
**Symbols:**

```
ffffffff81238770-ffffffff8123881e: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81244240)
Location: mm/memory-failure.c:1329
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81244240-ffffffff812442ee: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812640c0)
Location: mm/memory-failure.c:1327
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff812640c0-ffffffff8126416e: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81288330)
Location: mm/memory-failure.c:1454
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81288330-ffffffff812883cd: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8129d280)
Location: mm/memory-failure.c:1458
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff8129d280-ffffffff8129d31d: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1451
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff812baa9a-ffffffff812baaae: memory_failure_queue.cold (STB_LOCAL)
ffffffff812b8390-ffffffff812b8420: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1457
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff812cc976-ffffffff812cc98a: memory_failure_queue.cold (STB_LOCAL)
ffffffff812ca270-ffffffff812ca300: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1480
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81302ac3-ffffffff81302ad7: memory_failure_queue.cold (STB_LOCAL)
ffffffff81300000-ffffffff81300090: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1595
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81be9e63-ffffffff81be9e77: memory_failure_queue.cold (STB_LOCAL)
ffffffff8130c340-ffffffff8130c3d0: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1686
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81bdbe8f-ffffffff81bdbea3: memory_failure_queue.cold (STB_LOCAL)
ffffffff81312aa0-ffffffff81312b30: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1841
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81cc2e63-ffffffff81cc2e77: memory_failure_queue.cold (STB_LOCAL)
ffffffff8135e4e0-ffffffff8135e570: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:2005
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81e753ec-ffffffff81e75400: memory_failure_queue.cold (STB_LOCAL)
ffffffff813d8d70-ffffffff813d8e3c: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145e810)
Location: mm/memory-failure.c:2245
Inline: False
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff8145e810-ffffffff8145e8e9: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81494660)
Location: mm/memory-failure.c:2373
Inline: False
Direct callers:
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_subpage
  - mm/memory.c:__wp_page_copy_user
  - mm/ksm.c:ksm_might_need_to_copy
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81494660-ffffffff81494739: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c3f70)
Location: mm/memory-failure.c:2423
Inline: False
Direct callers:
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_subpage
  - mm/memory.c:__wp_page_copy_user
  - mm/ksm.c:ksm_might_need_to_copy
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff814c3f70-ffffffff814c4049: memory_failure_queue (STB_GLOBAL)
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
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffff80001036e330)
Location: mm/memory-failure.c:1457
Inline: False
```
**Symbols:**

```
ffff80001036e330-ffff80001036e470: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045e1b0)
Location: mm/memory-failure.c:1457
Inline: False
```
**Symbols:**

```
c00000000045e1b0-c00000000045e300: memory_failure_queue (STB_GLOBAL)
```
</details>
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
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1457
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff812c4f56-ffffffff812c4f6a: memory_failure_queue.cold (STB_LOCAL)
ffffffff812c2850-ffffffff812c28e0: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1457
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff812b5f96-ffffffff812b5faa: memory_failure_queue.cold (STB_LOCAL)
ffffffff812b38a0-ffffffff812b3930: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1457
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff812c2d66-ffffffff812c2d7a: memory_failure_queue.cold (STB_LOCAL)
ffffffff812c0660-ffffffff812c06f0: memory_failure_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void memory_failure_queue(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1457
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff812d3806-ffffffff812d381a: memory_failure_queue.cold (STB_LOCAL)
ffffffff812d1100-ffffffff812d11b0: memory_failure_queue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int trapno</code>
</li>
<li>
<b>Param reordered. </b>
<code>pfn, trapno, flags</code> ➡️ <code>pfn, flags</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
