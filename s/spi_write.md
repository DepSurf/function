# Function: <code>spi_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff8156ae00)
Location: include/linux/spi/spi.h:860
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff8156ae00-ffffffff8156ae8c: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff815bf9d0)
Location: include/linux/spi/spi.h:995
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff815bf9d0-ffffffff815bfa6c: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff815eee99)
Location: include/linux/spi/spi.h:1037
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
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
In drivers/base/regmap/regmap-spi.c (ffffffff81603019)
Location: include/linux/spi/spi.h:1074
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
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
In drivers/base/regmap/regmap-spi.c (ffffffff8166b3e9)
Location: include/linux/spi/spi.h:1074
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff816a6ed4)
Location: include/linux/spi/spi.h:1070
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff816c7910)
Location: include/linux/spi/spi.h:1068
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff816c7910-ffffffff816c795f: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81702bc0)
Location: include/linux/spi/spi.h:1140
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff81702bc0-ffffffff81702c0f: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81726f10)
Location: include/linux/spi/spi.h:1143
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff81726f10-ffffffff81726f5f: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff817e34e0)
Location: include/linux/spi/spi.h:1254
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff817e34e0-ffffffff817e353b: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff817f8140)
Location: include/linux/spi/spi.h:1279
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff817f8140-ffffffff817f819e: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff817dc8d0)
Location: include/linux/spi/spi.h:1269
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff817dc8d0-ffffffff817dc92e: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff818682d0)
Location: include/linux/spi/spi.h:1268
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff818682d0-ffffffff8186832e: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff819b0cc0)
Location: include/linux/spi/spi.h:1248
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff819b0cc0-ffffffff819b0d2d: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81b24be0)
Location: include/linux/spi/spi.h:1328
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff81b24be0-ffffffff81b24c4d: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81b74ce0)
Location: include/linux/spi/spi.h:1379
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff81b74ce0-ffffffff81b74d47: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81bc8b60)
Location: include/linux/spi/spi.h:1425
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff81bc8b60-ffffffff81bc8bc7: spi_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffff80001091c168)
Location: include/linux/spi/spi.h:1143
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/mfd/stmpe-spi.c (ffff800010930470)
Location: include/linux/spi/spi.h:1143
Inline: True
Direct callers:
  - drivers/mfd/stmpe-spi.c:spi_init
  - drivers/mfd/stmpe-spi.c:spi_block_write
```
**Symbols:**

```
ffff80001091c168-ffff80001091c1d4: spi_write (STB_LOCAL)
ffff800010930470-ffff8000109304e0: spi_write.constprop.0 (STB_LOCAL)
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
In drivers/base/regmap/regmap-spi.c (c0a0199c)
Location: include/linux/spi/spi.h:1143
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/mfd/stmpe-spi.c (c0a11a54)
Location: include/linux/spi/spi.h:1143
Inline: True
Inline callers:
  - drivers/mfd/stmpe-spi.c:spi_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (c0000000009c09b0)
Location: include/linux/spi/spi.h:1143
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/mfd/stmpe-spi.c (c0000000009d04b0)
Location: include/linux/spi/spi.h:1143
Inline: True
Direct callers:
  - drivers/mfd/stmpe-spi.c:spi_init
  - drivers/mfd/stmpe-spi.c:spi_block_write
```
**Symbols:**

```
c0000000009c09b0-c0000000009c0a48: spi_write (STB_LOCAL)
c0000000009d04b0-c0000000009d0540: spi_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffe00059bc32)
Location: include/linux/spi/spi.h:1143
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/mfd/stmpe-spi.c (ffffffe0005a6be6)
Location: include/linux/spi/spi.h:1143
Inline: True
Direct callers:
  - drivers/mfd/stmpe-spi.c:spi_init
  - drivers/mfd/stmpe-spi.c:spi_block_write
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a0b2)
Location: include/linux/spi/spi.h:1143
Inline: True
Direct callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_set_ios
  - drivers/mmc/host/mmc_spi.c:mmc_spi_set_ios
```
**Symbols:**

```
ffffffe0005a6be6-ffffffe0005a6c42: spi_write.constprop.0 (STB_LOCAL)
ffffffe00071a0b2-ffffffe00071a10e: spi_write.constprop.0 (STB_LOCAL)
ffffffe00059bc32-ffffffe00059bc8c: spi_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff816eccf0)
Location: include/linux/spi/spi.h:1143
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff816eccf0-ffffffff816ecd3f: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff816c7330)
Location: include/linux/spi/spi.h:1143
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff816c7330-ffffffff816c737f: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff8171a3d0)
Location: include/linux/spi/spi.h:1143
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff8171a3d0-ffffffff8171a41f: spi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int spi_write(struct spi_device *spi, const void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81735730)
Location: include/linux/spi/spi.h:1143
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
**Symbols:**

```
ffffffff81735730-ffffffff8173577f: spi_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
