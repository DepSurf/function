# Function: <code>of_platform_bus_create</code>

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
int of_platform_bus_create(struct device_node *bus, const struct of_device_id *matches, const struct of_dev_auxdata *lookup, struct device *parent, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffff800010b6d798)
Location: drivers/of/platform.c:346
Inline: False
Direct callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_probe
  - drivers/of/platform.c:of_platform_bus_probe
  - drivers/of/platform.c:of_platform_bus_create
```
**Symbols:**

```
ffff800010b6d798-ffff800010b6dc78: of_platform_bus_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_platform_bus_create(struct device_node *bus, const struct of_device_id *matches, const struct of_dev_auxdata *lookup, struct device *parent, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c0c505fc)
Location: drivers/of/platform.c:346
Inline: False
Direct callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_probe
  - drivers/of/platform.c:of_platform_bus_probe
  - drivers/of/platform.c:of_platform_bus_create
```
**Symbols:**

```
c0c505fc-c0c50b1c: of_platform_bus_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_platform_bus_create(struct device_node *bus, const struct of_device_id *matches, const struct of_dev_auxdata *lookup, struct device *parent, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c000000000c47fc0)
Location: drivers/of/platform.c:346
Inline: False
Direct callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_probe
  - drivers/of/platform.c:of_platform_bus_probe
  - drivers/of/platform.c:of_platform_bus_create
```
**Symbols:**

```
c000000000c47fc0-c000000000c4840c: of_platform_bus_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_platform_bus_create(struct device_node *bus, const struct of_device_id *matches, const struct of_dev_auxdata *lookup, struct device *parent, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffffffe0007223ae)
Location: drivers/of/platform.c:346
Inline: False
Direct callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_probe
  - drivers/of/platform.c:of_platform_bus_probe
  - drivers/of/platform.c:of_platform_bus_create
```
**Symbols:**

```
ffffffe0007223ae-ffffffe00072268a: of_platform_bus_create (STB_LOCAL)
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
