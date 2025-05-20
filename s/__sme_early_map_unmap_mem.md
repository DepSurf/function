# Function: <code>__sme_early_map_unmap_mem</code>

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
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c595e)
Location: arch/x86/mm/mem_encrypt.c:123
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff826c595e-ffffffff826c59c7: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826efa36)
Location: arch/x86/mm/mem_encrypt.c:118
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff826efa36-ffffffff826efa9d: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a66f3)
Location: arch/x86/mm/mem_encrypt.c:118
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff828a66f3-ffffffff828a675a: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828bed52)
Location: arch/x86/mm/mem_encrypt.c:119
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff828bed52-ffffffff828bedff: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c51cb)
Location: arch/x86/mm/mem_encrypt.c:119
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff828c51cb-ffffffff828c5278: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8520)
Location: arch/x86/mm/mem_encrypt.c:119
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff82ce8520-ffffffff82ce8560: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd5f3f)
Location: arch/x86/mm/mem_encrypt.c:121
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff82fd5f3f-ffffffff82fd5f7f: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff831e09ab)
Location: arch/x86/mm/mem_encrypt.c:120
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff831e09ab-ffffffff831e09eb: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff832c4089)
Location: arch/x86/mm/mem_encrypt.c:121
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff832c4089-ffffffff832c40c9: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476aac)
Location: arch/x86/mm/mem_encrypt_amd.c:156
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff83476aac-ffffffff83476af8: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83ea02d0)
Location: arch/x86/mm/mem_encrypt_amd.c:157
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c4440)
Location: arch/x86/mm/mem_encrypt_amd.c:157
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f50c0)
Location: arch/x86/mm/mem_encrypt_amd.c:156
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
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
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0163)
Location: arch/x86/mm/mem_encrypt.c:119
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff828b0163-ffffffff828b0210: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8350)
Location: arch/x86/mm/mem_encrypt.c:119
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff828a8350-ffffffff828a83fd: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3062)
Location: arch/x86/mm/mem_encrypt.c:119
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff828c3062-ffffffff828c310f: __sme_early_map_unmap_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sme_early_map_unmap_mem(void *vaddr, long unsigned int size, bool map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c61eb)
Location: arch/x86/mm/mem_encrypt.c:119
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff828c61eb-ffffffff828c62b5: __sme_early_map_unmap_mem (STB_LOCAL)
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
