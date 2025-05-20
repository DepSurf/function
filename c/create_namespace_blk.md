# Function: <code>create_namespace_blk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device **create_namespace_blk(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8159d880)
Location: drivers/nvdimm/namespace_devs.c:1757
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8159d880-ffffffff8159de30: create_namespace_blk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device **create_namespace_blk(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f3860)
Location: drivers/nvdimm/namespace_devs.c:1823
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff815f3860-ffffffff815f3ddb: create_namespace_blk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *create_namespace_blk(struct nd_region *nd_region, struct nd_namespace_label *nd_label, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816219a0)
Location: drivers/nvdimm/namespace_devs.c:2003
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff816219a0-ffffffff81621b71: create_namespace_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *create_namespace_blk(struct nd_region *nd_region, struct nd_namespace_label *nd_label, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816363d0)
Location: drivers/nvdimm/namespace_devs.c:2180
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff816363d0-ffffffff81636681: create_namespace_blk (STB_GLOBAL)
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169e655)
Location: drivers/nvdimm/namespace_devs.c:2189
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
In drivers/nvdimm/namespace_devs.c (ffffffff816dab3a)
Location: drivers/nvdimm/namespace_devs.c:2183
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fcaf3)
Location: drivers/nvdimm/namespace_devs.c:2208
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff81736be4)
Location: drivers/nvdimm/namespace_devs.c:2215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff8175a8e9)
Location: drivers/nvdimm/namespace_devs.c:2215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *create_namespace_blk(struct nd_region *nd_region, struct nd_namespace_label *nd_label, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a360)
Location: drivers/nvdimm/namespace_devs.c:2256
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff8181a360-ffffffff8181a613: create_namespace_blk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *create_namespace_blk(struct nd_region *nd_region, struct nd_namespace_label *nd_label, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81829480)
Location: drivers/nvdimm/namespace_devs.c:2256
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81829480-ffffffff81829733: create_namespace_blk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *create_namespace_blk(struct nd_region *nd_region, struct nd_namespace_label *nd_label, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c690)
Location: drivers/nvdimm/namespace_devs.c:2256
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff8180c690-ffffffff8180c943: create_namespace_blk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *create_namespace_blk(struct nd_region *nd_region, struct nd_namespace_label *nd_label, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81896cb0)
Location: drivers/nvdimm/namespace_devs.c:2249
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81896cb0-ffffffff81896edc: create_namespace_blk (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/nvdimm/namespace_devs.c (ffff80001095c008)
Location: drivers/nvdimm/namespace_devs.c:2215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (c000000000a0d3ac)
Location: drivers/nvdimm/namespace_devs.c:2215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca466)
Location: drivers/nvdimm/namespace_devs.c:2215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170efd9)
Location: drivers/nvdimm/namespace_devs.c:2215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e2a59)
Location: drivers/nvdimm/namespace_devs.c:2215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174dda9)
Location: drivers/nvdimm/namespace_devs.c:2215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff81769229)
Location: drivers/nvdimm/namespace_devs.c:2215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nd_namespace_label *nd_label</code>
</li>
<li>
<b>Param added. </b>
<code>int count</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct device **</code> ➡️ <code>struct device *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
</ul>
