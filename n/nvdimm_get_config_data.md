# Function: <code>nvdimm_get_config_data</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5ba0)
Location: drivers/nvdimm/dimm_devs.c:88
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff816f5ba0-ffffffff816f5d59: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81730176-ffffffff81730198: nvdimm_get_config_data.cold (STB_LOCAL)
ffffffff8172f380-ffffffff8172f52e: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817537e0)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff817537e0-ffffffff817539b4: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff818122e0)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff818122e0-ffffffff81812491: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81821530)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81821530-ffffffff818216e1: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81804860)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81804860-ffffffff81804a10: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8188ee90)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8188ee90-ffffffff8188f040: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff819d83a0)
Location: drivers/nvdimm/dimm_devs.c:81
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff819d83a0-ffffffff819d8544: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81b53280)
Location: drivers/nvdimm/dimm_devs.c:81
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81b53280-ffffffff81b53425: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6720)
Location: drivers/nvdimm/dimm_devs.c:81
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81ba6720-ffffffff81ba68da: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa9d0)
Location: drivers/nvdimm/dimm_devs.c:83
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81bfa9d0-ffffffff81bfab8a: nvdimm_get_config_data (STB_GLOBAL)
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
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff800010954138)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffff800010954138-ffff800010954308: nvdimm_get_config_data (STB_GLOBAL)
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
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a016a0)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
c000000000a016a0-c000000000a018f4: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3992)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffe0005c3992-ffffffe0005c3b52: nvdimm_get_config_data (STB_GLOBAL)
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
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81707ed0)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81707ed0-ffffffff817080a4: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816db950)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff816db950-ffffffff816dbb24: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81746ca0)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81746ca0-ffffffff81746e74: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata *ndd, void *buf, size_t offset, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817620e0)
Location: drivers/nvdimm/dimm_devs.c:85
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff817620e0-ffffffff817622b4: nvdimm_get_config_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
