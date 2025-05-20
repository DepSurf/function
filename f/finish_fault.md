# Function: <code>finish_fault</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ea300)
Location: mm/memory.c:3101
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff811ea300-ffffffff811ea34b: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f5350)
Location: mm/memory.c:3297
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff811f5350-ffffffff811f53c5: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120d460)
Location: mm/memory.c:3466
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8120d460-ffffffff8120d4d5: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122e040)
Location: mm/memory.c:3511
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff8122e040-ffffffff8122e0b5: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812416a0)
Location: mm/memory.c:3272
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812416a0-ffffffff81241715: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812539e0)
Location: mm/memory.c:3325
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
ffffffff812539e0-ffffffff81253a5b: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81261f40)
Location: mm/memory.c:3350
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
ffffffff81261f40-ffffffff81261fbb: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81291d70)
Location: mm/memory.c:3712
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_shared_fault
  - mm/memory.c:do_cow_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff81291d70-ffffffff81291de7: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129c630)
Location: mm/memory.c:3872
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_shared_fault
  - mm/memory.c:do_cow_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8129c630-ffffffff8129c6a7: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a1a80)
Location: mm/memory.c:3866
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff812a1a80-ffffffff812a1d96: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e2a50)
Location: mm/memory.c:4011
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - fs/dax.c:dax_fault_cow_page
```
**Symbols:**

```
ffffffff812e2a50-ffffffff812e2cd7: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813433a0)
Location: mm/memory.c:4338
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - fs/dax.c:dax_fault_cow_page
```
**Symbols:**

```
ffffffff813433a0-ffffffff81343600: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bb3e0)
Location: mm/memory.c:4339
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - fs/dax.c:dax_fault_cow_page
```
**Symbols:**

```
ffffffff813bb3e0-ffffffff813bb666: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813eff10)
Location: mm/memory.c:4371
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_read_fault
  - fs/dax.c:dax_fault_cow_page
```
**Symbols:**

```
ffffffff813eff10-ffffffff813f00c3: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141b570)
Location: mm/memory.c:4579
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - fs/dax.c:dax_fault_cow_page
```
**Symbols:**

```
ffffffff8141b570-ffffffff8141b74b: finish_fault (STB_GLOBAL)
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
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f91f8)
Location: mm/memory.c:3350
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
ffff8000102f91f8-ffff8000102f9280: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051b604)
Location: mm/memory.c:3350
Inline: True
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
c051b604-c051b6b4: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c2d50)
Location: mm/memory.c:3350
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
c0000000003c2d50-c0000000003c2e38: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002091d4)
Location: mm/memory.c:3350
Inline: True
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
ffffffe0002091d4-ffffffe000209274: finish_fault (STB_GLOBAL)
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
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125a590)
Location: mm/memory.c:3350
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
ffffffff8125a590-ffffffff8125a60b: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124c9b0)
Location: mm/memory.c:3350
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
ffffffff8124c9b0-ffffffff8124ca2b: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81258330)
Location: mm/memory.c:3350
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
ffffffff81258330-ffffffff812583ab: finish_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t finish_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81267d10)
Location: mm/memory.c:3350
Inline: False
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
```
**Symbols:**

```
ffffffff81267d10-ffffffff81267d8d: finish_fault (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
