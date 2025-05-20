# Function: <code>mmio_config_writel</code>

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
In arch/x86/pci/mmconfig_64.c (ffffffff816f67e0)
Location: arch/x86/include/asm/pci_x86.h:191
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff816fa3d8)
Location: arch/x86/include/asm/pci_x86.h:191
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff8175b468)
Location: arch/x86/include/asm/pci_x86.h:193
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff8175f150)
Location: arch/x86/include/asm/pci_x86.h:193
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff817879d8)
Location: arch/x86/include/asm/pci_x86.h:193
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff8178b680)
Location: arch/x86/include/asm/pci_x86.h:193
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff817a6b08)
Location: arch/x86/include/asm/pci_x86.h:195
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff817aa620)
Location: arch/x86/include/asm/pci_x86.h:195
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff8181dd68)
Location: arch/x86/include/asm/pci_x86.h:197
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff81821af0)
Location: arch/x86/include/asm/pci_x86.h:197
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff81867fd4)
Location: arch/x86/include/asm/pci_x86.h:199
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff8186bdc4)
Location: arch/x86/include/asm/pci_x86.h:199
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff81888054)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff8188bea4)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff818d295a)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff818d67fb)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff81904d0a)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff81908b7b)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff81bb52ca)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff81bb94cb)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff81bca4da)
Location: arch/x86/include/asm/pci_x86.h:217
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff81bcddb0)
Location: arch/x86/include/asm/pci_x86.h:217
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff81bbde25)
Location: arch/x86/include/asm/pci_x86.h:217
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff81bc176f)
Location: arch/x86/include/asm/pci_x86.h:217
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff81c8dd65)
Location: arch/x86/include/asm/pci_x86.h:217
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff81c91d3f)
Location: arch/x86/include/asm/pci_x86.h:217
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff81e3cd10)
Location: arch/x86/include/asm/pci_x86.h:233
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff81e4125c)
Location: arch/x86/include/asm/pci_x86.h:233
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff82015fe0)
Location: arch/x86/include/asm/pci_x86.h:233
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff8201b7dc)
Location: arch/x86/include/asm/pci_x86.h:233
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff820963b2)
Location: arch/x86/include/asm/pci_x86.h:233
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff8209be3e)
Location: arch/x86/include/asm/pci_x86.h:233
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff8216d8c2)
Location: arch/x86/include/asm/pci_x86.h:233
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff821735ee)
Location: arch/x86/include/asm/pci_x86.h:233
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff818a413a)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff818a7f3b)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff8185f8aa)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff81862a5b)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff818f572a)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff818f959b)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
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
In arch/x86/pci/mmconfig_64.c (ffffffff81916823)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
```
```
In arch/x86/pci/numachip.c (ffffffff8191a6e3)
Location: arch/x86/include/asm/pci_x86.h:206
Inline: True
Inline callers:
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
```
</details>
</li>
</ul>

## Differences
