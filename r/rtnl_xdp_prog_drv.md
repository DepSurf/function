# Function: <code>rtnl_xdp_prog_drv</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c9d40)
Location: net/core/rtnetlink.c:1381
Inline: False
```
**Symbols:**

```
ffffffff818c9d40-ffffffff818c9d63: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81916d30)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
ffffffff81916d30-ffffffff81916d53: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81949370)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
ffffffff81949370-ffffffff81949393: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1c122)
Location: net/core/rtnetlink.c:1417
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1c172)
Location: net/core/rtnetlink.c:1429
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a03292)
Location: net/core/rtnetlink.c:1431
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab4432)
Location: net/core/rtnetlink.c:1420
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2df83)
Location: net/core/rtnetlink.c:1460
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de1193)
Location: net/core/rtnetlink.c:1471
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e52883)
Location: net/core/rtnetlink.c:1482
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f11963)
Location: net/core/rtnetlink.c:1489
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
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
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010beade0)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
ffff800010beade0-ffff800010beae18: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d03b6c)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
c0d03b6c-c0d03b94: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cce0d0)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
c000000000cce0d0-c000000000cce110: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076e834)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
ffffffe00076e834-ffffffe00076e86a: rtnl_xdp_prog_drv (STB_LOCAL)
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
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e9340)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
ffffffff818e9340-ffffffff818e9363: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a3180)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
ffffffff818a3180-ffffffff818a31a3: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193a370)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
ffffffff8193a370-ffffffff8193a393: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_drv(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195bba0)
Location: net/core/rtnetlink.c:1379
Inline: False
```
**Symbols:**

```
ffffffff8195bba0-ffffffff8195bbc3: rtnl_xdp_prog_drv (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
