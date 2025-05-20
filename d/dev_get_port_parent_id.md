# Function: <code>dev_get_port_parent_id</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fa500)
Location: net/core/dev.c:7902
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff818fa500-ffffffff818fa653: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192c640)
Location: net/core/dev.c:8201
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff8192c640-ffffffff8192c793: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ffc30)
Location: net/core/dev.c:8614
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff819ffc30-ffffffff819ffd7f: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ff990)
Location: net/core/dev.c:8901
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff819ff990-ffffffff819ffadf: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e6170)
Location: net/core/dev.c:9160
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff819e6170-ffffffff819e62be: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a966a0)
Location: net/core/dev.c:9150
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff81a966a0-ffffffff81a967ee: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0d530)
Location: net/core/dev.c:8911
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff81c0d530-ffffffff81c0d68c: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbd160)
Location: net/core/dev.c:8898
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff81dbd160-ffffffff81dbd2bf: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2d990)
Location: net/core/dev.c:8906
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff81e2d990-ffffffff81e2daef: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eebce0)
Location: net/core/dev.c:9024
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff81eebce0-ffffffff81eebe3c: dev_get_port_parent_id (STB_GLOBAL)
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
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc8c08)
Location: net/core/dev.c:8201
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffff800010bc8c08-ffff800010bc8d84: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce4e30)
Location: net/core/dev.c:8201
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
c0ce4e30-c0ce4fa4: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca5570)
Location: net/core/dev.c:8201
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
c000000000ca5570-c000000000ca578c: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075540c)
Location: net/core/dev.c:8201
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffe00075540c-ffffffe0007554e4: dev_get_port_parent_id (STB_GLOBAL)
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
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cc640)
Location: net/core/dev.c:8201
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff818cc640-ffffffff818cc793: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818866d0)
Location: net/core/dev.c:8201
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff818866d0-ffffffff81886823: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191d640)
Location: net/core/dev.c:8201
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff8191d640-ffffffff8191d793: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_get_port_parent_id(struct net_device *dev, struct netdev_phys_item_id *ppid, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193eb50)
Location: net/core/dev.c:8201
Inline: False
Direct callers:
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:netdev_port_same_parent_id
  - net/core/dev.c:dev_get_port_parent_id
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff8193eb50-ffffffff8193eca3: dev_get_port_parent_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
