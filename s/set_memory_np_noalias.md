# Function: <code>set_memory_np_noalias</code>

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
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a5f0)
Location: arch/x86/mm/pageattr.c:1802
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff8107a5f0-ffffffff8107a61e: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080da0)
Location: arch/x86/mm/pageattr.c:1995
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff81080da0-ffffffff81080dce: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084880)
Location: arch/x86/mm/pageattr.c:2006
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff81084880-ffffffff810848ae: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085580)
Location: arch/x86/mm/pageattr.c:1912
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff81085580-ffffffff810855ae: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f2a0)
Location: arch/x86/mm/pat/set_memory.c:1948
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff8108f2a0-ffffffff8108f2ce: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f090)
Location: arch/x86/mm/pat/set_memory.c:1948
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff8108f090-ffffffff8108f0be: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fc20)
Location: arch/x86/mm/pat/set_memory.c:1956
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff8108fc20-ffffffff8108fc4e: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f700)
Location: arch/x86/mm/pat/set_memory.c:1956
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff8109f700-ffffffff8109f72e: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b34b0)
Location: arch/x86/mm/pat/set_memory.c:1993
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff810b34b0-ffffffff810b34f0: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce010)
Location: arch/x86/mm/pat/set_memory.c:2099
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff810ce010-ffffffff810ce050: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d15d0)
Location: arch/x86/mm/pat/set_memory.c:2100
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff810d15d0-ffffffff810d1610: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9cb0)
Location: arch/x86/mm/pat/set_memory.c:2099
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff810d9cb0-ffffffff810d9cf0: set_memory_np_noalias (STB_GLOBAL)
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
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084580)
Location: arch/x86/mm/pageattr.c:1912
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff81084580-ffffffff810845ae: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81073190)
Location: arch/x86/mm/pageattr.c:1912
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff81073190-ffffffff810731be: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084530)
Location: arch/x86/mm/pageattr.c:1912
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff81084530-ffffffff8108455e: set_memory_np_noalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_np_noalias(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086670)
Location: arch/x86/mm/pageattr.c:1912
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff81086670-ffffffff8108669e: set_memory_np_noalias (STB_GLOBAL)
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
