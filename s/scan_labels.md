# Function: <code>scan_labels</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81621d43)
Location: drivers/nvdimm/namespace_devs.c:2066
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8163685a)
Location: drivers/nvdimm/namespace_devs.c:2263
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169e4b0)
Location: drivers/nvdimm/namespace_devs.c:2272
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8169e4b0-ffffffff8169f396: scan_labels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816da8f0)
Location: drivers/nvdimm/namespace_devs.c:2266
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff816da8f0-ffffffff816db6b0: scan_labels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fc880)
Location: drivers/nvdimm/namespace_devs.c:2291
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff816fc880-ffffffff816fd696: scan_labels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2301
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81736930-ffffffff81737260: scan_labels (STB_LOCAL)
ffffffff81737a53-ffffffff81737ac8: scan_labels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2301
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8175a6c0-ffffffff8175b001: scan_labels (STB_LOCAL)
ffffffff8175b7f2-ffffffff8175b809: scan_labels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a620)
Location: drivers/nvdimm/namespace_devs.c:2342
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8181a620-ffffffff8181aad6: scan_labels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81829740)
Location: drivers/nvdimm/namespace_devs.c:2342
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81829740-ffffffff81829bf6: scan_labels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c950)
Location: drivers/nvdimm/namespace_devs.c:2342
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8180c950-ffffffff8180ce06: scan_labels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81896ee0)
Location: drivers/nvdimm/namespace_devs.c:2320
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81896ee0-ffffffff81897371: scan_labels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1936
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff819e0010-ffffffff819e050e: scan_labels (STB_LOCAL)
ffffffff81ed3ad7-ffffffff81ed3b67: scan_labels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1926
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81b5ba30-ffffffff81b5bf2e: scan_labels (STB_LOCAL)
ffffffff8209ac99-ffffffff8209ad1e: scan_labels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1926
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81baefd0-ffffffff81baf4fe: scan_labels (STB_LOCAL)
ffffffff8211bc06-ffffffff8211bc72: scan_labels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1937
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81c033a0-ffffffff81c0392c: scan_labels (STB_LOCAL)
ffffffff821f9a8d-ffffffff821f9af9: scan_labels.cold (STB_LOCAL)
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
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095be98)
Location: drivers/nvdimm/namespace_devs.c:2301
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffff80001095be98-ffff80001095c674: scan_labels (STB_LOCAL)
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
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0d1a0)
Location: drivers/nvdimm/namespace_devs.c:2301
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
c000000000a0d1a0-c000000000a0dbac: scan_labels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca34c)
Location: drivers/nvdimm/namespace_devs.c:2301
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffe0005ca34c-ffffffe0005caa66: scan_labels (STB_LOCAL)
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
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2301
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8170edb0-ffffffff8170f6f1: scan_labels (STB_LOCAL)
ffffffff8170fee2-ffffffff8170fef9: scan_labels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2301
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff816e2830-ffffffff816e3171: scan_labels (STB_LOCAL)
ffffffff816e3962-ffffffff816e3979: scan_labels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2301
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8174db80-ffffffff8174e4c1: scan_labels (STB_LOCAL)
ffffffff8174ecb2-ffffffff8174ecc9: scan_labels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct device **scan_labels(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2301
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81769000-ffffffff81769941: scan_labels (STB_LOCAL)
ffffffff8176a132-ffffffff8176a149: scan_labels.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
