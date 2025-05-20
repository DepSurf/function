# Function: <code>devm_nvdimm_memremap</code>

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
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815ebfb0)
Location: drivers/nvdimm/core.c:164
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff815ebfb0-ffffffff815ec27b: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81618ba0)
Location: drivers/nvdimm/core.c:164
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff81618ba0-ffffffff81618e6f: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8162ccf0)
Location: drivers/nvdimm/core.c:164
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff8162ccf0-ffffffff8162cf79: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81695480)
Location: drivers/nvdimm/core.c:164
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff81695480-ffffffff81695714: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d1540)
Location: drivers/nvdimm/core.c:164
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff816d1540-ffffffff816d17d5: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816f2bd0)
Location: drivers/nvdimm/core.c:164
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff816f2bd0-ffffffff816f2e68: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff8172c66c-ffffffff8172c696: devm_nvdimm_memremap.cold (STB_LOCAL)
ffffffff8172c140-ffffffff8172c3a6: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff817508ac-ffffffff817508d6: devm_nvdimm_memremap.cold (STB_LOCAL)
ffffffff81750390-ffffffff817505e6: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8180edf0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_map_flush
```
**Symbols:**

```
ffffffff8180edf0-ffffffff8180ef33: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8181dd60)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_map_flush
```
**Symbols:**

```
ffffffff8181dd60-ffffffff8181dea3: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81800fd0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff81800fd0-ffffffff8180110e: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8188b3e0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_map_flush
```
**Symbols:**

```
ffffffff8188b3e0-ffffffff8188b51e: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff819d4740)
Location: drivers/nvdimm/core.c:157
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_map_flush
```
**Symbols:**

```
ffffffff819d4740-ffffffff819d4891: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81b4efe0)
Location: drivers/nvdimm/core.c:157
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_map_flush
```
**Symbols:**

```
ffffffff81b4efe0-ffffffff81b4f131: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81ba2430)
Location: drivers/nvdimm/core.c:157
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_map_flush
```
**Symbols:**

```
ffffffff81ba2430-ffffffff81ba2588: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81bf65f0)
Location: drivers/nvdimm/core.c:157
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_map_flush
```
**Symbols:**

```
ffffffff81bf65f0-ffffffff81bf6748: devm_nvdimm_memremap (STB_GLOBAL)
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
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffff80001094fdb0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffff80001094fdb0-ffff8000109500d0: devm_nvdimm_memremap (STB_GLOBAL)
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
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (c0000000009fc9d0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
c0000000009fc9d0-c0000000009fcd0c: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffe0005c020a)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffe0005c020a-ffffffe0005c041a: devm_nvdimm_memremap (STB_GLOBAL)
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
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff81704f9c-ffffffff81704fc6: devm_nvdimm_memremap.cold (STB_LOCAL)
ffffffff81704a80-ffffffff81704cd6: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_enable
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_enable
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff816d8a1c-ffffffff816d8a46: devm_nvdimm_memremap.cold (STB_LOCAL)
ffffffff816d8500-ffffffff816d8756: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff81743d6c-ffffffff81743d96: devm_nvdimm_memremap.cold (STB_LOCAL)
ffffffff81743850-ffffffff81743aa6: devm_nvdimm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *devm_nvdimm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:156
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff8175f1bc-ffffffff8175f1e6: devm_nvdimm_memremap.cold (STB_LOCAL)
ffffffff8175eca0-ffffffff8175eef6: devm_nvdimm_memremap (STB_GLOBAL)
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
