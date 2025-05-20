# Function: <code>is_unicast_ether_addr</code>

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
In net/core/rtnetlink.c (ffffffff8172a970)
Location: include/linux/etherdevice.h:173
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
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
In net/core/rtnetlink.c (ffffffff8179447f)
Location: include/linux/etherdevice.h:173
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff817c1cff)
Location: include/linux/etherdevice.h:173
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff817e048f)
Location: include/linux/etherdevice.h:178
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff8185acff)
Location: include/linux/etherdevice.h:179
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff818a65b3)
Location: include/linux/etherdevice.h:179
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff818c9e03)
Location: include/linux/etherdevice.h:179
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff81916dfd)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff8194943d)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1931f)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1950f)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
```
In net/core/devlink.c (ffffffff81a668f3)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a0041f)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
```
In net/core/devlink.c (ffffffff81a46822)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_function_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab256f)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
```
In net/core/devlink.c (ffffffff81b0158c)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_function_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2b5ce)
Location: include/linux/etherdevice.h:182
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
```
In net/core/devlink.c (ffffffff81c80b4b)
Location: include/linux/etherdevice.h:182
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_function_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81dde1ca)
Location: include/linux/etherdevice.h:182
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
```
In net/core/devlink.c (ffffffff81e3dadb)
Location: include/linux/etherdevice.h:182
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_function_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4f10a)
Location: include/linux/etherdevice.h:182
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
```
In net/devlink/leftover.c (ffffffff8203d6c0)
Location: include/linux/etherdevice.h:182
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_port_function_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0dfda)
Location: include/linux/etherdevice.h:182
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
```
In net/devlink/port.c (ffffffff821070bc)
Location: include/linux/etherdevice.h:182
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_function_set
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
In net/core/rtnetlink.c (ffff800010beaf1c)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (c0d03c7c)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (c000000000cce25c)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffe00076e960)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff818e940d)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff818a324d)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff8193a43d)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
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
In net/core/rtnetlink.c (ffffffff8195bc6d)
Location: include/linux/etherdevice.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_del
  - net/core/rtnetlink.c:ndo_dflt_fdb_add
```
</details>
</li>
</ul>

## Differences
