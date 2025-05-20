# Function: <code>spi_message_init_with_transfers</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff815eee14)
Location: include/linux/spi/spi.h:869
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81602f8c)
Location: include/linux/spi/spi.h:904
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff8166b35c)
Location: include/linux/spi/spi.h:904
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
In drivers/tty/serial/max310x.c (ffffffff8163f964)
Location: include/linux/spi/spi.h:900
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816a6e54)
Location: include/linux/spi/spi.h:900
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff8165db74)
Location: include/linux/spi/spi.h:898
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c78b4)
Location: include/linux/spi/spi.h:898
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff81692804)
Location: include/linux/spi/spi.h:948
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81702b64)
Location: include/linux/spi/spi.h:948
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff816b53a4)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81726eb4)
Location: include/linux/spi/spi.h:951
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff817681f8)
Location: include/linux/spi/spi.h:1059
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817e347f)
Location: include/linux/spi/spi.h:1059
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff8178303b)
Location: include/linux/spi/spi.h:1084
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817f80df)
Location: include/linux/spi/spi.h:1084
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff81766932)
Location: include/linux/spi/spi.h:1074
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817dc874)
Location: include/linux/spi/spi.h:1074
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff817eb302)
Location: include/linux/spi/spi.h:1078
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81868274)
Location: include/linux/spi/spi.h:1078
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff8192b90f)
Location: include/linux/spi/spi.h:1069
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff819b0c44)
Location: include/linux/spi/spi.h:1069
Inline: True
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b24b54)
Location: include/linux/spi/spi.h:1148
Inline: True
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
In drivers/base/regmap/regmap-spi.c (ffffffff81b74c54)
Location: include/linux/spi/spi.h:1178
Inline: True
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
In drivers/base/regmap/regmap-spi.c (ffffffff81bc8ad4)
Location: include/linux/spi/spi.h:1222
Inline: True
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
In drivers/tty/serial/max310x.c (ffff800010898b58)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffff80001091c10c)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/mfd/stmpe-spi.c (ffff800010930414)
Location: include/linux/spi/spi.h:951
Inline: True
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
In drivers/tty/serial/max310x.c (c0994424)
Location: include/linux/spi/spi.h:951
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (c0a01904)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/mfd/stmpe-spi.c (c0a119b4)
Location: include/linux/spi/spi.h:951
Inline: True
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
In drivers/tty/serial/max310x.c (0)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (c0000000009c0934)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/mfd/stmpe-spi.c (c0000000009d0434)
Location: include/linux/spi/spi.h:951
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffe00055b644)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffe00059bbc8)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6b7c)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a048)
Location: include/linux/spi/spi.h:951
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff8167ae04)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816ecc94)
Location: include/linux/spi/spi.h:951
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff81659ef4)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c72d4)
Location: include/linux/spi/spi.h:951
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff816a91e4)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff8171a374)
Location: include/linux/spi/spi.h:951
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff816c3644)
Location: include/linux/spi/spi.h:951
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817356d4)
Location: include/linux/spi/spi.h:951
Inline: True
```
</details>
</li>
</ul>

## Differences
