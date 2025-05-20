# Function: <code>dma_async_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff814bdbc0)
Location: drivers/dma/dmaengine.c:838
Inline: False
```
**Symbols:**

```
ffffffff814bdbc0-ffffffff814be093: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8150d870)
Location: drivers/dma/dmaengine.c:915
Inline: False
```
**Symbols:**

```
ffffffff8150d870-ffffffff8150dd2b: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815399a0)
Location: drivers/dma/dmaengine.c:915
Inline: False
```
**Symbols:**

```
ffffffff815399a0-ffffffff81539e8a: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8154d1f0)
Location: drivers/dma/dmaengine.c:916
Inline: False
```
**Symbols:**

```
ffffffff8154d1f0-ffffffff8154d700: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815b0770)
Location: drivers/dma/dmaengine.c:916
Inline: False
```
**Symbols:**

```
ffffffff815b0770-ffffffff815b0d7d: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:916
Inline: False
```
**Symbols:**

```
ffffffff815e934b-ffffffff815e9361: dma_async_device_register.cold.29 (STB_LOCAL)
ffffffff815e8ba0-ffffffff815e91b0: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:911
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffff8160385b-ffffffff81603872: dma_async_device_register.cold.35 (STB_LOCAL)
ffffffff81602950-ffffffff81602ee0: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffff81636115-ffffffff8163628a: dma_async_device_register.cold (STB_LOCAL)
ffffffff81635160-ffffffff816355a9: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffff81657e35-ffffffff81657faa: dma_async_device_register.cold (STB_LOCAL)
ffffffff81656e70-ffffffff816572c5: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1143
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffff8170862a-ffffffff8170879e: dma_async_device_register.cold (STB_LOCAL)
ffffffff81708160-ffffffff81708510: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1139
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffff81c043f5-ffffffff81c04569: dma_async_device_register.cold (STB_LOCAL)
ffffffff81725380-ffffffff81725730: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1140
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81bf5e7a-ffffffff81bf5fee: dma_async_device_register.cold (STB_LOCAL)
ffffffff81706620-ffffffff817069cd: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1140
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81cf3e6e-ffffffff81cf3fe2: dma_async_device_register.cold (STB_LOCAL)
ffffffff81781ee0-ffffffff8178228d: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:1133
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81ebc02d-ffffffff81ebc144: dma_async_device_register.cold (STB_LOCAL)
ffffffff818b88d0-ffffffff818b8c73: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a05e10)
Location: drivers/dma/dmaengine.c:1134
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81a05e10-ffffffff81a062c7: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a4ecd0)
Location: drivers/dma/dmaengine.c:1134
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81a4ecd0-ffffffff81a4f187: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a9a970)
Location: drivers/dma/dmaengine.c:1137
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81a9a970-ffffffff81a9ae27: dma_async_device_register (STB_GLOBAL)
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
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffff8000107fd138)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
**Symbols:**

```
ffff8000107fd138-ffff8000107fd6f8: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c091e718)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
```
**Symbols:**

```
c091e718-c091ecf8: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c0000000008c82c0)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
c0000000008c82c0-c0000000008c8a08: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffe000516dda)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffe000516dda-ffffffe0005172ee: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffff8161dcd5-ffffffff8161de4a: dma_async_device_register.cold (STB_LOCAL)
ffffffff8161cd10-ffffffff8161d165: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffff816123c5-ffffffff8161253a: dma_async_device_register.cold (STB_LOCAL)
ffffffff81611400-ffffffff81611855: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffff8164bc75-ffffffff8164bdea: dma_async_device_register.cold (STB_LOCAL)
ffffffff8164acb0-ffffffff8164b105: dma_async_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dma_async_device_register(struct dma_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (0)
Location: drivers/dma/dmaengine.c:907
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
**Symbols:**

```
ffffffff81666215-ffffffff8166638a: dma_async_device_register.cold (STB_LOCAL)
ffffffff81665250-ffffffff816656a5: dma_async_device_register (STB_GLOBAL)
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
