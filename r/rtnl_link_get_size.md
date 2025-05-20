# Function: <code>rtnl_link_get_size</code>

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
In net/core/rtnetlink.c (ffffffff8172b76f)
Location: net/core/rtnetlink.c:423
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
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
In net/core/rtnetlink.c (ffffffff81794ef4)
Location: net/core/rtnetlink.c:445
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
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
In net/core/rtnetlink.c (ffffffff817c2767)
Location: net/core/rtnetlink.c:446
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
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
In net/core/rtnetlink.c (ffffffff817e0e95)
Location: net/core/rtnetlink.c:448
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185b54e)
Location: net/core/rtnetlink.c:425
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a6d7d)
Location: net/core/rtnetlink.c:508
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ca40d)
Location: net/core/rtnetlink.c:518
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819173bd)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819499fd)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t rtnl_link_get_size(const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18c30)
Location: net/core/rtnetlink.c:513
Inline: False
Direct callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
**Symbols:**

```
ffffffff81a18c30-ffffffff81a18ce7: rtnl_link_get_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t rtnl_link_get_size(const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18ce0)
Location: net/core/rtnetlink.c:515
Inline: False
Direct callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
**Symbols:**

```
ffffffff81a18ce0-ffffffff81a18d9c: rtnl_link_get_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t rtnl_link_get_size(const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819ffbc0)
Location: net/core/rtnetlink.c:515
Inline: False
Direct callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
**Symbols:**

```
ffffffff819ffbc0-ffffffff819ffc7c: rtnl_link_get_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t rtnl_link_get_size(const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab1ed0)
Location: net/core/rtnetlink.c:515
Inline: False
Direct callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
**Symbols:**

```
ffffffff81ab1ed0-ffffffff81ab1f8c: rtnl_link_get_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t rtnl_link_get_size(const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2b1d0)
Location: net/core/rtnetlink.c:552
Inline: False
Direct callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
**Symbols:**

```
ffffffff81c2b1d0-ffffffff81c2b29d: rtnl_link_get_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t rtnl_link_get_size(const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81dddd50)
Location: net/core/rtnetlink.c:553
Inline: False
Direct callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
**Symbols:**

```
ffffffff81dddd50-ffffffff81ddde1d: rtnl_link_get_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t rtnl_link_get_size(const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4ec90)
Location: net/core/rtnetlink.c:556
Inline: False
Direct callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
**Symbols:**

```
ffffffff81e4ec90-ffffffff81e4ed5d: rtnl_link_get_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t rtnl_link_get_size(const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0db60)
Location: net/core/rtnetlink.c:551
Inline: False
Direct callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
**Symbols:**

```
ffffffff81f0db60-ffffffff81f0dc2d: rtnl_link_get_size (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010beb534)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d03458)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccd6a8)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076e25e)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e99cd)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a380d)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193a9fd)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195c229)
Location: net/core/rtnetlink.c:513
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
```
</details>
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
