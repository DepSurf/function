# Function: <code>of_find_i2c_adapter_by_node</code>

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
struct i2c_adapter *of_find_i2c_adapter_by_node(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (ffff800010ab69b8)
Location: drivers/i2c/i2c-core-of.c:146
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_get_i2c_adapter_by_node
```
**Symbols:**

```
ffff800010ab69b8-ffff800010ab6a3c: of_find_i2c_adapter_by_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct i2c_adapter *of_find_i2c_adapter_by_node(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (c0b96be0)
Location: drivers/i2c/i2c-core-of.c:146
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_get_i2c_adapter_by_node
```
**Symbols:**

```
c0b96be0-c0b96c40: of_find_i2c_adapter_by_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct i2c_adapter *of_find_i2c_adapter_by_node(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (c000000000b99880)
Location: drivers/i2c/i2c-core-of.c:146
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_get_i2c_adapter_by_node
```
**Symbols:**

```
c000000000b99880-c000000000b99948: of_find_i2c_adapter_by_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct i2c_adapter *of_find_i2c_adapter_by_node(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (ffffffe0006bc604)
Location: drivers/i2c/i2c-core-of.c:146
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_get_i2c_adapter_by_node
```
**Symbols:**

```
ffffffe0006bc604-ffffffe0006bc67e: of_find_i2c_adapter_by_node (STB_GLOBAL)
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
