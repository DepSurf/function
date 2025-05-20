# Function: <code>snr_uncore_mmio_map</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int snr_uncore_mmio_map(struct intel_uncore_box *box, unsigned int box_ctl, int mem_offset, unsigned int device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: arch/x86/events/intel/uncore_snbep.c:4840
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
**Symbols:**

```
ffffffff810232d0-ffffffff810233c5: snr_uncore_mmio_map (STB_LOCAL)
ffffffff81c96c43-ffffffff81c96c5d: snr_uncore_mmio_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int snr_uncore_mmio_map(struct intel_uncore_box *box, unsigned int box_ctl, int mem_offset, unsigned int device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: arch/x86/events/intel/uncore_snbep.c:4840
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
**Symbols:**

```
ffffffff810270d0-ffffffff810271dc: snr_uncore_mmio_map (STB_LOCAL)
ffffffff81e460bb-ffffffff81e460d5: snr_uncore_mmio_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int snr_uncore_mmio_map(struct intel_uncore_box *box, unsigned int box_ctl, int mem_offset, unsigned int device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102cb80)
Location: arch/x86/events/intel/uncore_snbep.c:5094
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
**Symbols:**

```
ffffffff8102cb80-ffffffff8102ccaa: snr_uncore_mmio_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int snr_uncore_mmio_map(struct intel_uncore_box *box, unsigned int box_ctl, int mem_offset, unsigned int device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102cdc0)
Location: arch/x86/events/intel/uncore_snbep.c:5084
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
**Symbols:**

```
ffffffff8102cdc0-ffffffff8102ceea: snr_uncore_mmio_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int snr_uncore_mmio_map(struct intel_uncore_box *box, unsigned int box_ctl, int mem_offset, unsigned int device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81032f20)
Location: arch/x86/events/intel/uncore_snbep.c:5092
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
**Symbols:**

```
ffffffff81032f20-ffffffff8103304a: snr_uncore_mmio_map (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
