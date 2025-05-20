# Function: <code>of_platform_bus_probe</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_platform_bus_probe(struct device_node *root, const struct of_device_id *matches, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffff800010b6dc78)
Location: drivers/of/platform.c:417
Inline: False
```
**Symbols:**

```
ffff800010b6dc78-ffff800010b6ddec: of_platform_bus_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_platform_bus_probe(struct device_node *root, const struct of_device_id *matches, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c0c50b1c)
Location: drivers/of/platform.c:417
Inline: False
```
**Symbols:**

```
c0c50b1c-c0c50c84: of_platform_bus_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_platform_bus_probe(struct device_node *root, const struct of_device_id *matches, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c000000000c48410)
Location: drivers/of/platform.c:417
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/pmem.c:__machine_initcall_pseries_pseries_pmem_init
```
**Symbols:**

```
c000000000c48410-c000000000c485ec: of_platform_bus_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_platform_bus_probe(struct device_node *root, const struct of_device_id *matches, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffffffe00072268a)
Location: drivers/of/platform.c:417
Inline: False
```
**Symbols:**

```
ffffffe00072268a-ffffffe0007227cc: of_platform_bus_probe (STB_GLOBAL)
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
