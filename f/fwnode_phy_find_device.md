# Function: <code>fwnode_phy_find_device</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct phy_device *fwnode_phy_find_device(struct fwnode_handle *phy_fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81906570)
Location: drivers/net/phy/phy_device.c:2943
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:device_phy_find_device
```
**Symbols:**

```
ffffffff81906570-ffffffff819065b5: fwnode_phy_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct phy_device *fwnode_phy_find_device(struct fwnode_handle *phy_fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a59360)
Location: drivers/net/phy/phy_device.c:2971
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:device_phy_find_device
```
**Symbols:**

```
ffffffff81a59360-ffffffff81a593c9: fwnode_phy_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct phy_device *fwnode_phy_find_device(struct fwnode_handle *phy_fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be30f0)
Location: drivers/net/phy/phy_device.c:2977
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:device_phy_find_device
```
**Symbols:**

```
ffffffff81be30f0-ffffffff81be3159: fwnode_phy_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct phy_device *fwnode_phy_find_device(struct fwnode_handle *phy_fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3aff0)
Location: drivers/net/phy/phy_device.c:3133
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:device_phy_find_device
```
**Symbols:**

```
ffffffff81c3aff0-ffffffff81c3b059: fwnode_phy_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct phy_device *fwnode_phy_find_device(struct fwnode_handle *phy_fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cefc20)
Location: drivers/net/phy/phy_device.c:3208
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:device_phy_find_device
```
**Symbols:**

```
ffffffff81cefc20-ffffffff81cefc89: fwnode_phy_find_device (STB_GLOBAL)
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
