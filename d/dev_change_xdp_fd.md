# Function: <code>dev_change_xdp_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177e260)
Location: net/core/dev.c:6638
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8177e260-ffffffff8177e328: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ab9e0)
Location: net/core/dev.c:6792
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff817ab9e0-ffffffff817abb2e: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d27c0)
Location: net/core/dev.c:6992
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff817d27c0-ffffffff817d29a4: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184cae0)
Location: net/core/dev.c:7156
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8184cae0-ffffffff8184cd37: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81896e10)
Location: net/core/dev.c:7349
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81896e10-ffffffff81897080: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b92c0)
Location: net/core/dev.c:7972
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff818b92c0-ffffffff818b94d1: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81905440)
Location: net/core/dev.c:8069
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81905440-ffffffff81905676: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81937b00)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81937b00-ffffffff81937d69: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, int expected_fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0c640)
Location: net/core/dev.c:8799
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81a0c640-ffffffff81a0c931: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, int expected_fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0dec0)
Location: net/core/dev.c:9466
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81a0dec0-ffffffff81a0e0e8: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, int expected_fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f4be0)
Location: net/core/dev.c:9731
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff819f4be0-ffffffff819f4e08: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, int expected_fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9738
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81d3673d-ffffffff81d36758: dev_change_xdp_fd.cold (STB_LOCAL)
ffffffff81aa6510-ffffffff81aa6742: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, int expected_fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9476
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81f02f66-ffffffff81f02f81: dev_change_xdp_fd.cold (STB_LOCAL)
ffffffff81c1e2c0-ffffffff81c1e4d2: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, int expected_fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9463
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff820ab812-ffffffff820ab82d: dev_change_xdp_fd.cold (STB_LOCAL)
ffffffff81dcf710-ffffffff81dcf922: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, int expected_fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9475
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8212cf4c-ffffffff8212cf67: dev_change_xdp_fd.cold (STB_LOCAL)
ffffffff81e40320-ffffffff81e40526: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, int expected_fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9595
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8220ec9c-ffffffff8220ecb7: dev_change_xdp_fd.cold (STB_LOCAL)
ffffffff81efed20-ffffffff81efef23: dev_change_xdp_fd (STB_GLOBAL)
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
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd6590)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffff800010bd6590-ffff800010bd67f0: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf110c)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
c0cf110c-c0cf139c: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb5f70)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
c000000000cb5f70-c000000000cb631c: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075fca0)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffe00075fca0-ffffffe00075feb8: dev_change_xdp_fd (STB_GLOBAL)
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
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d7ad0)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff818d7ad0-ffffffff818d7d39: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81891910)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81891910-ffffffff81891b79: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81928b00)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81928b00-ffffffff81928d69: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_change_xdp_fd(struct net_device *dev, struct netlink_ext_ack *extack, int fd, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194a1d0)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8194a1d0-ffffffff8194a439: dev_change_xdp_fd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, fd, flags</code> ➡️ <code>dev, extack, fd, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int expected_fd</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, extack, fd, flags</code> ➡️ <code>dev, extack, fd, expected_fd, flags</code>
</li>
</ul>
</details>
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
