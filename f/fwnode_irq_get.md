# Function: <code>fwnode_irq_get</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688fc0)
Location: drivers/base/property.c:1326
Inline: False
```
**Symbols:**

```
ffffffff81688fc0-ffffffff81688fd5: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8c90)
Location: drivers/base/property.c:849
Inline: False
```
**Symbols:**

```
ffffffff816a8c90-ffffffff816a8ca5: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e20c0)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
ffffffff816e20c0-ffffffff816e20d5: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81706270)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
ffffffff81706270-ffffffff81706285: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0830)
Location: drivers/base/property.c:952
Inline: False
```
**Symbols:**

```
ffffffff817c0830-ffffffff817c0845: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d56d0)
Location: drivers/base/property.c:1004
Inline: False
```
**Symbols:**

```
ffffffff817d56d0-ffffffff817d56e5: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9110)
Location: drivers/base/property.c:1010
Inline: False
```
**Symbols:**

```
ffffffff817b9110-ffffffff817b9125: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fwnode_irq_get(const struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842d70)
Location: drivers/base/property.c:1008
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81842d70-ffffffff81842d85: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fwnode_irq_get(const struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986a30)
Location: drivers/base/property.c:945
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_irq_get_byname
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81986a30-ffffffff81986a8d: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fwnode_irq_get(const struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af5180)
Location: drivers/base/property.c:953
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_irq_get_byname
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81af5180-ffffffff81af51dd: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fwnode_irq_get(const struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43390)
Location: drivers/base/property.c:992
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_irq_get_byname
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81b43390-ffffffff81b43402: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fwnode_irq_get(const struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9b260)
Location: drivers/base/property.c:1056
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_irq_get_byname
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81b9b260-ffffffff81b9b2d2: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3280)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
ffff8000108f3280-ffff8000108f3360: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09dfc08)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
c09dfc08-c09dfc58: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098cee0)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
c00000000098cee0-c00000000098cf50: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584b40)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
ffffffe000584b40-ffffffe000584b9a: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb9c0)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
ffffffff816cb9c0-ffffffff816cb9d5: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6cf0)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
ffffffff816a6cf0-ffffffff816a6d05: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9f30)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
ffffffff816f9f30-ffffffff816f9f45: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fwnode_irq_get(struct fwnode_handle *fwnode, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817147d0)
Location: drivers/base/property.c:873
Inline: False
```
**Symbols:**

```
ffffffff817147d0-ffffffff817147e5: fwnode_irq_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
