# Function: <code>tun_xdp_xmit</code>

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
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173cce0)
Location: drivers/net/tun.c:1300
Inline: False
```
**Symbols:**

```
ffffffff8173cce0-ffffffff8173ce5b: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81760780)
Location: drivers/net/tun.c:1293
Inline: False
```
**Symbols:**

```
ffffffff81760780-ffffffff817608fb: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8179df60)
Location: drivers/net/tun.c:1281
Inline: True
```
**Symbols:**

```
ffffffff8179df60-ffffffff8179e0cc: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff8179e0d0-ffffffff8179e0ee: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817c19f0)
Location: drivers/net/tun.c:1281
Inline: True
```
**Symbols:**

```
ffffffff817c19f0-ffffffff817c1b5c: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff817c1b60-ffffffff817c1b7e: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8188cc29)
Location: drivers/net/tun.c:1247
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff8188c910-ffffffff8188ca83: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff8188ca90-ffffffff8188caae: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8189ae80)
Location: drivers/net/tun.c:1178
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff8189ab80-ffffffff8189acfe: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff8189ad00-ffffffff8189ad1e: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8187d6dd)
Location: drivers/net/tun.c:1186
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff8187d400-ffffffff8187d560: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff8187d560-ffffffff8187d57e: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8190ed5a)
Location: drivers/net/tun.c:1241
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff8190ea50-ffffffff8190ebd9: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff8190ebe0-ffffffff8190ebfe: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81a62510)
Location: drivers/net/tun.c:1269
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a60f50-ffffffff81a61109: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff81a61110-ffffffff81a6116c: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81becca8)
Location: drivers/net/tun.c:1271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81bec240-ffffffff81bec3f9: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff81bec410-ffffffff81bec46c: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81c451a8)
Location: drivers/net/tun.c:1271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81c44730-ffffffff81c448ed: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff81c44900-ffffffff81c4495c: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfa3fe)
Location: drivers/net/tun.c:1272
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81cfa020-ffffffff81cfa1ac: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff81cfa1c0-ffffffff81cfa21c: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffff8000109dc310)
Location: drivers/net/tun.c:1281
Inline: True
```
**Symbols:**

```
ffff8000109dc310-ffff8000109dc4d0: tun_xdp_xmit.part.0 (STB_LOCAL)
ffff8000109dc4d0-ffff8000109dc538: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (c0ac3188)
Location: drivers/net/tun.c:1281
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
c0ac2e30-c0ac2fa4: tun_xdp_xmit.part.0 (STB_LOCAL)
c0ac2fa4-c0ac2fd0: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (c000000000a9e818)
Location: drivers/net/tun.c:1281
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
c000000000a9e420-c000000000a9e658: tun_xdp_xmit.part.0 (STB_LOCAL)
c000000000a9e660-c000000000a9e688: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffe00062772a)
Location: drivers/net/tun.c:1281
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffe0006273d0-ffffffe000627566: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffe000627566-ffffffe0006275c0: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817864c0)
Location: drivers/net/tun.c:1281
Inline: True
```
**Symbols:**

```
ffffffff817864c0-ffffffff8178662c: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff81786630-ffffffff8178664e: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81765e10)
Location: drivers/net/tun.c:1281
Inline: True
```
**Symbols:**

```
ffffffff81765e10-ffffffff81765f7c: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff81765f80-ffffffff81765f9e: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817b6870)
Location: drivers/net/tun.c:1281
Inline: True
```
**Symbols:**

```
ffffffff817b6870-ffffffff817b69dc: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff817b69e0-ffffffff817b69fe: tun_xdp_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tun_xdp_xmit(struct net_device *dev, int n, struct xdp_frame **frames, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817d0a30)
Location: drivers/net/tun.c:1281
Inline: True
```
**Symbols:**

```
ffffffff817d0a30-ffffffff817d0bb6: tun_xdp_xmit.part.0 (STB_LOCAL)
ffffffff817d0bc0-ffffffff817d0c0b: tun_xdp_xmit (STB_LOCAL)
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
