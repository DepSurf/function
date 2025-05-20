# Function: <code>create_namespace_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8159e30e)
Location: drivers/nvdimm/namespace_devs.c:1634
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f4353)
Location: drivers/nvdimm/namespace_devs.c:1676
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81621050)
Location: drivers/nvdimm/namespace_devs.c:1700
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81621050-ffffffff81621597: create_namespace_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81635a40)
Location: drivers/nvdimm/namespace_devs.c:1869
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81635a40-ffffffff81635fc9: create_namespace_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169e9a8)
Location: drivers/nvdimm/namespace_devs.c:1878
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816dae3a)
Location: drivers/nvdimm/namespace_devs.c:1873
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fcdee)
Location: drivers/nvdimm/namespace_devs.c:1899
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff817350b0-ffffffff81735639: create_namespace_pmem (STB_LOCAL)
ffffffff81737a1d-ffffffff81737a53: create_namespace_pmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81758e40)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81758e40-ffffffff817593b9: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81818ce0)
Location: drivers/nvdimm/namespace_devs.c:1949
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81818ce0-ffffffff81819142: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81827e10)
Location: drivers/nvdimm/namespace_devs.c:1949
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81827e10-ffffffff81828262: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180b030)
Location: drivers/nvdimm/namespace_devs.c:1949
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff8180b030-ffffffff8180b482: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81895650)
Location: drivers/nvdimm/namespace_devs.c:1942
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81895650-ffffffff81895aac: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1669
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff819df9f0-ffffffff819e0010: create_namespace_pmem (STB_LOCAL)
ffffffff81ed3982-ffffffff81ed3ad7: create_namespace_pmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1661
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81b5b3c0-ffffffff81b5ba14: create_namespace_pmem (STB_LOCAL)
ffffffff8209ab5a-ffffffff8209ac99: create_namespace_pmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1661
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81bae970-ffffffff81baefbb: create_namespace_pmem (STB_LOCAL)
ffffffff8211bad2-ffffffff8211bc06: create_namespace_pmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1672
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81c02d10-ffffffff81c0338a: create_namespace_pmem (STB_LOCAL)
ffffffff821f9959-ffffffff821f9a8d: create_namespace_pmem.cold (STB_LOCAL)
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
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095a570)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffff80001095a570-ffff80001095aab0: create_namespace_pmem (STB_LOCAL)
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
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0a6d0)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
c000000000a0a6d0-c000000000a0adb0: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c8eb8)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffe0005c8eb8-ffffffe0005c9340: create_namespace_pmem (STB_LOCAL)
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
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8170d530)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff8170d530-ffffffff8170daa9: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816e0fb0)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff816e0fb0-ffffffff816e1529: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8174c300)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff8174c300-ffffffff8174c879: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *create_namespace_pmem(struct nd_region *nd_region, struct nd_namespace_index *nsindex, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81767780)
Location: drivers/nvdimm/namespace_devs.c:1906
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81767780-ffffffff81767cf9: create_namespace_pmem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nd_namespace_index *nsindex</code>
</li>
<li>
<b>Param reordered. </b>
<code>nd_region, nd_label</code> ➡️ <code>nd_region, nsindex, nd_label</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nd_mapping *nd_mapping</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nd_namespace_index *nsindex</code>
</li>
</ul>
</details>
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
