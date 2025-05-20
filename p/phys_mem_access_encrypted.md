# Function: <code>phys_mem_access_encrypted</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810743e0)
Location: arch/x86/mm/ioremap.c:695
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff810743e0-ffffffff810743f2: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81076df0)
Location: arch/x86/mm/ioremap.c:695
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff81076df0-ffffffff81076e02: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8107d480)
Location: arch/x86/mm/ioremap.c:703
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff8107d480-ffffffff8107d492: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080d30)
Location: arch/x86/mm/ioremap.c:728
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff81080d30-ffffffff81080d42: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81081df0)
Location: arch/x86/mm/ioremap.c:750
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff81081df0-ffffffff81081e02: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088e80)
Location: arch/x86/mm/ioremap.c:761
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff81088e80-ffffffff81088ea0: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810890c0)
Location: arch/x86/mm/ioremap.c:761
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff810890c0-ffffffff810890e0: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81089d40)
Location: arch/x86/mm/ioremap.c:744
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff81089d40-ffffffff81089d60: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81099210)
Location: arch/x86/mm/ioremap.c:789
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff81099210-ffffffff81099230: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810abfe0)
Location: arch/x86/mm/ioremap.c:795
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff810abfe0-ffffffff810abffc: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c5da0)
Location: arch/x86/mm/ioremap.c:804
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff810c5da0-ffffffff810c5dbc: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c9510)
Location: arch/x86/mm/ioremap.c:809
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff810c9510-ffffffff810c952c: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d1970)
Location: arch/x86/mm/ioremap.c:809
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff810d1970-ffffffff810d198c: phys_mem_access_encrypted (STB_GLOBAL)
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
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080df0)
Location: arch/x86/mm/ioremap.c:750
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff81080df0-ffffffff81080e02: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106fd40)
Location: arch/x86/mm/ioremap.c:750
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff8106fd40-ffffffff8106fd52: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080da0)
Location: arch/x86/mm/ioremap.c:750
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff81080da0-ffffffff81080db2: phys_mem_access_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool phys_mem_access_encrypted(long unsigned int phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81082ec0)
Location: arch/x86/mm/ioremap.c:750
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:phys_mem_access_prot
```
**Symbols:**

```
ffffffff81082ec0-ffffffff81082ed2: phys_mem_access_encrypted (STB_GLOBAL)
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
