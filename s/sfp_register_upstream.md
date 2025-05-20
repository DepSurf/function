# Function: <code>sfp_register_upstream</code>

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
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, struct net_device *ndev, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8173b020)
Location: drivers/net/phy/sfp-bus.c:458
Inline: False
```
**Symbols:**

```
ffffffff8173b020-ffffffff8173b0c5: sfp_register_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, struct net_device *ndev, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8175e660)
Location: drivers/net/phy/sfp-bus.c:461
Inline: False
```
**Symbols:**

```
ffffffff8175e660-ffffffff8175e6ee: sfp_register_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8179bcd0)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff8179bcd0-ffffffff8179bd4f: sfp_register_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817bf780)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff817bf780-ffffffff817bf7ff: sfp_register_upstream (STB_GLOBAL)
```
</details>
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
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffff8000109d9c10)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
ffff8000109d9c10-ffff8000109d9ca0: sfp_register_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c0ac0814)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
c0ac0814-c0ac0894: sfp_register_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c000000000a9baa0)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
c000000000a9baa0-c000000000a9bb78: sfp_register_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffe000624aea)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
ffffffe000624aea-ffffffe000624b7a: sfp_register_upstream (STB_GLOBAL)
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
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81784250)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff81784250-ffffffff817842cf: sfp_register_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81763ba0)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff81763ba0-ffffffff81763c1f: sfp_register_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817b4600)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff817b4600-ffffffff817b467f: sfp_register_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sfp_bus *sfp_register_upstream(struct fwnode_handle *fwnode, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817ce5d0)
Location: drivers/net/phy/sfp-bus.c:459
Inline: False
```
**Symbols:**

```
ffffffff817ce5d0-ffffffff817ce64f: sfp_register_upstream (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct net_device *ndev</code>
</li>
<li>
<b>Param reordered. </b>
<code>fwnode, ndev, upstream, ops</code> ➡️ <code>fwnode, upstream, ops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
