# Function: <code>dev_pm_opp_of_get_opp_desc_node</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct device_node *dev_pm_opp_of_get_opp_desc_node(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffff800010b1b534)
Location: drivers/opp/of.c:36
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
**Symbols:**

```
ffff800010b1b090-ffff800010b1b0c8: dev_pm_opp_of_get_opp_desc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device_node *dev_pm_opp_of_get_opp_desc_node(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c0bf5c64)
Location: drivers/opp/of.c:36
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
Direct callers:
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
```
**Symbols:**

```
c0bf5a74-c0bf5aa0: dev_pm_opp_of_get_opp_desc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device_node *dev_pm_opp_of_get_opp_desc_node(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c000000000c0d510)
Location: drivers/opp/of.c:36
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
**Symbols:**

```
c000000000c0d160-c000000000c0d1a4: dev_pm_opp_of_get_opp_desc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device_node *dev_pm_opp_of_get_opp_desc_node(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffffffe0007036a0)
Location: drivers/opp/of.c:36
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
**Symbols:**

```
ffffffe000703428-ffffffe00070345e: dev_pm_opp_of_get_opp_desc_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
