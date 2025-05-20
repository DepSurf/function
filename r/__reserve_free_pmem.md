# Function: <code>__reserve_free_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8159cbc0)
Location: drivers/nvdimm/namespace_devs.c:715
Inline: True
```
**Symbols:**

```
ffffffff8159cbc0-ffffffff8159cd7a: __reserve_free_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f2ba0)
Location: drivers/nvdimm/namespace_devs.c:712
Inline: True
```
**Symbols:**

```
ffffffff815f2ba0-ffffffff815f2d5a: __reserve_free_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816203f0)
Location: drivers/nvdimm/namespace_devs.c:783
Inline: True
```
**Symbols:**

```
ffffffff816203f0-ffffffff816205ae: __reserve_free_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81634e70)
Location: drivers/nvdimm/namespace_devs.c:802
Inline: True
```
**Symbols:**

```
ffffffff81634e70-ffffffff8163503a: __reserve_free_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169d7f0)
Location: drivers/nvdimm/namespace_devs.c:802
Inline: True
```
**Symbols:**

```
ffffffff8169d7f0-ffffffff8169d9ba: __reserve_free_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:802
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff816dbe98-ffffffff816dbea4: __reserve_free_pmem.cold.23 (STB_LOCAL)
ffffffff816d92e0-ffffffff816d94a3: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fb2a6)
Location: drivers/nvdimm/namespace_devs.c:805
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff816fde93-ffffffff816fde9f: __reserve_free_pmem.cold.23 (STB_LOCAL)
ffffffff816fb270-ffffffff816fb433: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81734d16)
Location: drivers/nvdimm/namespace_devs.c:797
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81737a11-ffffffff81737a1d: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff81734ce0-ffffffff81734e95: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81758aa6)
Location: drivers/nvdimm/namespace_devs.c:797
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff8175b7e6-ffffffff8175b7f2: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff81758a70-ffffffff81758c25: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818184e0)
Location: drivers/nvdimm/namespace_devs.c:777
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81818010-ffffffff818181a1: __reserve_free_pmem.part.0 (STB_LOCAL)
ffffffff8181aff9-ffffffff8181b005: __reserve_free_pmem.part.0.cold (STB_LOCAL)
ffffffff818184e0-ffffffff81818521: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81827610)
Location: drivers/nvdimm/namespace_devs.c:777
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81827140-ffffffff818272d1: __reserve_free_pmem.part.0 (STB_LOCAL)
ffffffff81c15be8-ffffffff81c15bf4: __reserve_free_pmem.part.0.cold (STB_LOCAL)
ffffffff81827610-ffffffff81827651: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180aa06)
Location: drivers/nvdimm/namespace_devs.c:777
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81c07981-ffffffff81c0798d: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff8180a9d0-ffffffff8180ab85: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818952c6)
Location: drivers/nvdimm/namespace_devs.c:777
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81d0b246-ffffffff81d0b26f: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff81895290-ffffffff81895458: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:607
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81ed3bf1-ffffffff81ed3c1a: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff819e0a30-ffffffff819e0c0b: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:604
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff8209ada8-ffffffff8209adc5: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff81b5c490-ffffffff81b5c677: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:604
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff8211bcac-ffffffff8211bcc9: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff81bafa70-ffffffff81bafc41: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:609
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff821f9b33-ffffffff821f9b50: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff81c03ea0-ffffffff81c04071: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095a180)
Location: drivers/nvdimm/namespace_devs.c:797
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffff80001095a180-ffff80001095a338: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a09e10)
Location: drivers/nvdimm/namespace_devs.c:797
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
c000000000a09e10-c000000000a0a050: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c8d5a)
Location: drivers/nvdimm/namespace_devs.c:797
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffe0005c8d5a-ffffffe0005c8eb8: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8170d196)
Location: drivers/nvdimm/namespace_devs.c:797
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff8170fed6-ffffffff8170fee2: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff8170d160-ffffffff8170d315: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816e0c16)
Location: drivers/nvdimm/namespace_devs.c:797
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff816e3956-ffffffff816e3962: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff816e0be0-ffffffff816e0d95: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8174bf66)
Location: drivers/nvdimm/namespace_devs.c:797
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff8174eca6-ffffffff8174ecb2: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff8174bf30-ffffffff8174c0e5: __reserve_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __reserve_free_pmem(struct device *dev, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff817673e6)
Location: drivers/nvdimm/namespace_devs.c:797
Inline: True
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff8176a126-ffffffff8176a132: __reserve_free_pmem.cold (STB_LOCAL)
ffffffff817673b0-ffffffff81767565: __reserve_free_pmem (STB_GLOBAL)
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
