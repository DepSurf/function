# Function: <code>devm_nsio_enable</code>

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
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff815f6a20)
Location: drivers/nvdimm/claim.c:249
Inline: False
```
**Symbols:**

```
ffffffff815f6a20-ffffffff815f6b27: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81624bf0)
Location: drivers/nvdimm/claim.c:267
Inline: False
```
**Symbols:**

```
ffffffff81624bf0-ffffffff81624cf7: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81639c50)
Location: drivers/nvdimm/claim.c:307
Inline: False
```
**Symbols:**

```
ffffffff81639c50-ffffffff81639d57: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff816a2850)
Location: drivers/nvdimm/claim.c:307
Inline: False
```
**Symbols:**

```
ffffffff816a2850-ffffffff816a2957: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff816de9f0)
Location: drivers/nvdimm/claim.c:309
Inline: False
```
**Symbols:**

```
ffffffff816de9f0-ffffffff816deaee: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81700dc0)
Location: drivers/nvdimm/claim.c:309
Inline: False
```
**Symbols:**

```
ffffffff81700dc0-ffffffff81700ebe: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:303
Inline: False
```
**Symbols:**

```
ffffffff8173b65f-ffffffff8173b67c: devm_nsio_enable.cold (STB_LOCAL)
ffffffff8173ac50-ffffffff8173ad34: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:303
Inline: False
```
**Symbols:**

```
ffffffff8175f32f-ffffffff8175f34c: devm_nsio_enable.cold (STB_LOCAL)
ffffffff8175e920-ffffffff8175ea04: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:303
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
```
**Symbols:**

```
ffffffff8181eed0-ffffffff8181eeee: devm_nsio_enable.cold (STB_LOCAL)
ffffffff8181ed40-ffffffff8181ee21: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:304
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
```
**Symbols:**

```
ffffffff81c15e69-ffffffff81c15e8a: devm_nsio_enable.cold (STB_LOCAL)
ffffffff8182dc80-ffffffff8182dd82: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:304
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
```
**Symbols:**

```
ffffffff81c07bd2-ffffffff81c07bf3: devm_nsio_enable.cold (STB_LOCAL)
ffffffff81810f50-ffffffff81811052: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:304
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
```
**Symbols:**

```
ffffffff81d0b558-ffffffff81d0b579: devm_nsio_enable.cold (STB_LOCAL)
ffffffff8189b5f0-ffffffff8189b6f2: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:304
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
```
**Symbols:**

```
ffffffff81ed4420-ffffffff81ed4441: devm_nsio_enable.cold (STB_LOCAL)
ffffffff819e4d50-ffffffff819e4e61: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81b60b00)
Location: drivers/nvdimm/claim.c:304
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
```
**Symbols:**

```
ffffffff81b60b00-ffffffff81b60c2f: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81bb4080)
Location: drivers/nvdimm/claim.c:304
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
```
**Symbols:**

```
ffffffff81bb4080-ffffffff81bb41af: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81c085d0)
Location: drivers/nvdimm/claim.c:304
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
```
**Symbols:**

```
ffffffff81c085d0-ffffffff81c086ff: devm_nsio_enable (STB_GLOBAL)
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
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffff800010960148)
Location: drivers/nvdimm/claim.c:303
Inline: False
```
**Symbols:**

```
ffff800010960148-ffff800010960230: devm_nsio_enable (STB_GLOBAL)
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
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (c000000000a12ef0)
Location: drivers/nvdimm/claim.c:303
Inline: False
```
**Symbols:**

```
c000000000a12ef0-c000000000a13038: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffe0005cdc32)
Location: drivers/nvdimm/claim.c:303
Inline: False
```
**Symbols:**

```
ffffffe0005cdc32-ffffffe0005cdd0e: devm_nsio_enable (STB_GLOBAL)
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
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:303
Inline: False
```
**Symbols:**

```
ffffffff81713a1f-ffffffff81713a3c: devm_nsio_enable.cold (STB_LOCAL)
ffffffff81713010-ffffffff817130f4: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:303
Inline: False
Direct callers:
  - drivers/nvdimm/pmem.c:nd_pmem_probe
  - drivers/dax/pmem/core.c:__dax_pmem_probe
```
**Symbols:**

```
ffffffff816e749f-ffffffff816e74bc: devm_nsio_enable.cold (STB_LOCAL)
ffffffff816e6a90-ffffffff816e6b74: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:303
Inline: False
```
**Symbols:**

```
ffffffff817527ef-ffffffff8175280c: devm_nsio_enable.cold (STB_LOCAL)
ffffffff81751de0-ffffffff81751ec4: devm_nsio_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int devm_nsio_enable(struct device *dev, struct nd_namespace_io *nsio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:303
Inline: False
```
**Symbols:**

```
ffffffff8176dc5f-ffffffff8176dc7c: devm_nsio_enable.cold (STB_LOCAL)
ffffffff8176d260-ffffffff8176d344: devm_nsio_enable (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>resource_size_t size</code>
</li>
</ul>
</details>
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
