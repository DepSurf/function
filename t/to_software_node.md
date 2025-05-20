# Function: <code>to_software_node</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e3940)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffffffff816e3940-ffffffff816e3974: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81707b80)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffffffff81707b80-ffffffff81707bb4: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct software_node *to_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c2700)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffffffff817c2700-ffffffff817c2734: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct software_node *to_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d7460)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffffffff817d7460-ffffffff817d7494: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct software_node *to_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bafd0)
Location: drivers/base/swnode.c:88
Inline: False
```
**Symbols:**

```
ffffffff817bafd0-ffffffff817bb004: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct software_node *to_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81845240)
Location: drivers/base/swnode.c:90
Inline: False
```
**Symbols:**

```
ffffffff81845240-ffffffff81845274: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct software_node *to_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81989940)
Location: drivers/base/swnode.c:90
Inline: True
```
**Symbols:**

```
ffffffff81989940-ffffffff81989980: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct software_node *to_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af8c70)
Location: drivers/base/swnode.c:90
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
**Symbols:**

```
ffffffff81af8c70-ffffffff81af8cb0: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct software_node *to_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b471a0)
Location: drivers/base/swnode.c:90
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
**Symbols:**

```
ffffffff81b471a0-ffffffff81b471e0: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct software_node *to_software_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b9f500)
Location: drivers/base/swnode.c:90
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
**Symbols:**

```
ffffffff81b9f500-ffffffff81b9f540: to_software_node (STB_GLOBAL)
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
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f5510)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffff8000108f5510-ffff8000108f5570: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e1950)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
c09e1950-c09e19a0: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c00000000098fc20)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
c00000000098fc20-c00000000098fc70: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe0005866fa)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffffffe0005866fa-ffffffe000586744: to_software_node (STB_GLOBAL)
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
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd2d0)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffffffff816cd2d0-ffffffff816cd304: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a8600)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffffffff816a8600-ffffffff816a8634: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fb840)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffffffff816fb840-ffffffff816fb874: to_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct software_node *to_software_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716170)
Location: drivers/base/swnode.c:74
Inline: False
```
**Symbols:**

```
ffffffff81716170-ffffffff817161a4: to_software_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
