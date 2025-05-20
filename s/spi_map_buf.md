# Function: <code>spi_map_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e7770)
Location: drivers/spi/spi.c:683
Inline: True
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff815e7770-ffffffff815e79ec: spi_map_buf.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81645740)
Location: drivers/spi/spi.c:706
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81645740-ffffffff81645a37: spi_map_buf.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81676ee0)
Location: drivers/spi/spi.c:712
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81676ee0-ffffffff8167719e: spi_map_buf.isra.32 (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff8168b5f0)
Location: drivers/spi/spi.c:739
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff8168b5f0-ffffffff8168b889: spi_map_buf.isra.33 (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff816f4f80)
Location: drivers/spi/spi.c:743
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff816f4f80-ffffffff816f51f9: spi_map_buf.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817326d0)
Location: drivers/spi/spi.c:747
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff817326d0-ffffffff81732969: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817550c0)
Location: drivers/spi/spi.c:789
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff817550c0-ffffffff81755377: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817911c0)
Location: drivers/spi/spi.c:806
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff817911c0-ffffffff8179147e: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b4db0)
Location: drivers/spi/spi.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff817b4db0-ffffffff817b507b: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187b9c0)
Location: drivers/spi/spi.c:833
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff8187b9c0-ffffffff8187bc66: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8188aba0)
Location: drivers/spi/spi.c:851
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff8188aba0-ffffffff8188ae05: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186d530)
Location: drivers/spi/spi.c:863
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff8186d530-ffffffff8186d77e: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fd510)
Location: drivers/spi/spi.c:923
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff818fd510-ffffffff818fd766: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4eb50)
Location: drivers/spi/spi.c:963
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff81a4eb50-ffffffff81a4ede7: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd8c30)
Location: drivers/spi/spi.c:1102
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff81bd8c30-ffffffff81bd8c54: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2f620)
Location: drivers/spi/spi.c:1102
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff81c2f620-ffffffff81c2f644: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce24e0)
Location: drivers/spi/spi.c:1172
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff81ce24e0-ffffffff81ce2504: spi_map_buf (STB_GLOBAL)
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
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c84b0)
Location: drivers/spi/spi.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffff8000109c84b0-ffff8000109c876c: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab2080)
Location: drivers/spi/spi.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
c0ab2080-c0ab23bc: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a89c80)
Location: drivers/spi/spi.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
c000000000a89c80-c000000000a8a160: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000618962)
Location: drivers/spi/spi.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffe000618962-ffffffe000618bd6: spi_map_buf (STB_GLOBAL)
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
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81779890)
Location: drivers/spi/spi.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff81779890-ffffffff81779b5b: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81759640)
Location: drivers/spi/spi.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff81759640-ffffffff8175990b: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817a9c30)
Location: drivers/spi/spi.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff817a9c30-ffffffff817a9efb: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int spi_map_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, void *buf, size_t len, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c3ac0)
Location: drivers/spi/spi.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_controller_dma_map_mem_op_data
```
**Symbols:**

```
ffffffff817c3ac0-ffffffff817c3d8b: spi_map_buf (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
