# Function: <code>arch_wb_cache_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8128698c)
Location: arch/x86/include/asm/pmem.h:63
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_do_io
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
In fs/dax.c (ffffffff8129abf9)
Location: arch/x86/include/asm/pmem.h:60
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff818fd590)
Location: arch/x86/lib/usercopy_64.c:100
Inline: False
```
**Symbols:**

```
ffffffff818fd590-ffffffff818fd5c0: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81985070)
Location: arch/x86/lib/usercopy_64.c:100
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81985070-ffffffff819850a2: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819e1560)
Location: arch/x86/lib/usercopy_64.c:120
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff819e1560-ffffffff819e1591: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c510)
Location: arch/x86/lib/usercopy_64.c:120
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81a1c510-ffffffff81a1c541: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c1c0)
Location: arch/x86/lib/usercopy_64.c:101
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81a8c1c0-ffffffff81a8c1f4: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ac3480)
Location: arch/x86/lib/usercopy_64.c:101
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81ac3480-ffffffff81ac34b4: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff815ff9f0)
Location: arch/x86/lib/usercopy_64.c:102
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff815ff9f0-ffffffff815ffa00: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81624920)
Location: arch/x86/lib/usercopy_64.c:81
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81624920-ffffffff81624930: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff816082f0)
Location: arch/x86/lib/usercopy_64.c:81
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff816082f0-ffffffff81608300: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81676f30)
Location: arch/x86/lib/usercopy_64.c:81
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81676f30-ffffffff81676f40: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81791f00)
Location: arch/x86/lib/usercopy_64.c:79
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81791f00-ffffffff81791f18: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8204fce0)
Location: arch/x86/lib/usercopy_64.c:39
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff8204fce0-ffffffff8204fcf8: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff820ce230)
Location: arch/x86/lib/usercopy_64.c:40
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff820ce230-ffffffff820ce248: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff821a8a40)
Location: arch/x86/lib/usercopy_64.c:40
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff821a8a40-ffffffff821a8a58: arch_wb_cache_pmem (STB_GLOBAL)
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
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/flush.c (ffff8000100adb38)
Location: arch/arm64/mm/flush.c:81
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffff8000100adb38-ffff8000100adb70: arch_wb_cache_pmem (STB_GLOBAL)
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
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/lib/pmem.c (c0000000000a7d80)
Location: arch/powerpc/lib/pmem.c:15
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
c0000000000a7d80-c0000000000a7de8: arch_wb_cache_pmem (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a622d0)
Location: arch/x86/lib/usercopy_64.c:101
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81a622d0-ffffffff81a62304: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f340)
Location: arch/x86/lib/usercopy_64.c:101
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81a1f340-ffffffff81a1f374: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ace6c0)
Location: arch/x86/lib/usercopy_64.c:101
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81ace6c0-ffffffff81ace6f4: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81adabd0)
Location: arch/x86/lib/usercopy_64.c:101
Inline: False
Direct callers:
  - drivers/dax/super.c:dax_flush
```
**Symbols:**

```
ffffffff81adabd0-ffffffff81adac04: arch_wb_cache_pmem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
