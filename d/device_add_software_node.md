# Function: <code>device_add_software_node</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_add_software_node(struct device *dev, const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc8d0)
Location: drivers/base/swnode.c:1027
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff817bc8d0-ffffffff817bc997: device_add_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_add_software_node(struct device *dev, const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81846ac0)
Location: drivers/base/swnode.c:1029
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81846ac0-ffffffff81846b86: device_add_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_add_software_node(struct device *dev, const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198b350)
Location: drivers/base/swnode.c:1023
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff8198b350-ffffffff8198b4ba: device_add_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_add_software_node(struct device *dev, const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81afa860)
Location: drivers/base/swnode.c:1023
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81afa860-ffffffff81afa9ca: device_add_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_add_software_node(struct device *dev, const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b48c50)
Location: drivers/base/swnode.c:962
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81b48c50-ffffffff81b48dba: device_add_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_add_software_node(struct device *dev, const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba1040)
Location: drivers/base/swnode.c:965
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81ba1040-ffffffff81ba11aa: device_add_software_node (STB_GLOBAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
