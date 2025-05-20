# Function: <code>enc_dec_hypercall</code>

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
void enc_dec_hypercall(long unsigned int vaddr, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/mm/mem_encrypt_amd.c:290
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
```
**Symbols:**

```
ffffffff810b9940-ffffffff810b9a63: enc_dec_hypercall (STB_LOCAL)
ffffffff81e51cee-ffffffff81e51d5f: enc_dec_hypercall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void enc_dec_hypercall(long unsigned int vaddr, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/mm/mem_encrypt_amd.c:291
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
```
**Symbols:**

```
ffffffff810d5600-ffffffff810d5723: enc_dec_hypercall (STB_LOCAL)
ffffffff8205541f-ffffffff82055490: enc_dec_hypercall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void enc_dec_hypercall(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/mm/mem_encrypt_amd.c:291
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
```
**Symbols:**

```
ffffffff810d8ae0-ffffffff810d8bfd: enc_dec_hypercall (STB_LOCAL)
ffffffff820d39ea-ffffffff820d3a48: enc_dec_hypercall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void enc_dec_hypercall(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/mm/mem_encrypt_amd.c:256
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish
```
**Symbols:**

```
ffffffff810e1360-ffffffff810e147d: enc_dec_hypercall (STB_LOCAL)
ffffffff821ae858-ffffffff821ae8b6: enc_dec_hypercall.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>int npages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
