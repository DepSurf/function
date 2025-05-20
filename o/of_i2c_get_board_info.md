# Function: <code>of_i2c_get_board_info</code>

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
int of_i2c_get_board_info(struct device *dev, struct device_node *node, struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (ffff800010ab66c8)
Location: drivers/i2c/i2c-core-of.c:22
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
```
**Symbols:**

```
ffff800010ab66c8-ffff800010ab683c: of_i2c_get_board_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_i2c_get_board_info(struct device *dev, struct device_node *node, struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (c0b96940)
Location: drivers/i2c/i2c-core-of.c:22
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
```
**Symbols:**

```
c0b96940-c0b96aac: of_i2c_get_board_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_i2c_get_board_info(struct device *dev, struct device_node *node, struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (c000000000b994d0)
Location: drivers/i2c/i2c-core-of.c:22
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
```
**Symbols:**

```
c000000000b994d0-c000000000b99694: of_i2c_get_board_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_i2c_get_board_info(struct device *dev, struct device_node *node, struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (ffffffe0006bc3ce)
Location: drivers/i2c/i2c-core-of.c:22
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
```
**Symbols:**

```
ffffffe0006bc3ce-ffffffe0006bc4fa: of_i2c_get_board_info (STB_GLOBAL)
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
