# Function: <code>set_memory_nonglobal</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a650)
Location: arch/x86/mm/pageattr.c:1817
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8107a650-ffffffff8107a67b: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080e00)
Location: arch/x86/mm/pageattr.c:2010
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff81080e00-ffffffff81080e2b: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810848e0)
Location: arch/x86/mm/pageattr.c:2021
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810848e0-ffffffff8108490b: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810855e0)
Location: arch/x86/mm/pageattr.c:1927
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810855e0-ffffffff8108560b: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f300)
Location: arch/x86/mm/pat/set_memory.c:1963
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108f300-ffffffff8108f32b: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f0f0)
Location: arch/x86/mm/pat/set_memory.c:1963
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108f0f0-ffffffff8108f11b: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fc80)
Location: arch/x86/mm/pat/set_memory.c:1971
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108fc80-ffffffff8108fcab: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f760)
Location: arch/x86/mm/pat/set_memory.c:1971
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8109f760-ffffffff8109f78b: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3530)
Location: arch/x86/mm/pat/set_memory.c:2008
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810b3530-ffffffff810b356d: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce0b0)
Location: arch/x86/mm/pat/set_memory.c:2112
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810ce0b0-ffffffff810ce0ed: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d1670)
Location: arch/x86/mm/pat/set_memory.c:2113
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810d1670-ffffffff810d16ad: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9da0)
Location: arch/x86/mm/pat/set_memory.c:2117
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810d9da0-ffffffff810d9ddd: set_memory_nonglobal (STB_GLOBAL)
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
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810845e0)
Location: arch/x86/mm/pageattr.c:1927
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810845e0-ffffffff8108460b: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810731f0)
Location: arch/x86/mm/pageattr.c:1927
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810731f0-ffffffff8107321b: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084590)
Location: arch/x86/mm/pageattr.c:1927
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff81084590-ffffffff810845bb: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_nonglobal(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810866d0)
Location: arch/x86/mm/pageattr.c:1927
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810866d0-ffffffff810866fb: set_memory_nonglobal (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
