# Function: <code>valid_mmap_phys_addr_range</code>

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
In drivers/char/mem.c (0)
Location: drivers/char/mem.c:56
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
In drivers/char/mem.c (0)
Location: drivers/char/mem.c:57
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
In drivers/char/mem.c (0)
Location: drivers/char/mem.c:57
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
In drivers/char/mem.c (0)
Location: drivers/char/mem.c:56
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81078170)
Location: arch/x86/mm/mmap.c:233
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81078170-ffffffff81078197: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8107ac40)
Location: arch/x86/mm/mmap.c:237
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff8107ac40-ffffffff8107ac67: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81081580)
Location: arch/x86/mm/mmap.c:237
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81081580-ffffffff810815a7: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81085200)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81085200-ffffffff81085227: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81085ef0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81085ef0-ffffffff81085f17: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81089650)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81089650-ffffffff81089677: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81089830)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81089830-ffffffff81089857: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8108a520)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff8108a520-ffffffff8108a547: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81ca1056-ffffffff81ca1074: valid_mmap_phys_addr_range.cold (STB_LOCAL)
ffffffff81099a80-ffffffff81099ab8: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81e50635-ffffffff81e50653: valid_mmap_phys_addr_range.cold (STB_LOCAL)
ffffffff810ac9d0-ffffffff810aca14: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff82054b16-ffffffff82054b34: valid_mmap_phys_addr_range.cold (STB_LOCAL)
ffffffff810c6a90-ffffffff810c6ad4: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff820d3120-ffffffff820d313e: valid_mmap_phys_addr_range.cold (STB_LOCAL)
ffffffff810ca220-ffffffff810ca264: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff821adf8e-ffffffff821adfac: valid_mmap_phys_addr_range.cold (STB_LOCAL)
ffffffff810d2680-ffffffff810d26c4: valid_mmap_phys_addr_range (STB_GLOBAL)
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmap.c (ffff8000100ae0b8)
Location: arch/arm64/mm/mmap.c:46
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffff8000100ae0b8-ffff8000100ae0ec: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/mmap.c (c031f764)
Location: arch/arm/mm/mmap.c:164
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
c031f764-c031f78c: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (0)
Location: drivers/char/mem.c:57
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (0)
Location: drivers/char/mem.c:57
Inline: True
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81084ef0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81084ef0-ffffffff81084f17: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81073bc0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81073bc0-ffffffff81073be7: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81084ea0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81084ea0-ffffffff81084ec7: valid_mmap_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81086ff0)
Location: arch/x86/mm/mmap.c:224
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81086ff0-ffffffff81087017: valid_mmap_phys_addr_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
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
