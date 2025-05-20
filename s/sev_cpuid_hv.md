# Function: <code>sev_cpuid_hv</code>

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
int sev_cpuid_hv(struct cpuid_leaf *leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a48c0)
Location: arch/x86/kernel/sev-shared.c:256
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
```
**Symbols:**

```
ffffffff810a48c0-ffffffff810a4969: sev_cpuid_hv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sev_cpuid_hv(struct cpuid_leaf *leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bcdf0)
Location: arch/x86/kernel/sev-shared.c:256
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
```
**Symbols:**

```
ffffffff810bcdf0-ffffffff810bce7e: sev_cpuid_hv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sev_cpuid_hv(struct cpuid_leaf *leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c0410)
Location: arch/x86/kernel/sev-shared.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
```
**Symbols:**

```
ffffffff810c0410-ffffffff810c04a0: sev_cpuid_hv (STB_LOCAL)
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
In arch/x86/kernel/sev.c (ffffffff810c78f5)
Location: arch/x86/kernel/sev-shared.c:315
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
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
</ul>
