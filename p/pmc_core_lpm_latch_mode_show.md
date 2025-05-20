# Function: <code>pmc_core_lpm_latch_mode_show</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pmc_core_lpm_latch_mode_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a9120)
Location: drivers/platform/x86/intel_pmc_core.c:1327
Inline: False
```
**Symbols:**

```
ffffffff819a9120-ffffffff819a91fe: pmc_core_lpm_latch_mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pmc_core_lpm_latch_mode_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1627
Inline: False
```
**Symbols:**

```
ffffffff81a563b0-ffffffff81a564f2: pmc_core_lpm_latch_mode_show (STB_LOCAL)
ffffffff81d30e0c-ffffffff81d30e25: pmc_core_lpm_latch_mode_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pmc_core_lpm_latch_mode_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1627
Inline: False
```
**Symbols:**

```
ffffffff81bc5c90-ffffffff81bc5dee: pmc_core_lpm_latch_mode_show (STB_LOCAL)
ffffffff81efd23e-ffffffff81efd25f: pmc_core_lpm_latch_mode_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pmc_core_lpm_latch_mode_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:735
Inline: False
```
**Symbols:**

```
ffffffff81d6de20-ffffffff81d6df7e: pmc_core_lpm_latch_mode_show (STB_LOCAL)
ffffffff820aa06c-ffffffff820aa08d: pmc_core_lpm_latch_mode_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pmc_core_lpm_latch_mode_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:812
Inline: False
```
**Symbols:**

```
ffffffff81ddb380-ffffffff81ddb4df: pmc_core_lpm_latch_mode_show (STB_LOCAL)
ffffffff8212b556-ffffffff8212b577: pmc_core_lpm_latch_mode_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
