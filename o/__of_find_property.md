# Function: <code>__of_find_property</code>

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
struct property *__of_find_property(const struct device_node *np, const char *name, int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b68698)
Location: drivers/of/base.c:253
Inline: False
Direct callers:
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/base.c:of_find_property
  - drivers/of/base.c:__of_node_is_type
```
**Symbols:**

```
ffff800010b68698-ffff800010b6870c: __of_find_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct property *__of_find_property(const struct device_node *np, const char *name, int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4c704)
Location: drivers/of/base.c:253
Inline: False
Direct callers:
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/base.c:of_find_property
  - drivers/of/base.c:__of_node_is_type
```
**Symbols:**

```
c0c4c704-c0c4c774: __of_find_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct property *__of_find_property(const struct device_node *np, const char *name, int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c41140)
Location: drivers/of/base.c:253
Inline: False
Direct callers:
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/base.c:of_find_property
  - drivers/of/base.c:__of_node_is_type
```
**Symbols:**

```
c000000000c41140-c000000000c41380: __of_find_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct property *__of_find_property(const struct device_node *np, const char *name, int *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071ea56)
Location: drivers/of/base.c:253
Inline: False
Direct callers:
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/base.c:of_find_property
  - drivers/of/base.c:__of_node_is_type
```
**Symbols:**

```
ffffffe00071ea56-ffffffe00071eaac: __of_find_property (STB_LOCAL)
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
