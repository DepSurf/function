# Function: <code>gen_pool_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81046f6e)
Location: include/linux/genalloc.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b5d79)
Location: include/linux/genalloc.h:94
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81047172)
Location: include/linux/genalloc.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505729)
Location: include/linux/genalloc.h:110
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81048d12)
Location: include/linux/genalloc.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529919)
Location: include/linux/genalloc.h:110
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff810486a3)
Location: include/linux/genalloc.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c429)
Location: include/linux/genalloc.h:110
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff8104c0d3)
Location: include/linux/genalloc.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159ef79)
Location: include/linux/genalloc.h:112
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff8104edc2)
Location: include/linux/genalloc.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6c9e)
Location: include/linux/genalloc.h:112
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104c492)
Location: include/linux/genalloc.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f158b)
Location: include/linux/genalloc.h:113
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104f3b3)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81623387)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fd33)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644e57)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81054243)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f242b)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810531a3)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f7eb)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81054a93)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f10bb)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105d3e3)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176b1cb)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81069924)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189fdc6)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81079624)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e91d3)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8107b8d4)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a318e3)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81082d94)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7cd53)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffff8000107b0ac8)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080fa6c)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff800010810764)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
```
</details>
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fe33)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8103f393)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fce3)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81638c97)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81051123)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652fe7)
Location: include/linux/genalloc.h:119
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
</details>
</li>
</ul>

## Differences
