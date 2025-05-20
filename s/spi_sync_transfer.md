# Function: <code>spi_sync_transfer</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff815eee10)
Location: include/linux/spi/spi.h:1014
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff815eee10-ffffffff815eee84: spi_sync_transfer.constprop.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81602f80)
Location: include/linux/spi/spi.h:1051
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff81602f80-ffffffff8160300b: spi_sync_transfer.constprop.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff8166b350)
Location: include/linux/spi/spi.h:1051
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff8166b350-ffffffff8166b3db: spi_sync_transfer.constprop.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8163f940)
Location: include/linux/spi/spi.h:1047
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816a6e30)
Location: include/linux/spi/spi.h:1047
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff8163f940-ffffffff8163f9ce: spi_sync_transfer.constprop.12 (STB_LOCAL)
ffffffff816a6e30-ffffffff816a6ea9: spi_sync_transfer.constprop.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8165db50)
Location: include/linux/spi/spi.h:1045
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c7890)
Location: include/linux/spi/spi.h:1045
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff8165db50-ffffffff8165dbde: spi_sync_transfer.constprop.13 (STB_LOCAL)
ffffffff816c7890-ffffffff816c7909: spi_sync_transfer.constprop.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816927e0)
Location: include/linux/spi/spi.h:1117
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81702b40)
Location: include/linux/spi/spi.h:1117
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff816927e0-ffffffff8169286e: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffffffff81702b40-ffffffff81702bb9: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816b5380)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81726e90)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff816b5380-ffffffff816b540e: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffffffff81726e90-ffffffff81726f09: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817681f8)
Location: include/linux/spi/spi.h:1231
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817e3460)
Location: include/linux/spi/spi.h:1231
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff817e3460-ffffffff817e34d5: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8178303b)
Location: include/linux/spi/spi.h:1256
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817f80c0)
Location: include/linux/spi/spi.h:1256
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff817f80c0-ffffffff817f8135: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81766932)
Location: include/linux/spi/spi.h:1246
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817dc850)
Location: include/linux/spi/spi.h:1246
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff817dc850-ffffffff817dc8cc: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817eb302)
Location: include/linux/spi/spi.h:1245
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81868250)
Location: include/linux/spi/spi.h:1245
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff81868250-ffffffff818682cc: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8192b90f)
Location: include/linux/spi/spi.h:1225
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff819b0c20)
Location: include/linux/spi/spi.h:1225
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff819b0c20-ffffffff819b0cb4: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81b24b30)
Location: include/linux/spi/spi.h:1305
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff81b24b30-ffffffff81b24bc4: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81b74c30)
Location: include/linux/spi/spi.h:1356
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff81b74c30-ffffffff81b74cc1: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81bc8ab0)
Location: include/linux/spi/spi.h:1402
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff81bc8ab0-ffffffff81bc8b41: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffff800010898b30)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffff80001091c0e8)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
```
In drivers/mfd/stmpe-spi.c (ffff8000109303f0)
Location: include/linux/spi/spi.h:1120
Inline: True
```
**Symbols:**

```
ffff800010898b30-ffff800010898bb8: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffff80001091c0e8-ffff80001091c164: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffff8000109303f0-ffff80001093046c: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (c0994424)
Location: include/linux/spi/spi.h:1120
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (c0a018c4)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/mfd/stmpe-spi.c (c0a11974)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/mfd/stmpe-spi.c:spi_reg_write
```
**Symbols:**

```
c0a018c4-c0a01958: spi_sync_transfer.constprop.0 (STB_LOCAL)
c0a11974-c0a11a08: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/spi/spi.h:1120
Inline: False
```
```
In drivers/base/regmap/regmap-spi.c (c0000000009c08f0)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
```
In drivers/mfd/stmpe-spi.c (c0000000009d03f0)
Location: include/linux/spi/spi.h:1120
Inline: True
```
**Symbols:**

```
c0000000009c08f0-c0000000009c09a8: spi_sync_transfer.constprop.0 (STB_LOCAL)
c0000000009d03f0-c0000000009d04a8: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffe00055b644)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffe00059bbc8)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6b7c)
Location: include/linux/spi/spi.h:1120
Inline: True
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a048)
Location: include/linux/spi/spi.h:1120
Inline: True
```
**Symbols:**

```
ffffffe00055b644-ffffffe00055b6b6: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffffffe0005a6b7c-ffffffe0005a6be6: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffffffe00071a048-ffffffe00071a0b2: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffffffe00059bbc8-ffffffe00059bc32: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8167ade0)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816ecc70)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff8167ade0-ffffffff8167ae6e: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffffffff816ecc70-ffffffff816ecce9: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81659ed0)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c72b0)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff81659ed0-ffffffff81659f5e: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffffffff816c72b0-ffffffff816c7329: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816a91c0)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff8171a350)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff816a91c0-ffffffff816a924e: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffffffff8171a350-ffffffff8171a3c9: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816c3620)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817356b0)
Location: include/linux/spi/spi.h:1120
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:spi_write
```
**Symbols:**

```
ffffffff816c3620-ffffffff816c36ae: spi_sync_transfer.constprop.0 (STB_LOCAL)
ffffffff817356b0-ffffffff81735729: spi_sync_transfer.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
