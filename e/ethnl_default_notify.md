# Function: <code>ethnl_default_notify</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ethnl_default_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a86670)
Location: net/ethtool/netlink.c:555
Inline: False
```
**Symbols:**

```
ffffffff81a86670-ffffffff81a868c7: ethnl_default_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ethnl_default_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a8ff80)
Location: net/ethtool/netlink.c:557
Inline: False
```
**Symbols:**

```
ffffffff81a8ff80-ffffffff81a901d7: ethnl_default_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ethnl_default_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a796a0)
Location: net/ethtool/netlink.c:562
Inline: False
```
**Symbols:**

```
ffffffff81a796a0-ffffffff81a798f1: ethnl_default_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ethnl_default_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:600
Inline: False
```
**Symbols:**

```
ffffffff81b33a20-ffffffff81b33cc5: ethnl_default_notify (STB_LOCAL)
ffffffff81d3973a-ffffffff81d3976b: ethnl_default_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ethnl_default_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:604
Inline: False
```
**Symbols:**

```
ffffffff81cbf150-ffffffff81cbf417: ethnl_default_notify (STB_LOCAL)
ffffffff81f05eb5-ffffffff81f05ee6: ethnl_default_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ethnl_default_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:609
Inline: False
```
**Symbols:**

```
ffffffff81e7dcf0-ffffffff81e7dfb7: ethnl_default_notify (STB_LOCAL)
ffffffff820adbb8-ffffffff820adbe9: ethnl_default_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ethnl_default_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:677
Inline: False
```
**Symbols:**

```
ffffffff81eda2b0-ffffffff81eda580: ethnl_default_notify (STB_LOCAL)
ffffffff8212ee06-ffffffff8212ee37: ethnl_default_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ethnl_default_notify(struct net_device *dev, unsigned int cmd, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:645
Inline: False
```
**Symbols:**

```
ffffffff81f9e050-ffffffff81f9e353: ethnl_default_notify (STB_LOCAL)
ffffffff82210b91-ffffffff82210bc8: ethnl_default_notify.cold (STB_LOCAL)
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
