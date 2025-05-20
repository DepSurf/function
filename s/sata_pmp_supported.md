# Function: <code>sata_pmp_supported</code>

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
Location: include/linux/libata.h:1388
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1388
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1388
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
Location: include/linux/libata.h:1364
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1364
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1364
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
Location: include/linux/libata.h:1370
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1370
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1370
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
Location: include/linux/libata.h:1373
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1373
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1373
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
Location: include/linux/libata.h:1374
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1374
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1374
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
In drivers/ata/libata-core.c (ffffffff817122ee)
Location: include/linux/libata.h:1378
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffffffff8171d7d0)
Location: include/linux/libata.h:1378
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffffffff81725cb0)
Location: include/linux/libata.h:1378
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff8173478e)
Location: include/linux/libata.h:1377
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffffffff817400b0)
Location: include/linux/libata.h:1377
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffffffff81748470)
Location: include/linux/libata.h:1377
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff817700ec)
Location: include/linux/libata.h:1362
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffffffff8177bed3)
Location: include/linux/libata.h:1362
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffffffff817842b0)
Location: include/linux/libata.h:1362
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff8179414c)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffffffff8179fa43)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffffffff817a7f20)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-eh.c (ffffffff81864430)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81868ab5)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
```
In drivers/ata/libata-pmp.c (ffffffff8186d900)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-eh.c (ffffffff81873230)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff818778c5)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
```
In drivers/ata/libata-pmp.c (ffffffff8187c5d0)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-eh.c (ffffffff8185584d)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff8185a0a5)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
```
In drivers/ata/libata-pmp.c (ffffffff8185ee40)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-eh.c (ffffffff818e3d83)
Location: include/linux/libata.h:1436
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff818e8b95)
Location: include/linux/libata.h:1436
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
```
In drivers/ata/libata-pmp.c (ffffffff818edba0)
Location: include/linux/libata.h:1436
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-eh.c (ffffffff81a350fc)
Location: include/linux/libata.h:1422
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81a3a40c)
Location: include/linux/libata.h:1422
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
```
In drivers/ata/libata-pmp.c (ffffffff81a3fd6f)
Location: include/linux/libata.h:1422
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-eh.c (ffffffff81bb9670)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81bbf819)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
```
In drivers/ata/libata-pmp.c (ffffffff81bc5d9f)
Location: include/linux/libata.h:1427
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-eh.c (ffffffff81c11246)
Location: include/linux/libata.h:1446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81c17309)
Location: include/linux/libata.h:1446
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
```
In drivers/ata/libata-pmp.c (ffffffff81c1d8ef)
Location: include/linux/libata.h:1446
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-eh.c (ffffffff81c663e4)
Location: include/linux/libata.h:1442
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81c6c3dc)
Location: include/linux/libata.h:1442
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
```
In drivers/ata/libata-pmp.c (ffffffff81c729df)
Location: include/linux/libata.h:1442
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffff80001099e714)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffff8000109ab484)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffff8000109b486c)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/ata/libahci.c (ffff8000109bbca4)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_softreset
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
In drivers/ata/libata-core.c (c0a6ee14)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (c0a7accc)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (c0a836d0)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/ata/libahci.c (c0a86304)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_softreset
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
In drivers/ata/libata-core.c (c000000000a62aa8)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (c000000000a72250)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (c000000000a7d8f0)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffe0005fe73c)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffffffe000608b8e)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffffffe000610d42)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff8175925c)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffffffff81764b33)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffffffff8176cfe0)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff817390fc)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffffffff81744993)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffffffff8174ce30)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff81788fcc)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffffffff817948c3)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffffffff8179cda0)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
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
In drivers/ata/libata-core.c (ffffffff817a2e1c)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
```
In drivers/ata/libata-eh.c (ffffffff817ae733)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-pmp.c (ffffffff817b6c20)
Location: include/linux/libata.h:1364
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
</details>
</li>
</ul>

## Differences
