# Function: <code>__of_get_property</code>

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
const void *__of_get_property(const struct device_node *np, const char *name, int *lenp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b68874)
Location: drivers/of/base.c:330
Inline: True
Inline callers:
  - drivers/of/base.c:__of_node_is_type
Direct callers:
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/dynamic.c:__of_attach_node
```
**Symbols:**

```
ffff800010b6a9c8-ffff800010b6aa14: __of_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const void *__of_get_property(const struct device_node *np, const char *name, int *lenp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4c93c)
Location: drivers/of/base.c:330
Inline: True
Inline callers:
  - drivers/of/base.c:__of_node_is_type
Direct callers:
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/dynamic.c:__of_attach_node
```
**Symbols:**

```
c0c4df88-c0c4dfac: __of_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const void *__of_get_property(const struct device_node *np, const char *name, int *lenp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c419f4)
Location: drivers/of/base.c:330
Inline: True
Inline callers:
  - drivers/of/base.c:__of_node_is_type
Direct callers:
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/dynamic.c:__of_attach_node
```
**Symbols:**

```
c000000000c44230-c000000000c4426c: __of_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const void *__of_get_property(const struct device_node *np, const char *name, int *lenp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071eca4)
Location: drivers/of/base.c:330
Inline: True
Inline callers:
  - drivers/of/base.c:__of_node_is_type
Direct callers:
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/dynamic.c:__of_attach_node
```
**Symbols:**

```
ffffffe00072011e-ffffffe00072015c: __of_get_property (STB_GLOBAL)
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
