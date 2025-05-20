# Function: <code>pmc_core_send_ltr_ignore</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_send_ltr_ignore(struct pmc_dev *pmcdev, u32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a9c13)
Location: drivers/platform/x86/intel_pmc_core.c:1030
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_write
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff819a84d0-ffffffff819a853c: pmc_core_send_ltr_ignore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pmc_core_send_ltr_ignore(struct pmc_dev *pmcdev, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1330
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_write
```
**Symbols:**

```
ffffffff81a55a70-ffffffff81a55aed: pmc_core_send_ltr_ignore (STB_LOCAL)
ffffffff81d30df3-ffffffff81d30e0c: pmc_core_send_ltr_ignore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pmc_core_send_ltr_ignore(struct pmc_dev *pmcdev, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1330
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_write
```
**Symbols:**

```
ffffffff81bc52a0-ffffffff81bc5326: pmc_core_send_ltr_ignore (STB_LOCAL)
ffffffff81efd225-ffffffff81efd23e: pmc_core_send_ltr_ignore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pmc_core_send_ltr_ignore(struct pmc_dev *pmcdev, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:438
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_write
  - drivers/platform/x86/intel/pmc/tgl.c:tgl_core_configure
  - drivers/platform/x86/intel/pmc/adl.c:adl_core_configure
  - drivers/platform/x86/intel/pmc/mtl.c:mtl_core_configure
```
**Symbols:**

```
ffffffff820aa134-ffffffff820aa14d: pmc_core_send_ltr_ignore.cold (STB_LOCAL)
ffffffff81d6f040-ffffffff81d6f0c6: pmc_core_send_ltr_ignore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pmc_core_send_ltr_ignore(struct pmc_dev *pmcdev, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:463
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_write
  - drivers/platform/x86/intel/pmc/cnp.c:cnp_core_init
  - drivers/platform/x86/intel/pmc/tgl.c:tgl_core_init
  - drivers/platform/x86/intel/pmc/adl.c:adl_core_init
  - drivers/platform/x86/intel/pmc/mtl.c:mtl_core_init
```
**Symbols:**

```
ffffffff8212b5fb-ffffffff8212b614: pmc_core_send_ltr_ignore.cold (STB_LOCAL)
ffffffff81ddc540-ffffffff81ddc654: pmc_core_send_ltr_ignore (STB_GLOBAL)
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
