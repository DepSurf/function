# Function: <code>nd_region_register_namespaces</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8159df90)
Location: drivers/nvdimm/namespace_devs.c:1908
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff8159df90-ffffffff8159e9a0: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f4000)
Location: drivers/nvdimm/namespace_devs.c:1974
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff815f4000-ffffffff815f4a02: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81621b80)
Location: drivers/nvdimm/namespace_devs.c:2283
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff81621b80-ffffffff816226dc: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81636690)
Location: drivers/nvdimm/namespace_devs.c:2490
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff81636690-ffffffff81637235: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169f6c0)
Location: drivers/nvdimm/namespace_devs.c:2499
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff8169f6c0-ffffffff8169fb96: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816db9c0)
Location: drivers/nvdimm/namespace_devs.c:2493
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff816db9c0-ffffffff816dbe98: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fd9c0)
Location: drivers/nvdimm/namespace_devs.c:2518
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff816fd9c0-ffffffff816fde93: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2534
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff81737b50-ffffffff81737b94: nd_region_register_namespaces.cold (STB_LOCAL)
ffffffff81737540-ffffffff817379fe: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2557
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff8175b845-ffffffff8175b889: nd_region_register_namespaces.cold (STB_LOCAL)
ffffffff8175b2f0-ffffffff8175b7e6: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8181ace0)
Location: drivers/nvdimm/namespace_devs.c:2598
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff8181ace0-ffffffff8181aff9: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81829e00)
Location: drivers/nvdimm/namespace_devs.c:2598
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff81829e00-ffffffff8182a119: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180d0e0)
Location: drivers/nvdimm/namespace_devs.c:2603
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff8180d0e0-ffffffff8180d3f8: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81897650)
Location: drivers/nvdimm/namespace_devs.c:2578
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff81897650-ffffffff81897968: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff819e1360)
Location: drivers/nvdimm/namespace_devs.c:2163
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff819e1360-ffffffff819e165c: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5ced0)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff81b5ced0-ffffffff81b5d1cc: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bb0480)
Location: drivers/nvdimm/namespace_devs.c:2153
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff81bb0480-ffffffff81bb077b: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c048e0)
Location: drivers/nvdimm/namespace_devs.c:2164
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff81c048e0-ffffffff81c04c39: nd_region_register_namespaces (STB_GLOBAL)
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
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095c9c0)
Location: drivers/nvdimm/namespace_devs.c:2557
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffff80001095c9c0-ffff80001095cf08: nd_region_register_namespaces (STB_GLOBAL)
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
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0e000)
Location: drivers/nvdimm/namespace_devs.c:2557
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
c000000000a0e000-c000000000a0e694: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005cad28)
Location: drivers/nvdimm/namespace_devs.c:2557
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffe0005cad28-ffffffe0005cb194: nd_region_register_namespaces (STB_GLOBAL)
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
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2557
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff8170ff35-ffffffff8170ff79: nd_region_register_namespaces.cold (STB_LOCAL)
ffffffff8170f9e0-ffffffff8170fed6: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2557
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff816e39b5-ffffffff816e39f9: nd_region_register_namespaces.cold (STB_LOCAL)
ffffffff816e3460-ffffffff816e3956: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2557
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff8174ed05-ffffffff8174ed49: nd_region_register_namespaces.cold (STB_LOCAL)
ffffffff8174e7b0-ffffffff8174eca6: nd_region_register_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nd_region_register_namespaces(struct nd_region *nd_region, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2557
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
**Symbols:**

```
ffffffff8176a185-ffffffff8176a1c9: nd_region_register_namespaces.cold (STB_LOCAL)
ffffffff81769c30-ffffffff8176a126: nd_region_register_namespaces (STB_GLOBAL)
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
