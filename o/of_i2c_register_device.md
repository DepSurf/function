# Function: <code>of_i2c_register_device</code>

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
struct i2c_client *of_i2c_register_device(struct i2c_adapter *adap, struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (ffff800010ab6858)
Location: drivers/i2c/i2c-core-of.c:64
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
**Symbols:**

```
ffff800010ab6858-ffff800010ab6930: of_i2c_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct i2c_client *of_i2c_register_device(struct i2c_adapter *adap, struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (c0b96aac)
Location: drivers/i2c/i2c-core-of.c:64
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
**Symbols:**

```
c0b96aac-c0b96b80: of_i2c_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct i2c_client *of_i2c_register_device(struct i2c_adapter *adap, struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (c000000000b996a0)
Location: drivers/i2c/i2c-core-of.c:64
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
**Symbols:**

```
c000000000b996a0-c000000000b997ac: of_i2c_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct i2c_client *of_i2c_register_device(struct i2c_adapter *adap, struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-of.c (ffffffe0006bc4fa)
Location: drivers/i2c/i2c-core-of.c:64
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
**Symbols:**

```
ffffffe0006bc4fa-ffffffe0006bc58a: of_i2c_register_device (STB_LOCAL)
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
