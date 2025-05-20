# Function: <code>nvdimm_set_config_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81598d60)
Location: drivers/nvdimm/dimm_devs.c:136
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff81598d60-ffffffff81598f7f: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff815ee840)
Location: drivers/nvdimm/dimm_devs.c:136
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff815ee840-ffffffff815eea5c: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8161b940)
Location: drivers/nvdimm/dimm_devs.c:138
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff8161b940-ffffffff8161bb5c: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8162fa10)
Location: drivers/nvdimm/dimm_devs.c:140
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff8162fa10-ffffffff8162fc29: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816981f0)
Location: drivers/nvdimm/dimm_devs.c:140
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff816981f0-ffffffff8169840c: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816d4370)
Location: drivers/nvdimm/dimm_devs.c:142
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff816d4370-ffffffff816d45b6: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5d60)
Location: drivers/nvdimm/dimm_devs.c:134
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff816f5d60-ffffffff816f5f1f: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff81730198-ffffffff817301ba: nvdimm_set_config_data.cold (STB_LOCAL)
ffffffff8172f530-ffffffff8172f6df: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817539c0)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff817539c0-ffffffff81753b95: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff818124a0)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff818124a0-ffffffff8181264e: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff818216f0)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff818216f0-ffffffff8182189e: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81804a10)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff81804a10-ffffffff81804bbd: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8188f040)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff8188f040-ffffffff8188f1ed: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff819d8550)
Location: drivers/nvdimm/dimm_devs.c:127
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff819d8550-ffffffff819d8700: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81b53440)
Location: drivers/nvdimm/dimm_devs.c:127
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff81b53440-ffffffff81b535f0: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba68f0)
Location: drivers/nvdimm/dimm_devs.c:127
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff81ba68f0-ffffffff81ba6aed: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfaba0)
Location: drivers/nvdimm/dimm_devs.c:129
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff81bfaba0-ffffffff81bfad9d: nvdimm_set_config_data (STB_GLOBAL)
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
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff800010954308)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffff800010954308-ffff8000109544f8: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a01900)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
c000000000a01900-c000000000a01b40: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3b52)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffe0005c3b52-ffffffe0005c3cf2: nvdimm_set_config_data (STB_GLOBAL)
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
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817080b0)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff817080b0-ffffffff81708285: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816dbb30)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff816dbb30-ffffffff816dbd05: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81746e80)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff81746e80-ffffffff81747055: nvdimm_set_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvdimm_set_config_data(struct nvdimm_drvdata *ndd, size_t offset, void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817622c0)
Location: drivers/nvdimm/dimm_devs.c:131
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff817622c0-ffffffff81762495: nvdimm_set_config_data (STB_GLOBAL)
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
