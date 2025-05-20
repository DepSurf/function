# Function: <code>nd_namespace_pmem_create</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff816216c2)
Location: drivers/nvdimm/namespace_devs.c:1873
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff81636190)
Location: drivers/nvdimm/namespace_devs.c:2050
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169f480)
Location: drivers/nvdimm/namespace_devs.c:2059
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff816db6f2)
Location: drivers/nvdimm/namespace_devs.c:2053
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fd6e2)
Location: drivers/nvdimm/namespace_devs.c:2079
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff817372a3)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff8175b053)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *nd_namespace_pmem_create(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81818be0)
Location: drivers/nvdimm/namespace_devs.c:2128
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff81818be0-ffffffff81818cdc: nd_namespace_pmem_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *nd_namespace_pmem_create(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81827d10)
Location: drivers/nvdimm/namespace_devs.c:2128
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff81827d10-ffffffff81827e0c: nd_namespace_pmem_create (STB_LOCAL)
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
In drivers/nvdimm/namespace_devs.c (ffffffff8180ce53)
Location: drivers/nvdimm/namespace_devs.c:2128
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818973c3)
Location: drivers/nvdimm/namespace_devs.c:2121
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff819e112f)
Location: drivers/nvdimm/namespace_devs.c:1802
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff81b5cc1f)
Location: drivers/nvdimm/namespace_devs.c:1792
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff81bb01cf)
Location: drivers/nvdimm/namespace_devs.c:1792
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff81c045ff)
Location: drivers/nvdimm/namespace_devs.c:1803
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffff80001095c76c)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (c000000000a0dc18)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffe0005caaaa)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170f743)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e31c3)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174e513)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
In drivers/nvdimm/namespace_devs.c (ffffffff81769993)
Location: drivers/nvdimm/namespace_devs.c:2086
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
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
</ul>
