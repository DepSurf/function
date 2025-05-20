# Function: <code>uncore_mmio_box_ctl</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c24d)
Location: arch/x86/events/intel/uncore.h:199
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cbcd)
Location: arch/x86/events/intel/uncore.h:199
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e443)
Location: arch/x86/events/intel/uncore.h:200
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ea83)
Location: arch/x86/events/intel/uncore.h:237
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ff23)
Location: arch/x86/events/intel/uncore.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023428)
Location: arch/x86/events/intel/uncore.h:251
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff810234c5)
Location: arch/x86/events/intel/uncore.h:251
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_mmio_enable_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_mmio_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81027248)
Location: arch/x86/events/intel/uncore.h:251
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff810281f5)
Location: arch/x86/events/intel/uncore.h:267
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_mmio_enable_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_mmio_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102cd38)
Location: arch/x86/events/intel/uncore.h:267
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028225)
Location: arch/x86/events/intel/uncore.h:270
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_mmio_enable_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_mmio_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102cf78)
Location: arch/x86/events/intel/uncore.h:270
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102e385)
Location: arch/x86/events/intel/uncore.h:270
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_mmio_enable_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_mmio_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810330d8)
Location: arch/x86/events/intel/uncore.h:270
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cbcd)
Location: arch/x86/events/intel/uncore.h:199
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c2bd)
Location: arch/x86/events/intel/uncore.h:199
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cb8d)
Location: arch/x86/events/intel/uncore.h:199
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cffd)
Location: arch/x86/events/intel/uncore.h:199
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
</details>
</li>
</ul>

## Differences
