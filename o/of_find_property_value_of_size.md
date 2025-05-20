# Function: <code>of_find_property_value_of_size</code>

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
void *of_find_property_value_of_size(const struct device_node *np, const char *propname, u32 min, u32 max, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6fabc)
Location: drivers/of/property.c:78
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_u64
  - drivers/of/property.c:of_property_read_u64_index
  - drivers/of/property.c:of_property_read_u32_index
Direct callers:
  - drivers/of/property.c:of_property_read_variable_u64_array
  - drivers/of/property.c:of_property_read_variable_u32_array
  - drivers/of/property.c:of_property_read_variable_u16_array
  - drivers/of/property.c:of_property_read_variable_u8_array
```
**Symbols:**

```
ffff800010b6e2a0-ffff800010b6e35c: of_find_property_value_of_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *of_find_property_value_of_size(const struct device_node *np, const char *propname, u32 min, u32 max, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c513c4)
Location: drivers/of/property.c:78
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_u64
  - drivers/of/property.c:of_property_read_u64_index
  - drivers/of/property.c:of_property_read_u32_index
Direct callers:
  - drivers/of/property.c:of_property_read_variable_u64_array
  - drivers/of/property.c:of_property_read_variable_u32_array
  - drivers/of/property.c:of_property_read_variable_u16_array
  - drivers/of/property.c:of_property_read_variable_u8_array
```
**Symbols:**

```
c0c51020-c0c51098: of_find_property_value_of_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *of_find_property_value_of_size(const struct device_node *np, const char *propname, u32 min, u32 max, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c49060)
Location: drivers/of/property.c:78
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_u64
  - drivers/of/property.c:of_property_read_u64_index
  - drivers/of/property.c:of_property_read_u32_index
Direct callers:
  - drivers/of/property.c:of_property_read_variable_u64_array
  - drivers/of/property.c:of_property_read_variable_u32_array
  - drivers/of/property.c:of_property_read_variable_u16_array
  - drivers/of/property.c:of_property_read_variable_u8_array
```
**Symbols:**

```
c000000000c48ad0-c000000000c48bd0: of_find_property_value_of_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *of_find_property_value_of_size(const struct device_node *np, const char *propname, u32 min, u32 max, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe000723e10)
Location: drivers/of/property.c:78
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_u64
  - drivers/of/property.c:of_property_read_u64_index
  - drivers/of/property.c:of_property_read_u32_index
Direct callers:
  - drivers/of/property.c:of_property_read_variable_u64_array
  - drivers/of/property.c:of_property_read_variable_u32_array
  - drivers/of/property.c:of_property_read_variable_u16_array
  - drivers/of/property.c:of_property_read_variable_u8_array
```
**Symbols:**

```
ffffffe000722afa-ffffffe000722b6e: of_find_property_value_of_size (STB_LOCAL)
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
