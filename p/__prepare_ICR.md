# Function: <code>__prepare_ICR</code>

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
In arch/x86/kernel/apic/ipi.c (ffffffff81054b75)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810593f0)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d2a)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a5ae)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/apic/probe_64.c (ffffffff8105a8f3)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
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
In arch/x86/kernel/apic/ipi.c (ffffffff81054d3c)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d25)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest
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
In arch/x86/kernel/apic/ipi.c (ffffffff81057afc)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cae5)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest
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
In arch/x86/kernel/apic/ipi.c (ffffffff8105727c)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c225)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest
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
In arch/x86/kernel/apic/ipi.c (ffffffff8105af0c)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81060185)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
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
In arch/x86/kernel/apic/ipi.c (ffffffff8105df0c)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106306f)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff81063b9c)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068e4f)
Location: arch/x86/include/asm/ipi.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff8106725f)
Location: arch/x86/include/asm/ipi.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c66f)
Location: arch/x86/include/asm/ipi.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff81067d5e)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106de35)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff8106eaae)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810752e5)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff8106ff2e)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075945)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff81070a7e)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810763e5)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff8107c6fe)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083a35)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff8108babe)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093a15)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff8109ff3e)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a9145)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff810a2ebe)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac305)
Location: arch/x86/kernel/apic/local.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff810a9ddf)
Location: arch/x86/kernel/apic/local.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2ec5)
Location: arch/x86/kernel/apic/local.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8106784e)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cdd5)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057bbe)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105d0f5)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff81067cfe)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d285)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/ipi.c (ffffffff810692de)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f505)
Location: arch/x86/kernel/apic/local.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
</details>
</li>
</ul>

## Differences
