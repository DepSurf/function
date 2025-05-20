# Function: <code>ncsi_init_netlink</code>

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
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff819cb3c0)
Location: net/ncsi/ncsi-netlink.c:400
Inline: False
```
**Symbols:**

```
ffffffff819cb3c0-ffffffff819cb404: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81a04480)
Location: net/ncsi/ncsi-netlink.c:768
Inline: False
```
**Symbols:**

```
ffffffff81a04480-ffffffff81a044c4: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffff81a739d5-ffffffff81a739ef: ncsi_init_netlink.cold (STB_LOCAL)
ffffffff81a736e0-ffffffff81a7370e: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffff81aaa0c8-ffffffff81aaa0e2: ncsi_init_netlink.cold (STB_LOCAL)
ffffffff81aa9ed0-ffffffff81aa9efe: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffff81ba6411-ffffffff81ba642b: ncsi_init_netlink.cold (STB_LOCAL)
ffffffff81ba6180-ffffffff81ba61ac: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ncsi_init_netlink();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff8301f832)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffff8301f832-ffffffff8301f849: ncsi_init_netlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ncsi_init_netlink();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff8322a956)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffff8322a956-ffffffff8322a96d: ncsi_init_netlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ncsi_init_netlink();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff83315054)
Location: net/ncsi/ncsi-netlink.c:773
Inline: False
```
**Symbols:**

```
ffffffff83315054-ffffffff8331506b: ncsi_init_netlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ncsi_init_netlink();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff834cf5e8)
Location: net/ncsi/ncsi-netlink.c:773
Inline: False
```
**Symbols:**

```
ffffffff834cf5e8-ffffffff834cf605: ncsi_init_netlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ncsi_init_netlink();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff83f12e50)
Location: net/ncsi/ncsi-netlink.c:774
Inline: False
```
**Symbols:**

```
ffffffff83f12e50-ffffffff83f12e6d: ncsi_init_netlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ncsi_init_netlink();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff83739500)
Location: net/ncsi/ncsi-netlink.c:774
Inline: False
```
**Symbols:**

```
ffffffff83739500-ffffffff8373951d: ncsi_init_netlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ncsi_init_netlink();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff8396dce0)
Location: net/ncsi/ncsi-netlink.c:774
Inline: False
```
**Symbols:**

```
ffffffff8396dce0-ffffffff8396dcfd: ncsi_init_netlink (STB_LOCAL)
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
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffff800010d7dbc8)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffff800010d7dbc8-ffff800010d7dc18: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c0e7871c)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
c0e7871c-c0e78764: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c000000000ebd7a0)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
c000000000ebd7a0-c000000000ebd814: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab37c)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffe0008ab37c-ffffffe0008ab3ca: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffff81a49458-ffffffff81a49472: ncsi_init_netlink.cold (STB_LOCAL)
ffffffff81a49260-ffffffff81a4928e: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffff81a06048-ffffffff81a06062: ncsi_init_netlink.cold (STB_LOCAL)
ffffffff81a05e50-ffffffff81a05e7e: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffff81ab5308-ffffffff81ab5322: ncsi_init_netlink.cold (STB_LOCAL)
ffffffff81ab5110-ffffffff81ab513e: ncsi_init_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ncsi_init_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:769
Inline: False
```
**Symbols:**

```
ffffffff81ac16a8-ffffffff81ac16c2: ncsi_init_netlink.cold (STB_LOCAL)
ffffffff81ac14b0-ffffffff81ac14de: ncsi_init_netlink (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct net_device *dev</code>
</li>
</ul>
</details>
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
