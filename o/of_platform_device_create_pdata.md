# Function: <code>of_platform_device_create_pdata</code>

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
struct platform_device *of_platform_device_create_pdata(struct device_node *np, const char *bus_id, void *platform_data, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffff800010b6d610)
Location: drivers/of/platform.c:166
Inline: False
Direct callers:
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_bus_create
```
**Symbols:**

```
ffff800010b6d610-ffff800010b6d74c: of_platform_device_create_pdata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct platform_device *of_platform_device_create_pdata(struct device_node *np, const char *bus_id, void *platform_data, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c0c5050c)
Location: drivers/of/platform.c:166
Inline: False
Direct callers:
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_bus_create
```
**Symbols:**

```
c0c5050c-c0c505d8: of_platform_device_create_pdata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct platform_device *of_platform_device_create_pdata(struct device_node *np, const char *bus_id, void *platform_data, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c000000000c47df0)
Location: drivers/of/platform.c:166
Inline: False
Direct callers:
  - drivers/of/platform.c:of_platform_bus_create
```
**Symbols:**

```
c000000000c47df0-c000000000c47f98: of_platform_device_create_pdata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct platform_device *of_platform_device_create_pdata(struct device_node *np, const char *bus_id, void *platform_data, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffffffe0007222b8)
Location: drivers/of/platform.c:166
Inline: False
Direct callers:
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_bus_create
```
**Symbols:**

```
ffffffe0007222b8-ffffffe000722372: of_platform_device_create_pdata (STB_LOCAL)
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
