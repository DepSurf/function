# Function: <code>dma_request_chan</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8150d3d0)
Location: drivers/dma/dmaengine.c:704
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff8150d3d0-ffffffff8150d5e4: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81539500)
Location: drivers/dma/dmaengine.c:704
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff81539500-ffffffff81539714: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8154cdb0)
Location: drivers/dma/dmaengine.c:704
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff8154cdb0-ffffffff8154cf72: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815b0320)
Location: drivers/dma/dmaengine.c:704
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff815b0320-ffffffff815b04d7: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815e86f0)
Location: drivers/dma/dmaengine.c:704
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff815e86f0-ffffffff815e8922: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81603410)
Location: drivers/dma/dmaengine.c:698
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff81603410-ffffffff81603640: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81635a60)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff81635a60-ffffffff81635cc9: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81657780)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff81657780-ffffffff816579e9: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:801
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff817085f7-ffffffff8170862a: dma_request_chan.cold (STB_LOCAL)
ffffffff81707e70-ffffffff81708138: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:813
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
**Symbols:**

```
ffffffff81c043c2-ffffffff81c043f5: dma_request_chan.cold (STB_LOCAL)
ffffffff817250b0-ffffffff81725375: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:813
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
**Symbols:**

```
ffffffff81bf5e47-ffffffff81bf5e7a: dma_request_chan.cold (STB_LOCAL)
ffffffff81706360-ffffffff81706615: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:813
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
**Symbols:**

```
ffffffff81cf3e3b-ffffffff81cf3e6e: dma_request_chan.cold (STB_LOCAL)
ffffffff81781c20-ffffffff81781ed5: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:812
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
**Symbols:**

```
ffffffff81ebbffa-ffffffff81ebc02d: dma_request_chan.cold (STB_LOCAL)
ffffffff818b8650-ffffffff818b88c9: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a05b50)
Location: drivers/dma/dmaengine.c:813
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
**Symbols:**

```
ffffffff81a05b50-ffffffff81a05dfb: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a4ea10)
Location: drivers/dma/dmaengine.c:813
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
**Symbols:**

```
ffffffff81a4ea10-ffffffff81a4ecbb: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a9a6b0)
Location: drivers/dma/dmaengine.c:813
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
**Symbols:**

```
ffffffff81a9a6b0-ffffffff81a9a95b: dma_request_chan (STB_GLOBAL)
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
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffff8000107fdf80)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
  - drivers/tty/serial/amba-pl011.c:pl011_dma_probe
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
**Symbols:**

```
ffff8000107fdf80-ffff8000107fe1c8: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c091f200)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
  - drivers/tty/serial/amba-pl011.c:pl011_dma_probe
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - sound/soc/soc-generic-dmaengine-pcm.c:snd_dmaengine_pcm_register
```
**Symbols:**

```
c091f200-c091f3d4: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c0000000008c8ae0)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
c0000000008c8ae0-c0000000008c9038: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffe000516a20)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffe000516a20-ffffffe000516bba: dma_request_chan (STB_GLOBAL)
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
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8161d620)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff8161d620-ffffffff8161d889: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81611d10)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff81611d10-ffffffff81611f79: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8164b5c0)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff8164b5c0-ffffffff8164b829: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dma_chan *dma_request_chan(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81665b60)
Location: drivers/dma/dmaengine.c:694
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dma_request_slave_channel
```
**Symbols:**

```
ffffffff81665b60-ffffffff81665dc9: dma_request_chan (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
