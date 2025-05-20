# Function: <code>readsw</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b2556c)
Location: include/asm-generic/io.h:416
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
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
In drivers/base/regmap/regmap-mmio.c (ffffffff81b75670)
Location: include/asm-generic/io.h:416
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
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
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc95ba)
Location: include/asm-generic/io.h:416
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
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
In lib/logic_pio.c (ffff80001063ea64)
Location: include/asm-generic/io.h:333
Inline: True
```
```
In drivers/ata/libata-sff.c (ffff8000109b0684)
Location: include/asm-generic/io.h:333
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fd150)
Location: include/asm-generic/io.h:333
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e5cec)
Location: arch/powerpc/include/asm/io-defs.h:32
Inline: True
```
</details>
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
