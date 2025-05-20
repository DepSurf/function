# Function: <code>nvdimm_map_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815f07a3)
Location: drivers/nvdimm/region_devs.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161d6db)
Location: drivers/nvdimm/region_devs.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
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
In drivers/nvdimm/region_devs.c (ffffffff81631b4e)
Location: drivers/nvdimm/region_devs.c:33
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
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
In drivers/nvdimm/region_devs.c (ffffffff8169a4ae)
Location: drivers/nvdimm/region_devs.c:33
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
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
In drivers/nvdimm/region_devs.c (ffffffff816d6792)
Location: drivers/nvdimm/region_devs.c:33
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
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
In drivers/nvdimm/region_devs.c (ffffffff816f8575)
Location: drivers/nvdimm/region_devs.c:33
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81731c3d)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81755dad)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvdimm_map_flush(struct device *dev, struct nvdimm *nvdimm, int dimm, struct nd_region_data *ndrd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81813300)
Location: drivers/nvdimm/region_devs.c:25
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff81813300-ffffffff81813478: nvdimm_map_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvdimm_map_flush(struct device *dev, struct nvdimm *nvdimm, int dimm, struct nd_region_data *ndrd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818224f0)
Location: drivers/nvdimm/region_devs.c:25
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff818224f0-ffffffff81822668: nvdimm_map_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818078f4)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nvdimm_map_flush(struct device *dev, struct nvdimm *nvdimm, int dimm, struct nd_region_data *ndrd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:25
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff818906c0-ffffffff81890851: nvdimm_map_flush (STB_LOCAL)
ffffffff81d0af80-ffffffff81d0aff2: nvdimm_map_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nvdimm_map_flush(struct device *dev, struct nvdimm *nvdimm, int dimm, struct nd_region_data *ndrd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:25
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff819dab80-ffffffff819dad3b: nvdimm_map_flush (STB_LOCAL)
ffffffff81ed345f-ffffffff81ed34d1: nvdimm_map_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nvdimm_map_flush(struct device *dev, struct nvdimm *nvdimm, int dimm, struct nd_region_data *ndrd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:25
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff81b55fa0-ffffffff81b5615b: nvdimm_map_flush (STB_LOCAL)
ffffffff8209a6c9-ffffffff8209a73b: nvdimm_map_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nvdimm_map_flush(struct device *dev, struct nvdimm *nvdimm, int dimm, struct nd_region_data *ndrd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:25
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff81ba94f0-ffffffff81ba96af: nvdimm_map_flush (STB_LOCAL)
ffffffff8211b7a1-ffffffff8211b7f6: nvdimm_map_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nvdimm_map_flush(struct device *dev, struct nvdimm *nvdimm, int dimm, struct nd_region_data *ndrd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:26
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
**Symbols:**

```
ffffffff81bfd830-ffffffff81bfd9ef: nvdimm_map_flush (STB_LOCAL)
ffffffff821f9628-ffffffff821f967d: nvdimm_map_flush.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff8000109570a8)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a04eec)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c61ae)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8170a49d)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816ddf1d)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8174926d)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817646ed)
Location: drivers/nvdimm/region_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
