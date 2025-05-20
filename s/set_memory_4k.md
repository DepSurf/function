# Function: <code>set_memory_4k</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f3f0)
Location: arch/x86/mm/pageattr.c:1718
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs_64.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
**Symbols:**

```
ffffffff8106f3f0-ffffffff8106f421: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f150)
Location: arch/x86/mm/pageattr.c:1726
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs_64.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
**Symbols:**

```
ffffffff8106f150-ffffffff8106f181: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072dc0)
Location: arch/x86/mm/pageattr.c:1726
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
**Symbols:**

```
ffffffff81072dc0-ffffffff81072df1: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072340)
Location: arch/x86/mm/pageattr.c:1772
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
**Symbols:**

```
ffffffff81072340-ffffffff8107236b: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81077bb0)
Location: arch/x86/mm/pageattr.c:1772
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
**Symbols:**

```
ffffffff81077bb0-ffffffff81077bdb: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a620)
Location: arch/x86/mm/pageattr.c:1811
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
**Symbols:**

```
ffffffff8107a620-ffffffff8107a64b: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080dd0)
Location: arch/x86/mm/pageattr.c:2004
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
**Symbols:**

```
ffffffff81080dd0-ffffffff81080dfb: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810848b0)
Location: arch/x86/mm/pageattr.c:2015
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
**Symbols:**

```
ffffffff810848b0-ffffffff810848db: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810855b0)
Location: arch/x86/mm/pageattr.c:1921
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
**Symbols:**

```
ffffffff810855b0-ffffffff810855db: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f2d0)
Location: arch/x86/mm/pat/set_memory.c:1957
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
**Symbols:**

```
ffffffff8108f2d0-ffffffff8108f2fb: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f0c0)
Location: arch/x86/mm/pat/set_memory.c:1957
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff8108f0c0-ffffffff8108f0eb: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fc50)
Location: arch/x86/mm/pat/set_memory.c:1965
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff8108fc50-ffffffff8108fc7b: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f730)
Location: arch/x86/mm/pat/set_memory.c:1965
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - mm/kfence/core.c:kfence_init_pool
```
**Symbols:**

```
ffffffff8109f730-ffffffff8109f75b: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b34f0)
Location: arch/x86/mm/pat/set_memory.c:2002
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - mm/kfence/core.c:kfence_init_pool
```
**Symbols:**

```
ffffffff810b34f0-ffffffff810b352d: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce060)
Location: arch/x86/mm/pat/set_memory.c:2106
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - mm/kfence/core.c:kfence_init_pool
```
**Symbols:**

```
ffffffff810ce060-ffffffff810ce09d: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d1620)
Location: arch/x86/mm/pat/set_memory.c:2107
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:arch_cpu_finalize_init
  - mm/kfence/core.c:kfence_init_pool
```
**Symbols:**

```
ffffffff810d1620-ffffffff810d165d: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9d50)
Location: arch/x86/mm/pat/set_memory.c:2111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:arch_cpu_finalize_init
```
**Symbols:**

```
ffffffff810d9d50-ffffffff810d9d8d: set_memory_4k (STB_GLOBAL)
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
In <code>armhf</code>: Absent ⚠️
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
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810845b0)
Location: arch/x86/mm/pageattr.c:1921
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
**Symbols:**

```
ffffffff810845b0-ffffffff810845db: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810731c0)
Location: arch/x86/mm/pageattr.c:1921
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
**Symbols:**

```
ffffffff810731c0-ffffffff810731eb: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084560)
Location: arch/x86/mm/pageattr.c:1921
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
**Symbols:**

```
ffffffff81084560-ffffffff8108458b: set_memory_4k (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_4k(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810866a0)
Location: arch/x86/mm/pageattr.c:1921
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
**Symbols:**

```
ffffffff810866a0-ffffffff810866cb: set_memory_4k (STB_GLOBAL)
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
