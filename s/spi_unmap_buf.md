# Function: <code>spi_unmap_buf</code>

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
In drivers/spi/spi.c (ffffffff815e7110)
Location: drivers/spi/spi.c:743
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff815e7110-ffffffff815e7168: spi_unmap_buf.isra.26 (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff81645a40)
Location: drivers/spi/spi.c:768
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81645a40-ffffffff81645a98: spi_unmap_buf.isra.29 (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff81676840)
Location: drivers/spi/spi.c:787
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81676840-ffffffff81676898: spi_unmap_buf.isra.31 (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff8168af40)
Location: drivers/spi/spi.c:814
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff8168af40-ffffffff8168af94: spi_unmap_buf.isra.32 (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff816f48b0)
Location: drivers/spi/spi.c:818
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff816f48b0-ffffffff816f4906: spi_unmap_buf.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81732970)
Location: drivers/spi/spi.c:828
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81732970-ffffffff817329ca: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81755380)
Location: drivers/spi/spi.c:870
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81755380-ffffffff817553ee: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81791480)
Location: drivers/spi/spi.c:887
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81791480-ffffffff817914eb: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b5080)
Location: drivers/spi/spi.c:888
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff817b5080-ffffffff817b50eb: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187bc70)
Location: drivers/spi/spi.c:914
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_map_msg
```
**Symbols:**

```
ffffffff8187bc70-ffffffff8187bcdf: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8188b079)
Location: drivers/spi/spi.c:932
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_msg
```
**Symbols:**

```
ffffffff8188ba30-ffffffff8188ba68: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186d9e9)
Location: drivers/spi/spi.c:944
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_msg
```
**Symbols:**

```
ffffffff8186e390-ffffffff8186e3c8: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fda18)
Location: drivers/spi/spi.c:1004
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_msg
```
**Symbols:**

```
ffffffff818fe430-ffffffff818fe468: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4f088)
Location: drivers/spi/spi.c:1044
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_msg
```
**Symbols:**

```
ffffffff81a4fc00-ffffffff81a4fc54: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd8c70)
Location: drivers/spi/spi.c:1122
Inline: False
```
**Symbols:**

```
ffffffff81bd8c70-ffffffff81bd8ccc: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2f660)
Location: drivers/spi/spi.c:1122
Inline: False
```
**Symbols:**

```
ffffffff81c2f660-ffffffff81c2f6bc: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce2520)
Location: drivers/spi/spi.c:1192
Inline: False
```
**Symbols:**

```
ffffffff81ce2520-ffffffff81ce257c: spi_unmap_buf (STB_GLOBAL)
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
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c8770)
Location: drivers/spi/spi.c:888
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffff8000109c8770-ffff8000109c8814: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab23bc)
Location: drivers/spi/spi.c:888
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
c0ab23bc-c0ab2450: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a8a160)
Location: drivers/spi/spi.c:888
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
c000000000a8a160-c000000000a8a220: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000618bd6)
Location: drivers/spi/spi.c:888
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffe000618bd6-ffffffe000618c5c: spi_unmap_buf (STB_GLOBAL)
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
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81779b60)
Location: drivers/spi/spi.c:888
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81779b60-ffffffff81779bcb: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81759910)
Location: drivers/spi/spi.c:888
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81759910-ffffffff8175997b: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817a9f00)
Location: drivers/spi/spi.c:888
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff817a9f00-ffffffff817a9f6b: spi_unmap_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void spi_unmap_buf(struct spi_controller *ctlr, struct device *dev, struct sg_table *sgt, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c3d90)
Location: drivers/spi/spi.c:888
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff817c3d90-ffffffff817c3dfb: spi_unmap_buf (STB_GLOBAL)
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
