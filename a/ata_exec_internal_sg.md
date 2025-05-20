# Function: <code>ata_exec_internal_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cb690)
Location: drivers/ata/libata-core.c:1553
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff815cb690-ffffffff815cbc88: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81623e40)
Location: drivers/ata/libata-core.c:1556
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81623e40-ffffffff81624455: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816549c0)
Location: drivers/ata/libata-core.c:1563
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff816549c0-ffffffff81654ff2: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81668f70)
Location: drivers/ata/libata-core.c:1563
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff81668f70-ffffffff816695b2: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d25d0)
Location: drivers/ata/libata-core.c:1563
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff816d25d0-ffffffff816d2c10: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1563
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff817131d8-ffffffff817131f8: ata_exec_internal_sg.cold.53 (STB_LOCAL)
ffffffff8170ece0-ffffffff8170f260: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1563
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81735688-ffffffff817356a8: ata_exec_internal_sg.cold.54 (STB_LOCAL)
ffffffff81731190-ffffffff81731710: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff817710da-ffffffff817710fa: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff8176c950-ffffffff8176cece: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff817950d8-ffffffff817950f8: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff817909c0-ffffffff81790f3e: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1491
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff81859531-ffffffff81859551: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff818554f0-ffffffff81855a6c: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1491
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff81c17544-ffffffff81c17564: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff81865760-ffffffff81865cdc: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1491
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81c09171-ffffffff81c09191: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff81848200-ffffffff8184877c: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1494
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
```
**Symbols:**

```
ffffffff81d0da78-ffffffff81d0da98: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff818d5250-ffffffff818d57cc: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a25a10)
Location: drivers/ata/libata-core.c:1470
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
**Symbols:**

```
ffffffff81a25a10-ffffffff81a25fb6: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba7be0)
Location: drivers/ata/libata-core.c:1470
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
**Symbols:**

```
ffffffff81ba7be0-ffffffff81ba8141: ata_exec_internal_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfe880)
Location: drivers/ata/libata-core.c:1504
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
**Symbols:**

```
ffffffff81bfe880-ffffffff81bfede1: ata_exec_internal_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c54570)
Location: drivers/ata/libata-core.c:1504
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_power_set_active
  - drivers/ata/libata-core.c:ata_dev_power_set_standby
  - drivers/ata/libata-core.c:ata_dev_power_is_active
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
```
**Symbols:**

```
ffffffff81c54570-ffffffff81c54a8c: ata_exec_internal_sg (STB_LOCAL)
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
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099a678)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffff80001099a678-ffff80001099abfc: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6a92c)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
**Symbols:**

```
c0a6a92c-c0a6ae3c: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5dc10)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
c000000000a5dc10-c000000000a5e1e8: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005faf9e)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffe0005faf9e-ffffffe0005fb3c6: ata_exec_internal_sg (STB_GLOBAL)
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
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff8175a1e8-ffffffff8175a208: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff81755b00-ffffffff8175607e: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff8173a088-ffffffff8173a0a8: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff817359a0-ffffffff81735f1e: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff81789f58-ffffffff81789f78: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff81785840-ffffffff81785dbe: ata_exec_internal_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, struct scatterlist *sgl, unsigned int n_elem, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:1547
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
  - drivers/ata/libata-core.c:ata_read_native_max_address
```
**Symbols:**

```
ffffffff817a3da8-ffffffff817a3dc8: ata_exec_internal_sg.cold (STB_LOCAL)
ffffffff8179f690-ffffffff8179fc0e: ata_exec_internal_sg (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int timeout</code> ➡️ <code>unsigned int timeout</code>
</li>
</ul>
</details>
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
