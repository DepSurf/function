# Function: <code>cpu_show_common</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81043cd5)
Location: arch/x86/kernel/cpu/bugs.c:798
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81045695)
Location: arch/x86/kernel/cpu/bugs.c:1130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047350)
Location: arch/x86/kernel/cpu/bugs.c:1363
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
**Symbols:**

```
ffffffff81047350-ffffffff810477e3: cpu_show_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047ad0)
Location: arch/x86/kernel/cpu/bugs.c:1524
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
**Symbols:**

```
ffffffff81047ad0-ffffffff81048023: cpu_show_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c785)
Location: arch/x86/kernel/cpu/bugs.c:1651
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_srbds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104bca5)
Location: arch/x86/kernel/cpu/bugs.c:1659
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_srbds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d7d5)
Location: arch/x86/kernel/cpu/bugs.c:1659
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_srbds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
```
**Symbols:**

```
ffffffff8104c9c0-ffffffff8104cd4b: cpu_show_common.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054eb5)
Location: arch/x86/kernel/cpu/bugs.c:1835
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_srbds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
**Symbols:**

```
ffffffff81054130-ffffffff810543b4: cpu_show_common.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060ee5)
Location: arch/x86/kernel/cpu/bugs.c:2387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_retbleed
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
  - arch/x86/kernel/cpu/bugs.c:cpu_show_srbds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f750)
Location: arch/x86/kernel/cpu/bugs.c:2437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_retbleed
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
  - arch/x86/kernel/cpu/bugs.c:cpu_show_srbds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81071305)
Location: arch/x86/kernel/cpu/bugs.c:2728
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_gds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_rstack_overflow
  - arch/x86/kernel/cpu/bugs.c:cpu_show_retbleed
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
  - arch/x86/kernel/cpu/bugs.c:cpu_show_srbds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81078ac5)
Location: arch/x86/kernel/cpu/bugs.c:2888
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_reg_file_data_sampling
  - arch/x86/kernel/cpu/bugs.c:cpu_show_gds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_rstack_overflow
  - arch/x86/kernel/cpu/bugs.c:cpu_show_retbleed
  - arch/x86/kernel/cpu/bugs.c:cpu_show_srbds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
```
**Symbols:**

```
ffffffff81077240-ffffffff8107769a: cpu_show_common.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047c40)
Location: arch/x86/kernel/cpu/bugs.c:1524
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
**Symbols:**

```
ffffffff81047c40-ffffffff81048193: cpu_show_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81036f50)
Location: arch/x86/kernel/cpu/bugs.c:1524
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
**Symbols:**

```
ffffffff81036f50-ffffffff810374a3: cpu_show_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047a80)
Location: arch/x86/kernel/cpu/bugs.c:1524
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
**Symbols:**

```
ffffffff81047a80-ffffffff81047fd3: cpu_show_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048e90)
Location: arch/x86/kernel/cpu/bugs.c:1524
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
  - arch/x86/kernel/cpu/bugs.c:cpu_show_l1tf
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spec_store_bypass
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v1
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
**Symbols:**

```
ffffffff81048e90-ffffffff810493e3: cpu_show_common.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
