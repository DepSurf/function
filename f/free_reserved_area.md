# Function: <code>free_reserved_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81195120)
Location: mm/page_alloc.c:5792
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff81195120-ffffffff81195243: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a9160)
Location: mm/page_alloc.c:6419
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff811a9160-ffffffff811a9287: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b96c0)
Location: mm/page_alloc.c:6458
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff811b96c0-ffffffff811b97d1: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1730)
Location: mm/page_alloc.c:6753
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff811c1730-ffffffff811c1840: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5b50)
Location: mm/page_alloc.c:6766
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff811d5b50-ffffffff811d5c60: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:6934
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff811fad2d-ffffffff811fad4a: free_reserved_area.cold.114 (STB_LOCAL)
ffffffff811f6f60-ffffffff811f7087: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7239
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff8120d5d7-ffffffff8120d5f4: free_reserved_area.cold.118 (STB_LOCAL)
ffffffff81209300-ffffffff81209427: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7441
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff81274434-ffffffff81274451: free_reserved_area.cold (STB_LOCAL)
ffffffff81272810-ffffffff81272965: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7471
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff8128324b-ffffffff81283268: free_reserved_area.cold (STB_LOCAL)
ffffffff81281670-ffffffff812817c5: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7500
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff812b5309-ffffffff812b5326: free_reserved_area.cold (STB_LOCAL)
ffffffff812b3b40-ffffffff812b3ca6: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7646
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff81be863d-ffffffff81be865a: free_reserved_area.cold (STB_LOCAL)
ffffffff812bf610-ffffffff812bf763: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7864
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff81bda440-ffffffff81bda45d: free_reserved_area.cold (STB_LOCAL)
ffffffff812c4c90-ffffffff812c4de5: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8106
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff81cbe49d-ffffffff81cbe4ba: free_reserved_area.cold (STB_LOCAL)
ffffffff81309140-ffffffff81309295: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8292
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff81e70468-ffffffff81e70485: free_reserved_area.cold (STB_LOCAL)
ffffffff81371640-ffffffff81371798: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813eed70)
Location: mm/page_alloc.c:8466
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff813eed70-ffffffff813eeedc: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81422b40)
Location: mm/page_alloc.c:5529
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_initrd_mem
```
**Symbols:**

```
ffffffff81422b40-ffffffff81422cac: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144fa20)
Location: mm/page_alloc.c:5671
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_initrd_mem
```
**Symbols:**

```
ffffffff8144fa20-ffffffff8144fb8c: free_reserved_area (STB_GLOBAL)
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
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010319b48)
Location: mm/page_alloc.c:7471
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/arm64/mm/init.c:free_initrd_mem
  - arch/arm64/mm/init.c:free_initmem
```
**Symbols:**

```
ffff800010319b48-ffff800010319c90: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0534454)
Location: mm/page_alloc.c:7471
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/arm/mm/init.c:free_initrd_mem
  - arch/arm/mm/init.c:free_initmem
```
**Symbols:**

```
c0534454-c053456c: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ecb80)
Location: mm/page_alloc.c:7471
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/powerpc/kernel/fadump.c:fadump_free_cpu_notes_buf
  - arch/powerpc/mm/mem.c:free_initmem
```
**Symbols:**

```
c0000000003ecb80-c0000000003ecd94: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021f62e)
Location: mm/page_alloc.c:7471
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
```
**Symbols:**

```
ffffffe00021f62e-ffffffe00021f77c: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7471
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff8127b89b-ffffffff8127b8b8: free_reserved_area.cold (STB_LOCAL)
ffffffff81279cc0-ffffffff81279e15: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7471
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff8126d77b-ffffffff8126d798: free_reserved_area.cold (STB_LOCAL)
ffffffff8126bbb0-ffffffff8126bd05: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7471
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff8127963b-ffffffff81279658: free_reserved_area.cold (STB_LOCAL)
ffffffff81277a60-ffffffff81277bb5: free_reserved_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long unsigned int free_reserved_area(void *start, void *end, int poison, const char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7471
Inline: False
Direct callers:
  - init/main.c:free_initmem
  - init/initramfs.c:free_initrd_mem
  - arch/x86/mm/init.c:free_init_pages
```
**Symbols:**

```
ffffffff8128922b-ffffffff81289248: free_reserved_area.cold (STB_LOCAL)
ffffffff81287650-ffffffff812877a5: free_reserved_area (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *s</code> ➡️ <code>const char *s</code>
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
