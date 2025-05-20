# Function: <code>add_namespace_resource</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff81621d94)
Location: drivers/nvdimm/namespace_devs.c:1965
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
In drivers/nvdimm/namespace_devs.c (ffffffff816368a2)
Location: drivers/nvdimm/namespace_devs.c:2142
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169e57f)
Location: drivers/nvdimm/namespace_devs.c:2151
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
In drivers/nvdimm/namespace_devs.c (ffffffff816da9ab)
Location: drivers/nvdimm/namespace_devs.c:2145
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fc93f)
Location: drivers/nvdimm/namespace_devs.c:2170
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
In drivers/nvdimm/namespace_devs.c (ffffffff817369fb)
Location: drivers/nvdimm/namespace_devs.c:2177
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
In drivers/nvdimm/namespace_devs.c (ffffffff8175a78b)
Location: drivers/nvdimm/namespace_devs.c:2177
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int add_namespace_resource(struct nd_region *nd_region, struct nd_namespace_label *nd_label, struct device **devs, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2218
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff8181a210-ffffffff8181a353: add_namespace_resource (STB_LOCAL)
ffffffff8181b067-ffffffff8181b084: add_namespace_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int add_namespace_resource(struct nd_region *nd_region, struct nd_namespace_label *nd_label, struct device **devs, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2218
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81829330-ffffffff81829473: add_namespace_resource (STB_LOCAL)
ffffffff81c15c56-ffffffff81c15c73: add_namespace_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int add_namespace_resource(struct nd_region *nd_region, struct nd_namespace_label *nd_label, struct device **devs, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2218
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff8180c540-ffffffff8180c683: add_namespace_resource (STB_LOCAL)
ffffffff81c079af-ffffffff81c079cc: add_namespace_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int add_namespace_resource(struct nd_region *nd_region, struct nd_namespace_label *nd_label, struct device **devs, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:2211
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81896b70-ffffffff81896cb0: add_namespace_resource (STB_LOCAL)
ffffffff81d0b2cd-ffffffff81d0b2ea: add_namespace_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff819e00d6)
Location: drivers/nvdimm/namespace_devs.c:1894
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5bb01)
Location: drivers/nvdimm/namespace_devs.c:1884
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81baf0a4)
Location: drivers/nvdimm/namespace_devs.c:1884
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c03474)
Location: drivers/nvdimm/namespace_devs.c:1895
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffff80001095bf64)
Location: drivers/nvdimm/namespace_devs.c:2177
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
In drivers/nvdimm/namespace_devs.c (c000000000a0d2e0)
Location: drivers/nvdimm/namespace_devs.c:2177
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
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca3d8)
Location: drivers/nvdimm/namespace_devs.c:2177
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170ee7b)
Location: drivers/nvdimm/namespace_devs.c:2177
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e28fb)
Location: drivers/nvdimm/namespace_devs.c:2177
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174dc4b)
Location: drivers/nvdimm/namespace_devs.c:2177
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
In drivers/nvdimm/namespace_devs.c (ffffffff817690cb)
Location: drivers/nvdimm/namespace_devs.c:2177
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
