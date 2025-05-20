# Function: <code>ipmr_del_tunnel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a80c4)
Location: net/ipv4/ipmr.c:359
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818908a6)
Location: net/ipv4/ipmr.c:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818c4ec0)
Location: net/ipv4/ipmr.c:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81869297)
Location: net/ipv4/ipmr.c:365
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818e8980)
Location: net/ipv4/ipmr.c:397
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff818e8980-ffffffff818e8a9d: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8193f0d0)
Location: net/ipv4/ipmr.c:423
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff8193f0d0-ffffffff8193f1d6: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196ed80)
Location: net/ipv4/ipmr.c:426
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff8196ed80-ffffffff8196ee86: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819d8e10)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff819d8e10-ffffffff819d8f16: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a0fb80)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff81a0fb80-ffffffff81a0fc86: ipmr_del_tunnel (STB_LOCAL)
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
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010ccc6d0)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffff800010ccc6d0-ffff800010ccc840: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd4578)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
c0dd4578-c0dd4694: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de6740)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
c000000000de6740-c000000000de68d4: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081d520)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffe00081d520-ffffffe00081d5ec: ipmr_del_tunnel (STB_LOCAL)
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
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819af5a0)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff819af5a0-ffffffff819af6a6: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196bbd0)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff8196bbd0-ffffffff8196bcd6: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a19e40)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff81a19e40-ffffffff81a19f46: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipmr_del_tunnel(struct net_device *dev, struct vifctl *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a24c70)
Location: net/ipv4/ipmr.c:420
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff81a24c70-ffffffff81a24d76: ipmr_del_tunnel (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
