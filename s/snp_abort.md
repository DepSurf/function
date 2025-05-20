# Function: <code>snp_abort</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void snp_abort();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff8347185c)
Location: arch/x86/kernel/sev.c:2115
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_init
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff8347185c-ffffffff8347186c: snp_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void snp_abort();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e98730)
Location: arch/x86/kernel/sev.c:2115
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_init
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff83e98730-ffffffff83e98740: snp_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void snp_abort();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff836bc160)
Location: arch/x86/kernel/sev.c:2072
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_init
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff836bc160-ffffffff836bc170: snp_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void snp_abort();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff838ecb40)
Location: arch/x86/kernel/sev.c:2110
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_init
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff838ecb40-ffffffff838ecb50: snp_abort (STB_GLOBAL)
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
