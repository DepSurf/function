# Function: <code>switchdev_port_attr_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: include/net/switchdev.h:217
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/net/switchdev.h:217
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int switchdev_port_attr_get(struct net_device *dev, struct switchdev_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8188a220)
Location: net/switchdev/switchdev.c:184
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_get_dev_by_nhs
  - net/switchdev/switchdev.c:switchdev_port_br_setflag
  - net/switchdev/switchdev.c:switchdev_port_bridge_getlink
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff8188a220-ffffffff8188a36a: switchdev_port_attr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int switchdev_port_attr_get(struct net_device *dev, struct switchdev_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818be8f0)
Location: net/switchdev/switchdev.c:183
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_br_setflag
  - net/switchdev/switchdev.c:switchdev_port_bridge_getlink
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff818be8f0-ffffffff818bea3a: switchdev_port_attr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int switchdev_port_attr_get(struct net_device *dev, struct switchdev_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818e5350)
Location: net/switchdev/switchdev.c:183
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_br_setflag
  - net/switchdev/switchdev.c:switchdev_port_bridge_getlink
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff818e5350-ffffffff818e549a: switchdev_port_attr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int switchdev_port_attr_get(struct net_device *dev, struct switchdev_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8196af30)
Location: net/switchdev/switchdev.c:183
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/ipv4/ipmr.c:vif_add
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff8196af30-ffffffff8196b07d: switchdev_port_attr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int switchdev_port_attr_get(struct net_device *dev, struct switchdev_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819c4ab0)
Location: net/switchdev/switchdev.c:183
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/ipv4/ipmr.c:vif_add
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff819c4ab0-ffffffff819c4bfd: switchdev_port_attr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int switchdev_port_attr_get(struct net_device *dev, struct switchdev_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fc130)
Location: net/switchdev/switchdev.c:183
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_phys_switch_id_fill
  - net/ipv4/ipmr.c:vif_add
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_same_parent_id
  - net/switchdev/switchdev.c:switchdev_port_attr_get
```
**Symbols:**

```
ffffffff819fc130-ffffffff819fc27d: switchdev_port_attr_get (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
</ul>
