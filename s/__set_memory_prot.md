# Function: <code>__set_memory_prot</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __set_memory_prot(long unsigned int addr, int numpages, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ef70)
Location: arch/x86/mm/pat/set_memory.c:1813
Inline: False
```
**Symbols:**

```
ffffffff8108ef70-ffffffff8108ef9a: __set_memory_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __set_memory_prot(long unsigned int addr, int numpages, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ed60)
Location: arch/x86/mm/pat/set_memory.c:1813
Inline: False
```
**Symbols:**

```
ffffffff8108ed60-ffffffff8108ed8a: __set_memory_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __set_memory_prot(long unsigned int addr, int numpages, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f8f0)
Location: arch/x86/mm/pat/set_memory.c:1821
Inline: False
```
**Symbols:**

```
ffffffff8108f8f0-ffffffff8108f91a: __set_memory_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __set_memory_prot(long unsigned int addr, int numpages, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f3d0)
Location: arch/x86/mm/pat/set_memory.c:1821
Inline: False
```
**Symbols:**

```
ffffffff8109f3d0-ffffffff8109f3fa: __set_memory_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __set_memory_prot(long unsigned int addr, int numpages, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2fd0)
Location: arch/x86/mm/pat/set_memory.c:1813
Inline: False
```
**Symbols:**

```
ffffffff810b2fd0-ffffffff810b300c: __set_memory_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __set_memory_prot(long unsigned int addr, int numpages, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd9f0)
Location: arch/x86/mm/pat/set_memory.c:1909
Inline: False
```
**Symbols:**

```
ffffffff810cd9f0-ffffffff810cda2c: __set_memory_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __set_memory_prot(long unsigned int addr, int numpages, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d0fb0)
Location: arch/x86/mm/pat/set_memory.c:1910
Inline: False
```
**Symbols:**

```
ffffffff810d0fb0-ffffffff810d0fec: __set_memory_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __set_memory_prot(long unsigned int addr, int numpages, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9690)
Location: arch/x86/mm/pat/set_memory.c:1914
Inline: False
```
**Symbols:**

```
ffffffff810d9690-ffffffff810d96cc: __set_memory_prot (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
