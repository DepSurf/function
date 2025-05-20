# Function: <code>set_memory_global</code>

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
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a680)
Location: arch/x86/mm/pageattr.c:1823
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_kernel_text
```
**Symbols:**

```
ffffffff8107a680-ffffffff8107a6ab: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080e30)
Location: arch/x86/mm/pageattr.c:2016
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81080e30-ffffffff81080e5b: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084910)
Location: arch/x86/mm/pageattr.c:2027
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81084910-ffffffff8108493b: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085610)
Location: arch/x86/mm/pageattr.c:1933
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81085610-ffffffff8108563b: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f330)
Location: arch/x86/mm/pat/set_memory.c:1969
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_kernel_text
```
**Symbols:**

```
ffffffff8108f330-ffffffff8108f35b: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f120)
Location: arch/x86/mm/pat/set_memory.c:1969
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_kernel_text
```
**Symbols:**

```
ffffffff8108f120-ffffffff8108f14b: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fcb0)
Location: arch/x86/mm/pat/set_memory.c:1977
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff8108fcb0-ffffffff8108fcdb: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f790)
Location: arch/x86/mm/pat/set_memory.c:1977
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff8109f790-ffffffff8109f7bb: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3570)
Location: arch/x86/mm/pat/set_memory.c:2014
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff810b3570-ffffffff810b35ad: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce100)
Location: arch/x86/mm/pat/set_memory.c:2118
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff810ce100-ffffffff810ce13d: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d16c0)
Location: arch/x86/mm/pat/set_memory.c:2119
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff810d16c0-ffffffff810d16fd: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9df0)
Location: arch/x86/mm/pat/set_memory.c:2123
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff810d9df0-ffffffff810d9e2d: set_memory_global (STB_GLOBAL)
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
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084610)
Location: arch/x86/mm/pageattr.c:1933
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81084610-ffffffff8108463b: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81073220)
Location: arch/x86/mm/pageattr.c:1933
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81073220-ffffffff8107324b: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810845c0)
Location: arch/x86/mm/pageattr.c:1933
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff810845c0-ffffffff810845eb: set_memory_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_global(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086700)
Location: arch/x86/mm/pageattr.c:1933
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81086700-ffffffff8108672b: set_memory_global (STB_GLOBAL)
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
