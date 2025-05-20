# Function: <code>__of_device_is_compatible</code>

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
int __of_device_is_compatible(const struct device_node *device, const char *compat, const char *type, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b688d8)
Location: drivers/of/base.c:510
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_device_is_compatible
```
**Symbols:**

```
ffff800010b688d8-ffff800010b68a24: __of_device_is_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __of_device_is_compatible(const struct device_node *device, const char *compat, const char *type, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4c99c)
Location: drivers/of/base.c:510
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_device_is_compatible
```
**Symbols:**

```
c0c4c99c-c0c4cab4: __of_device_is_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __of_device_is_compatible(const struct device_node *device, const char *compat, const char *type, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c41bc0)
Location: drivers/of/base.c:510
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_device_is_compatible
```
**Symbols:**

```
c000000000c41bc0-c000000000c41ddc: __of_device_is_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __of_device_is_compatible(const struct device_node *device, const char *compat, const char *type, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071ece4)
Location: drivers/of/base.c:510
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_device_is_compatible
```
**Symbols:**

```
ffffffe00071ece4-ffffffe00071edc8: __of_device_is_compatible (STB_LOCAL)
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
