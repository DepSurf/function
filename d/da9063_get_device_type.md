# Function: <code>da9063_get_device_type</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int da9063_get_device_type(struct i2c_client *i2c, struct da9063 *da9063);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/da9063-i2c.c (0)
Location: drivers/mfd/da9063-i2c.c:105
Inline: False
Direct callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
**Symbols:**

```
ffffffff81816280-ffffffff81816327: da9063_get_device_type (STB_LOCAL)
ffffffff81c13c8b-ffffffff81c13d12: da9063_get_device_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-i2c.c (ffffffff817fa9ca)
Location: drivers/mfd/da9063-i2c.c:105
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-i2c.c (ffffffff81883eba)
Location: drivers/mfd/da9063-i2c.c:105
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-i2c.c (ffffffff819cca61)
Location: drivers/mfd/da9063-i2c.c:105
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-i2c.c (ffffffff81b449d7)
Location: drivers/mfd/da9063-i2c.c:105
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-i2c.c (ffffffff81b97d87)
Location: drivers/mfd/da9063-i2c.c:105
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/da9063-i2c.c (ffffffff81bebd57)
Location: drivers/mfd/da9063-i2c.c:105
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
</ul>
