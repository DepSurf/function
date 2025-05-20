# Function: <code>xennet_xdp_xmit</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xennet_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a8800)
Location: drivers/net/xen-netfront.c:604
Inline: True
```
**Symbols:**

```
ffffffff818a8800-ffffffff818a88e9: xennet_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xennet_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8188a060)
Location: drivers/net/xen-netfront.c:604
Inline: False
```
**Symbols:**

```
ffffffff8188a060-ffffffff8188a24b: xennet_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xennet_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:638
Inline: False
```
**Symbols:**

```
ffffffff8191d6a0-ffffffff8191d93d: xennet_xdp_xmit (STB_LOCAL)
ffffffff81d11332-ffffffff81d1134d: xennet_xdp_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xennet_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:644
Inline: False
```
**Symbols:**

```
ffffffff81a72230-ffffffff81a724fa: xennet_xdp_xmit (STB_LOCAL)
ffffffff81edbfd9-ffffffff81edbffa: xennet_xdp_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xennet_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:644
Inline: False
```
**Symbols:**

```
ffffffff81c06660-ffffffff81c0692a: xennet_xdp_xmit (STB_LOCAL)
ffffffff8209db6a-ffffffff8209db8b: xennet_xdp_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xennet_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:644
Inline: False
```
**Symbols:**

```
ffffffff81c6bd70-ffffffff81c6c03a: xennet_xdp_xmit (STB_LOCAL)
ffffffff8211f0f2-ffffffff8211f113: xennet_xdp_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xennet_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:645
Inline: False
```
**Symbols:**

```
ffffffff81d20720-ffffffff81d209e7: xennet_xdp_xmit (STB_LOCAL)
ffffffff822008c8-ffffffff822008e9: xennet_xdp_xmit.cold (STB_LOCAL)
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
