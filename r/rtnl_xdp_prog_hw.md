# Function: <code>rtnl_xdp_prog_hw</code>

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
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c9d10)
Location: net/core/rtnetlink.c:1386
Inline: False
```
**Symbols:**

```
ffffffff818c9d10-ffffffff818c9d33: rtnl_xdp_prog_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81916d00)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
ffffffff81916d00-ffffffff81916d23: rtnl_xdp_prog_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81949340)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
ffffffff81949340-ffffffff81949363: rtnl_xdp_prog_hw (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81a1c141)
Location: net/core/rtnetlink.c:1422
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
In net/core/rtnetlink.c (ffffffff81a1c183)
Location: net/core/rtnetlink.c:1434
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
In net/core/rtnetlink.c (ffffffff81a032a3)
Location: net/core/rtnetlink.c:1436
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
In net/core/rtnetlink.c (ffffffff81ab4443)
Location: net/core/rtnetlink.c:1425
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
In net/core/rtnetlink.c (ffffffff81c2df94)
Location: net/core/rtnetlink.c:1465
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
In net/core/rtnetlink.c (ffffffff81de11a4)
Location: net/core/rtnetlink.c:1476
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
In net/core/rtnetlink.c (ffffffff81e52894)
Location: net/core/rtnetlink.c:1487
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
In net/core/rtnetlink.c (ffffffff81f11974)
Location: net/core/rtnetlink.c:1494
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
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010beada8)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
ffff800010beada8-ffff800010beade0: rtnl_xdp_prog_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d03b44)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
c0d03b44-c0d03b6c: rtnl_xdp_prog_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cce090)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
c000000000cce090-c000000000cce0d0: rtnl_xdp_prog_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076e7fe)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
ffffffe00076e7fe-ffffffe00076e834: rtnl_xdp_prog_hw (STB_LOCAL)
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
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e9310)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
ffffffff818e9310-ffffffff818e9333: rtnl_xdp_prog_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a3150)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
ffffffff818a3150-ffffffff818a3173: rtnl_xdp_prog_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193a340)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
ffffffff8193a340-ffffffff8193a363: rtnl_xdp_prog_hw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_hw(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195bb70)
Location: net/core/rtnetlink.c:1384
Inline: False
```
**Symbols:**

```
ffffffff8195bb70-ffffffff8195bb93: rtnl_xdp_prog_hw (STB_LOCAL)
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
