# Function: <code>ata_port_is_dummy</code>

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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1102
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1102
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1078
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1078
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1084
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1084
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1085
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1085
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1086
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/libata.h:1086
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
In drivers/ata/libata-core.c (ffffffff8170d7f5)
Location: include/linux/libata.h:1088
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81722fa4)
Location: include/linux/libata.h:1088
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff8172fc5b)
Location: include/linux/libata.h:1088
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81745373)
Location: include/linux/libata.h:1088
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff81771e33)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff81781070)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff81795de6)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff817a5178)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff81859f68)
Location: include/linux/libata.h:1065
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff8186a138)
Location: include/linux/libata.h:1065
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff81c17f7b)
Location: include/linux/libata.h:1065
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff81878f48)
Location: include/linux/libata.h:1065
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff81c09d73)
Location: include/linux/libata.h:1065
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff8185b5bc)
Location: include/linux/libata.h:1065
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff818d89c6)
Location: include/linux/libata.h:1071
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff818ea0ec)
Location: include/linux/libata.h:1071
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff81a29b6a)
Location: include/linux/libata.h:1044
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_start
```
```
In drivers/ata/libata-sff.c (ffffffff81a3b9ba)
Location: include/linux/libata.h:1044
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff81bac6c0)
Location: include/linux/libata.h:1041
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_start
```
```
In drivers/ata/libata-sff.c (ffffffff81bc1c51)
Location: include/linux/libata.h:1041
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff81c03850)
Location: include/linux/libata.h:1055
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_start
```
```
In drivers/ata/libata-sff.c (ffffffff81c19551)
Location: include/linux/libata.h:1055
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff81c5902e)
Location: include/linux/libata.h:1054
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_start
```
```
In drivers/ata/libata-sff.c (ffffffff81c6e641)
Location: include/linux/libata.h:1054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffff80001099ee18)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffff8000109b1750)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
```
In drivers/ata/libahci.c (ffff8000109b9b60)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_init_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6f4e0)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (c0a804b4)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
```
In drivers/ata/libahci.c (c0a87330)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_init_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a6331c)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (c000000000a796d0)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fed22)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffe00060e01a)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
</details>
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
In drivers/ata/libata-core.c (ffffffff8175aefd)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff8176a238)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff8173ad9d)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff8174a098)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff8178ac66)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff81799ff8)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
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
In drivers/ata/libata-core.c (ffffffff817a4ab6)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sff.c (ffffffff817b3e78)
Location: include/linux/libata.h:1072
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
</details>
</li>
</ul>

## Differences
