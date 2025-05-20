# Function: <code>extend_netdev_table</code>

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
In net/core/netprio_cgroup.c (ffffffff8173db82)
Location: net/core/netprio_cgroup.c:37
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff817aa3b2)
Location: net/core/netprio_cgroup.c:42
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff817d8ef2)
Location: net/core/netprio_cgroup.c:42
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff817f8114)
Location: net/core/netprio_cgroup.c:46
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff818759d4)
Location: net/core/netprio_cgroup.c:45
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff818c7074)
Location: net/core/netprio_cgroup.c:45
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff818f01e4)
Location: net/core/netprio_cgroup.c:45
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff81941b53)
Location: net/core/netprio_cgroup.c:41
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff81976a63)
Location: net/core/netprio_cgroup.c:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int extend_netdev_table(struct net_device *dev, u32 target_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netprio_cgroup.c (ffffffff81a4b750)
Location: net/core/netprio_cgroup.c:41
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
```
**Symbols:**

```
ffffffff81a4b750-ffffffff81a4b7ff: extend_netdev_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int extend_netdev_table(struct net_device *dev, u32 target_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netprio_cgroup.c (ffffffff81a513a0)
Location: net/core/netprio_cgroup.c:41
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
```
**Symbols:**

```
ffffffff81a513a0-ffffffff81a5144f: extend_netdev_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int extend_netdev_table(struct net_device *dev, u32 target_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netprio_cgroup.c (ffffffff81a36c10)
Location: net/core/netprio_cgroup.c:41
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
```
**Symbols:**

```
ffffffff81a36c10-ffffffff81a36cbf: extend_netdev_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int extend_netdev_table(struct net_device *dev, u32 target_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netprio_cgroup.c (ffffffff81aec9a0)
Location: net/core/netprio_cgroup.c:41
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
```
**Symbols:**

```
ffffffff81aec9a0-ffffffff81aeca4f: extend_netdev_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int extend_netdev_table(struct net_device *dev, u32 target_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netprio_cgroup.c (ffffffff81c6f4e0)
Location: net/core/netprio_cgroup.c:41
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
```
**Symbols:**

```
ffffffff81c6f4e0-ffffffff81c6f598: extend_netdev_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int extend_netdev_table(struct net_device *dev, u32 target_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netprio_cgroup.c (ffffffff81e27320)
Location: net/core/netprio_cgroup.c:41
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
```
**Symbols:**

```
ffffffff81e27320-ffffffff81e273d8: extend_netdev_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int extend_netdev_table(struct net_device *dev, u32 target_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/netprio_cgroup.c (0)
Location: net/core/netprio_cgroup.c:41
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
```
**Symbols:**

```
ffffffff81e9c890-ffffffff81e9c9e4: extend_netdev_table (STB_LOCAL)
ffffffff8212e430-ffffffff8212e463: extend_netdev_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int extend_netdev_table(struct net_device *dev, u32 target_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netprio_cgroup.c (ffffffff81f5f030)
Location: net/core/netprio_cgroup.c:41
Inline: False
Direct callers:
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
```
**Symbols:**

```
ffffffff81f5f030-ffffffff81f5f10a: extend_netdev_table (STB_LOCAL)
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
In net/core/netprio_cgroup.c (ffff800010c1d078)
Location: net/core/netprio_cgroup.c:41
Inline: True
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
In net/core/netprio_cgroup.c (c0d35094)
Location: net/core/netprio_cgroup.c:41
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_set_prio
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
In net/core/netprio_cgroup.c (c000000000d0e3a0)
Location: net/core/netprio_cgroup.c:41
Inline: True
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
In net/core/netprio_cgroup.c (ffffffe000796eac)
Location: net/core/netprio_cgroup.c:41
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff819168d3)
Location: net/core/netprio_cgroup.c:41
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff818d0683)
Location: net/core/netprio_cgroup.c:41
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff81967a63)
Location: net/core/netprio_cgroup.c:41
Inline: True
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
In net/core/netprio_cgroup.c (ffffffff81989da3)
Location: net/core/netprio_cgroup.c:41
Inline: True
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
