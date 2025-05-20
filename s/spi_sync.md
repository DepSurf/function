# Function: <code>spi_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e8410)
Location: drivers/spi/spi.c:2426
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:spi_write
  - drivers/mfd/tps65912-spi.c:tps65912_spi_write
  - drivers/mfd/tps65912-spi.c:tps65912_spi_read
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
```
**Symbols:**

```
ffffffff815e8410-ffffffff815e8422: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81646cd0)
Location: drivers/spi/spi.c:2896
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:spi_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
```
**Symbols:**

```
ffffffff81646cd0-ffffffff81646d1e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81677dc0)
Location: drivers/spi/spi.c:2923
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
```
**Symbols:**

```
ffffffff81677dc0-ffffffff81677e0e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168c4a0)
Location: drivers/spi/spi.c:3086
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
```
**Symbols:**

```
ffffffff8168c4a0-ffffffff8168c4ee: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f5e50)
Location: drivers/spi/spi.c:3156
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
```
**Symbols:**

```
ffffffff816f5e50-ffffffff816f5e9e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817338f0)
Location: drivers/spi/spi.c:3156
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff817338f0-ffffffff8173393e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81756360)
Location: drivers/spi/spi.c:3255
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81756360-ffffffff817563ae: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81792410)
Location: drivers/spi/spi.c:3484
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81792410-ffffffff8179245e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b5fe0)
Location: drivers/spi/spi.c:3488
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff817b5fe0-ffffffff817b602e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187cfa7)
Location: drivers/spi/spi.c:3778
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff8187ce10-ffffffff8187ce5e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8188b957)
Location: drivers/spi/spi.c:3874
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff8188b7c0-ffffffff8188b80e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186e2c2)
Location: drivers/spi/spi.c:3921
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff8186e120-ffffffff8186e16e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fe362)
Location: drivers/spi/spi.c:3979
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff818fe1c0-ffffffff818fe20e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4fb1f)
Location: drivers/spi/spi.c:3979
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81a4f940-ffffffff81a4f996: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd7538)
Location: drivers/spi/spi.c:4240
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81bd7330-ffffffff81bd7386: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2df5f)
Location: drivers/spi/spi.c:4295
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81c2dd60-ffffffff81c2ddb6: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce09af)
Location: drivers/spi/spi.c:4462
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_write_then_read
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff81ce07b0-ffffffff81ce0806: spi_sync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c99f8)
Location: drivers/spi/spi.c:3488
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffff8000109c99f8-ffff8000109c9a4c: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab348c)
Location: drivers/spi/spi.c:3488
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
c0ab348c-c0ab34d8: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a8b6a0)
Location: drivers/spi/spi.c:3488
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
c000000000a8b6a0-c000000000a8b710: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000619a44)
Location: drivers/spi/spi.c:3488
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffe000619a44-ffffffe000619a9a: spi_sync (STB_GLOBAL)
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
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8177aac0)
Location: drivers/spi/spi.c:3488
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff8177aac0-ffffffff8177ab0e: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8175a870)
Location: drivers/spi/spi.c:3488
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff8175a870-ffffffff8175a8be: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817aae60)
Location: drivers/spi/spi.c:3488
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff817aae60-ffffffff817aaeae: spi_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int spi_sync(struct spi_device *spi, struct spi_message *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c4df0)
Location: drivers/spi/spi.c:3488
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/mfd/ezx-pcap.c:ezx_pcap_putget
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
**Symbols:**

```
ffffffff817c4df0-ffffffff817c4e3e: spi_sync (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
