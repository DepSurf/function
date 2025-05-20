# Function: <code>dev_change_tx_queue_len</code>

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
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81896cf0)
Location: net/core/dev.c:7140
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81896cf0-ffffffff81896db8: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b91d0)
Location: net/core/dev.c:7732
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff818b91d0-ffffffff818b9298: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7742
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81907631-ffffffff8190765b: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff81905380-ffffffff8190541b: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8041
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81939c18-ffffffff81939c42: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff81937a40-ffffffff81937adb: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8454
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81a0f1b8-ffffffff81a0f1e0: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff81a0c580-ffffffff81a0c61d: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8699
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81c31503-ffffffff81c3152b: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff81a0dc40-ffffffff81a0dcdd: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8958
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81c237e8-ffffffff81c23810: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff819f4950-ffffffff819f49ed: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8948
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81d36715-ffffffff81d3673d: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff81aa6280-ffffffff81aa631d: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8713
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:tx_queue_len_store
```
**Symbols:**

```
ffffffff81f02ee7-ffffffff81f02f0f: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff81c1dd50-ffffffff81c1ddfb: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcf0c0)
Location: net/core/dev.c:8700
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:tx_queue_len_store
```
**Symbols:**

```
ffffffff81dcf0c0-ffffffff81dcf19a: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3fcf0)
Location: net/core/dev.c:8706
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:tx_queue_len_store
```
**Symbols:**

```
ffffffff81e3fcf0-ffffffff81e3fdca: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efe650)
Location: net/core/dev.c:8824
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:tx_queue_len_store
```
**Symbols:**

```
ffffffff81efe650-ffffffff81efe72a: dev_change_tx_queue_len (STB_GLOBAL)
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
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd6470)
Location: net/core/dev.c:8041
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffff800010bd6470-ffff800010bd653c: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf1024)
Location: net/core/dev.c:8041
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
c0cf1024-c0cf10e0: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb5e20)
Location: net/core/dev.c:8041
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
c000000000cb5e20-c000000000cb5f38: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075fbc0)
Location: net/core/dev.c:8041
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffe00075fbc0-ffffffe00075fc60: dev_change_tx_queue_len (STB_GLOBAL)
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
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8041
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff818d9be8-ffffffff818d9c12: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff818d7a10-ffffffff818d7aab: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8041
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81893a28-ffffffff81893a52: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff81891850-ffffffff818918eb: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8041
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8192ac18-ffffffff8192ac42: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff81928a40-ffffffff81928adb: dev_change_tx_queue_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dev_change_tx_queue_len(struct net_device *dev, long unsigned int new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8041
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8194c2e8-ffffffff8194c312: dev_change_tx_queue_len.cold (STB_LOCAL)
ffffffff8194a110-ffffffff8194a1ab: dev_change_tx_queue_len (STB_GLOBAL)
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
