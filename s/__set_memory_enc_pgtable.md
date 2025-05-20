# Function: <code>__set_memory_enc_pgtable</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __set_memory_enc_pgtable(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:2024
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff810b2aa0-ffffffff810b2c51: __set_memory_enc_pgtable (STB_LOCAL)
ffffffff81e509ca-ffffffff81e509eb: __set_memory_enc_pgtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __set_memory_enc_pgtable(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:2128
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff810cd460-ffffffff810cd611: __set_memory_enc_pgtable (STB_LOCAL)
ffffffff82054e90-ffffffff82054eb1: __set_memory_enc_pgtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __set_memory_enc_pgtable(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:2129
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff810d0a90-ffffffff810d0c43: __set_memory_enc_pgtable (STB_LOCAL)
ffffffff820d3467-ffffffff820d3480: __set_memory_enc_pgtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __set_memory_enc_pgtable(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:2133
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff810d9170-ffffffff810d9323: __set_memory_enc_pgtable (STB_LOCAL)
ffffffff821ae2d5-ffffffff821ae2ee: __set_memory_enc_pgtable.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
