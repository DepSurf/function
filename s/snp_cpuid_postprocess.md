# Function: <code>snp_cpuid_postprocess</code>

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
int snp_cpuid_postprocess(struct cpuid_leaf *leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a4970)
Location: arch/x86/kernel/sev-shared.c:394
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_cpuid
```
**Symbols:**

```
ffffffff810a4970-ffffffff810a4bd3: snp_cpuid_postprocess (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int snp_cpuid_postprocess(struct cpuid_leaf *leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bce90)
Location: arch/x86/kernel/sev-shared.c:394
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_cpuid
```
**Symbols:**

```
ffffffff810bce90-ffffffff810bd0ed: snp_cpuid_postprocess (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int snp_cpuid_postprocess(struct cpuid_leaf *leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c04b0)
Location: arch/x86/kernel/sev-shared.c:397
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_cpuid
```
**Symbols:**

```
ffffffff810c04b0-ffffffff810c0758: snp_cpuid_postprocess (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int snp_cpuid_postprocess(struct ghcb *ghcb, struct es_em_ctxt *ctxt, struct cpuid_leaf *leaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c78a0)
Location: arch/x86/kernel/sev-shared.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_cpuid
```
**Symbols:**

```
ffffffff810c78a0-ffffffff810c7b94: snp_cpuid_postprocess (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ghcb *ghcb</code>
</li>
<li>
<b>Param added. </b>
<code>struct es_em_ctxt *ctxt</code>
</li>
<li>
<b>Param reordered. </b>
<code>leaf</code> ➡️ <code>ghcb, ctxt, leaf</code>
</li>
</ul>
</details>
</li>
</ul>
