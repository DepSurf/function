# Function: <code>devlink_compat_switch_id_get</code>

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
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81951ef0)
Location: net/core/devlink.c:6939
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff81951ef0-ffffffff81951f9c: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81988930)
Location: net/core/devlink.c:8103
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff81988930-ffffffff8198899d: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a60590)
Location: net/core/devlink.c:9334
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff81a60590-ffffffff81a60603: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a68e70)
Location: net/core/devlink.c:10297
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff81a68e70-ffffffff81a68ee6: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4c230)
Location: net/core/devlink.c:10561
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff81a4c230-ffffffff81a4c2a6: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b046e0)
Location: net/core/devlink.c:11503
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff81b046e0-ffffffff81b04756: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c89f50)
Location: net/core/devlink.c:12088
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff81c89f50-ffffffff81c89fd6: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e44b40)
Location: net/core/devlink.c:12969
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff81e44b40-ffffffff81e44ba7: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82041c10)
Location: net/devlink/leftover.c:9494
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff82041c10-ffffffff82041c77: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff82108370)
Location: net/devlink/port.c:1551
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff82108370-ffffffff821083d7: devlink_compat_switch_id_get (STB_GLOBAL)
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
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c308f0)
Location: net/core/devlink.c:8103
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffff800010c308f0-ffff800010c30968: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d478f8)
Location: net/core/devlink.c:8103
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
c0d478f8-c0d4798c: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d29810)
Location: net/core/devlink.c:8103
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
c000000000d29810-c000000000d298d8: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a6a44)
Location: net/core/devlink.c:8103
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffe0007a6a44-ffffffe0007a6aa6: devlink_compat_switch_id_get (STB_GLOBAL)
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
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819287a0)
Location: net/core/devlink.c:8103
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff819287a0-ffffffff8192880d: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e2550)
Location: net/core/devlink.c:8103
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff818e2550-ffffffff818e25bd: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81979930)
Location: net/core/devlink.c:8103
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff81979930-ffffffff8197999d: devlink_compat_switch_id_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_compat_switch_id_get(struct net_device *dev, struct netdev_phys_item_id *ppid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199be20)
Location: net/core/devlink.c:8103
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_port_parent_id
```
**Symbols:**

```
ffffffff8199be20-ffffffff8199be8d: devlink_compat_switch_id_get (STB_GLOBAL)
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
