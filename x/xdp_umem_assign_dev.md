# Function: <code>xdp_umem_assign_dev</code>

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
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u32 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff819ccdc0)
Location: net/xdp/xdp_umem.c:43
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff819ccdc0-ffffffff819ccf19: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a05f10)
Location: net/xdp/xdp_umem.c:79
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a05f10-ffffffff81a06162: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a75630)
Location: net/xdp/xdp_umem.c:83
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a75630-ffffffff81a7587d: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81aac480)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81aac480-ffffffff81aac704: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ba8740)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ba8740-ffffffff81ba89b6: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
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
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffff800010d80d98)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffff800010d80d98-ffff800010d80fd0: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c0e7b294)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
c0e7b294-c0e7b4e0: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c000000000ec0a20)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
c000000000ec0a20-c000000000ec0da4: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffe0008ad2ea)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffe0008ad2ea-ffffffe0008ad4d0: xdp_umem_assign_dev (STB_GLOBAL)
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
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a4b810)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a4b810-ffffffff81a4ba94: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a08400)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a08400-ffffffff81a08684: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ab76c0)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ab76c0-ffffffff81ab7944: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xdp_umem_assign_dev(struct xdp_umem *umem, struct net_device *dev, u16 queue_id, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ac3ae0)
Location: net/xdp/xdp_umem.c:90
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ac3ae0-ffffffff81ac3d64: xdp_umem_assign_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 queue_id</code> ➡️ <code>u16 queue_id</code>
</li>
</ul>
</details>
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
