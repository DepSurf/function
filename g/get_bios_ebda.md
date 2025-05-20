# Function: <code>get_bios_ebda</code>

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
In arch/x86/kernel/head.c (ffffffff81f59667)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/head.c:reserve_ebda_region
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f70f3a)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f76424)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
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
In arch/x86/kernel/ebda.c (ffffffff81f815f3)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f9966c)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9eb7b)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
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
In arch/x86/kernel/ebda.c (ffffffff81fbd5f3)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff81fd4b42)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fda0fe)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
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
In arch/x86/kernel/ebda.c (ffffffff8209d5f1)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff820b5803)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bb07c)
Location: arch/x86/include/asm/bios_ebda.h:9
Inline: True
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
In arch/x86/kernel/ebda.c (ffffffff826a358e)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff826bbff5)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c1a5d)
Location: arch/x86/include/asm/bios_ebda.h:10
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
In arch/x86/kernel/ebda.c (ffffffff826cc58d)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff826e5da3)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826eb93b)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
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
In arch/x86/kernel/ebda.c (ffffffff82882598)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff8289c8e4)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a253d)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
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
In arch/x86/kernel/ebda.c (ffffffff82899526)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b46ba)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bab49)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
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
In arch/x86/kernel/ebda.c (ffffffff8289c526)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b7b13)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c100b)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
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
In arch/x86/kernel/ebda.c (ffffffff82cc25fb)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff82cdcc4d)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
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
In arch/x86/kernel/ebda.c (ffffffff82fae66e)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff82fc8fe1)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
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
In arch/x86/kernel/ebda.c (ffffffff831b866e)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff831d3923)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
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
In arch/x86/kernel/ebda.c (ffffffff83298744)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff832b6487)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
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
In arch/x86/kernel/ebda.c (ffffffff834467e3)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff83467ed5)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
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
In arch/x86/kernel/ebda.c (ffffffff83e5fa1f)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff83e8c1ab)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
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
In arch/x86/kernel/ebda.c (ffffffff83694bef)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff836af9bb)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
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
In arch/x86/kernel/ebda.c (ffffffff838c4adf)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff838dff2b)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
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
In arch/x86/kernel/ebda.c (ffffffff8288a526)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff828a5b1a)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828abfe1)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
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
In arch/x86/kernel/ebda.c (ffffffff828884ca)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff8289dc5c)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a42a8)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
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
In arch/x86/kernel/ebda.c (ffffffff8289d526)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b8a2a)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828beee0)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
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
In arch/x86/kernel/ebda.c (ffffffff8289d526)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b8b2b)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c202d)
Location: arch/x86/include/asm/bios_ebda.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
```
</details>
</li>
</ul>

## Differences
