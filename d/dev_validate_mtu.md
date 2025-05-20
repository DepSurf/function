# Function: <code>dev_validate_mtu</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81937817)
Location: net/core/dev.c:7960
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81937790-ffffffff819377dd: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0c362)
Location: net/core/dev.c:8373
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81a0c2e0-ffffffff81a0c32d: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0da32)
Location: net/core/dev.c:8618
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81a0d9b0-ffffffff81a0d9fd: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f4707)
Location: net/core/dev.c:8877
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff819f4650-ffffffff819f46c9: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa6037)
Location: net/core/dev.c:8867
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81aa5f80-ffffffff81aa5ff9: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1db07)
Location: net/core/dev.c:8632
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81c1da40-ffffffff81c1dac8: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcee33)
Location: net/core/dev.c:8619
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81dced60-ffffffff81dcede8: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3fa67)
Location: net/core/dev.c:8625
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81e3f990-ffffffff81e3fa18: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efe3c4)
Location: net/core/dev.c:8743
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81efe2f0-ffffffff81efe378: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd626c)
Location: net/core/dev.c:7960
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffff800010bd6198-ffff800010bd6228: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf0dfc)
Location: net/core/dev.c:7960
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
c0cf0d30-c0cf0dbc: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb5b0c)
Location: net/core/dev.c:7960
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
c000000000cb5a50-c000000000cb5acc: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075fa3a)
Location: net/core/dev.c:7960
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffe00075f99e-ffffffe00075fa0e: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d77e7)
Location: net/core/dev.c:7960
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff818d7760-ffffffff818d77ad: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81891627)
Location: net/core/dev.c:7960
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff818915a0-ffffffff818915ed: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81928817)
Location: net/core/dev.c:7960
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81928790-ffffffff819287dd: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dev_validate_mtu(struct net_device *dev, int new_mtu, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81949ee7)
Location: net/core/dev.c:7960
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
Direct callers:
  - net/core/rtnetlink.c:rtnl_create_link
```
**Symbols:**

```
ffffffff81949e60-ffffffff81949ead: dev_validate_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
