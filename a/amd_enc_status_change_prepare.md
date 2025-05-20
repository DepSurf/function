# Function: <code>amd_enc_status_change_prepare</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void amd_enc_status_change_prepare(long unsigned int vaddr, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b98e0)
Location: arch/x86/mm/mem_encrypt_amd.c:321
Inline: True
```
**Symbols:**

```
ffffffff810b98e0-ffffffff810b9934: amd_enc_status_change_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void amd_enc_status_change_prepare(long unsigned int vaddr, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d5590)
Location: arch/x86/mm/mem_encrypt_amd.c:322
Inline: True
```
**Symbols:**

```
ffffffff810d5590-ffffffff810d55e4: amd_enc_status_change_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool amd_enc_status_change_prepare(long unsigned int vaddr, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d8900)
Location: arch/x86/mm/mem_encrypt_amd.c:321
Inline: False
```
**Symbols:**

```
ffffffff810d8900-ffffffff810d895a: amd_enc_status_change_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool amd_enc_status_change_prepare(long unsigned int vaddr, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810e1180)
Location: arch/x86/mm/mem_encrypt_amd.c:286
Inline: False
```
**Symbols:**

```
ffffffff810e1180-ffffffff810e11da: amd_enc_status_change_prepare (STB_LOCAL)
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
