# Function: <code>dev_pre_changeaddr_notify</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ad920)
Location: net/core/dev.c:7776
Inline: True
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff818ad920-ffffffff818ad98c: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f9230)
Location: net/core/dev.c:7786
Inline: True
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff818f9230-ffffffff818f9298: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192b390)
Location: net/core/dev.c:8085
Inline: True
```
**Symbols:**

```
ffffffff8192b390-ffffffff8192b3f8: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01807)
Location: net/core/dev.c:8498
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mac_address
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff819ff070-ffffffff819ff0d3: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01c17)
Location: net/core/dev.c:8743
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mac_address
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff819fedd0-ffffffff819fee33: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e83ec)
Location: net/core/dev.c:9002
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mac_address
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff819e5670-ffffffff819e56d8: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a993ec)
Location: net/core/dev.c:8992
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mac_address
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff81a97250-ffffffff81a972b8: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1146c)
Location: net/core/dev.c:8756
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mac_address
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff81c0e120-ffffffff81c0e192: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc199c)
Location: net/core/dev.c:8743
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mac_address
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff81dbe0e0-ffffffff81dbe152: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e39f10)
Location: net/core/dev.c:8749
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mac_address
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff81e39e20-ffffffff81e39e92: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef8200)
Location: net/core/dev.c:8867
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mac_address
Direct callers:
  - net/core/dev_addr_lists.c:dev_addr_add
```
**Symbols:**

```
ffffffff81ef8110-ffffffff81ef8182: dev_pre_changeaddr_notify (STB_GLOBAL)
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
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc7ce8)
Location: net/core/dev.c:8085
Inline: True
```
**Symbols:**

```
ffff800010bc7ce8-ffff800010bc7d68: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce3384)
Location: net/core/dev.c:8085
Inline: True
```
**Symbols:**

```
c0ce3384-c0ce3404: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca3550)
Location: net/core/dev.c:8085
Inline: True
```
**Symbols:**

```
c000000000ca3550-c000000000ca35e0: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007541ca)
Location: net/core/dev.c:8085
Inline: True
```
**Symbols:**

```
ffffffe0007541ca-ffffffe000754232: dev_pre_changeaddr_notify (STB_GLOBAL)
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
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cb390)
Location: net/core/dev.c:8085
Inline: True
```
**Symbols:**

```
ffffffff818cb390-ffffffff818cb3f8: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818852d0)
Location: net/core/dev.c:8085
Inline: True
```
**Symbols:**

```
ffffffff818852d0-ffffffff81885338: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191c390)
Location: net/core/dev.c:8085
Inline: True
```
**Symbols:**

```
ffffffff8191c390-ffffffff8191c3f8: dev_pre_changeaddr_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dev_pre_changeaddr_notify(struct net_device *dev, const char *addr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193d870)
Location: net/core/dev.c:8085
Inline: True
```
**Symbols:**

```
ffffffff8193d870-ffffffff8193d8d8: dev_pre_changeaddr_notify (STB_GLOBAL)
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
