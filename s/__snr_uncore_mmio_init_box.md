# Function: <code>__snr_uncore_mmio_init_box</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __snr_uncore_mmio_init_box(struct intel_uncore_box *box, unsigned int box_ctl, int mem_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e310)
Location: arch/x86/events/intel/uncore_snbep.c:4420
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
**Symbols:**

```
ffffffff8101e310-ffffffff8101e3f5: __snr_uncore_mmio_init_box (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __snr_uncore_mmio_init_box(struct intel_uncore_box *box, unsigned int box_ctl, int mem_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: arch/x86/events/intel/uncore_snbep.c:4667
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
**Symbols:**

```
ffffffff8101e930-ffffffff8101ea37: __snr_uncore_mmio_init_box (STB_LOCAL)
ffffffff81bd2637-ffffffff81bd264f: __snr_uncore_mmio_init_box.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __snr_uncore_mmio_init_box(struct intel_uncore_box *box, unsigned int box_ctl, int mem_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: arch/x86/events/intel/uncore_snbep.c:4692
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
**Symbols:**

```
ffffffff8101fdd0-ffffffff8101fed9: __snr_uncore_mmio_init_box (STB_LOCAL)
ffffffff81bc4829-ffffffff81bc4841: __snr_uncore_mmio_init_box.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023845)
Location: arch/x86/events/intel/uncore_snbep.c:4869
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81027675)
Location: arch/x86/events/intel/uncore_snbep.c:4869
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102d6e5)
Location: arch/x86/events/intel/uncore_snbep.c:5125
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102da65)
Location: arch/x86/events/intel/uncore_snbep.c:5115
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81033a95)
Location: arch/x86/events/intel/uncore_snbep.c:5123
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
