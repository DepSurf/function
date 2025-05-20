# Function: <code>kernel_page_present</code>

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
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2174
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2301
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2288
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2404
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2513
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2646
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2691
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084ab0)
Location: arch/x86/mm/pageattr.c:2304
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff81084ab0-ffffffff81084b25: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810857b0)
Location: arch/x86/mm/pageattr.c:2194
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff810857b0-ffffffff81085825: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f570)
Location: arch/x86/mm/pat/set_memory.c:2230
Inline: False
Direct callers:
  - kernel/power/snapshot.c:safe_copy_page
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff8108f570-ffffffff8108f5ed: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f330)
Location: arch/x86/mm/pat/set_memory.c:2231
Inline: False
Direct callers:
  - kernel/power/snapshot.c:safe_copy_page
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff8108f330-ffffffff8108f3ad: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fec0)
Location: arch/x86/mm/pat/set_memory.c:2239
Inline: False
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff8108fec0-ffffffff8108ff3d: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:2239
Inline: False
```
**Symbols:**

```
ffffffff81ca1413-ffffffff81ca1434: kernel_page_present.cold (STB_LOCAL)
ffffffff8109f9a0-ffffffff8109fa2b: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:2290
Inline: False
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff81e50a1b-ffffffff81e50a3c: kernel_page_present.cold (STB_LOCAL)
ffffffff810b37d0-ffffffff810b3866: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:2394
Inline: False
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff82054ecd-ffffffff82054eee: kernel_page_present.cold (STB_LOCAL)
ffffffff810ce3d0-ffffffff810ce466: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:2393
Inline: False
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff820d349c-ffffffff820d34bd: kernel_page_present.cold (STB_LOCAL)
ffffffff810d1990-ffffffff810d1a26: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:2397
Inline: False
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff821ae30a-ffffffff821ae32b: kernel_page_present.cold (STB_LOCAL)
ffffffff810da0c0-ffffffff810da156: kernel_page_present (STB_GLOBAL)
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
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pageattr.c (ffff8000100b0680)
Location: arch/arm64/mm/pageattr.c:198
Inline: False
```
**Symbols:**

```
ffff8000100b0680-ffff8000100b0770: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2736
Inline: True
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810847b0)
Location: arch/x86/mm/pageattr.c:2194
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff810847b0-ffffffff81084825: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810733b0)
Location: arch/x86/mm/pageattr.c:2194
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff810733b0-ffffffff8107341e: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084760)
Location: arch/x86/mm/pageattr.c:2194
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff81084760-ffffffff810847d5: kernel_page_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kernel_page_present(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810868b0)
Location: arch/x86/mm/pageattr.c:2194
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff810868b0-ffffffff81086925: kernel_page_present (STB_GLOBAL)
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
