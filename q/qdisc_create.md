# Function: <code>qdisc_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81744fe0)
Location: net/sched/sch_api.c:889
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81744fe0-ffffffff817453ee: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b1ec0)
Location: net/sched/sch_api.c:888
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff817b1ec0-ffffffff817b229c: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817e15f0)
Location: net/sched/sch_api.c:893
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff817e15f0-ffffffff817e1a48: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81800b60)
Location: net/sched/sch_api.c:889
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81800b60-ffffffff81800fb7: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187e960)
Location: net/sched/sch_api.c:984
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff8187e960-ffffffff8187eceb: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818d1540)
Location: net/sched/sch_api.c:1059
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff818d1540-ffffffff818d19bf: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fc8c0)
Location: net/sched/sch_api.c:1144
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff818fc8c0-ffffffff818fcd3f: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff8195c260-ffffffff8195c6e3: qdisc_create (STB_LOCAL)
ffffffff8195cf46-ffffffff8195cf65: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff819927b0-ffffffff81992c33: qdisc_create (STB_LOCAL)
ffffffff8199344d-ffffffff8199346c: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1157
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81a69db0-ffffffff81a6a2c0: qdisc_create (STB_LOCAL)
ffffffff81a6b63d-ffffffff81a6b65b: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1158
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81a72500-ffffffff81a729e7: qdisc_create (STB_LOCAL)
ffffffff81c321ad-ffffffff81c321cd: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1158
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81a5ad70-ffffffff81a5b336: qdisc_create (STB_LOCAL)
ffffffff81c24497-ffffffff81c244b6: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1164
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81b13f20-ffffffff81b144f5: qdisc_create (STB_LOCAL)
ffffffff81d39034-ffffffff81d3906e: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1164
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81c9b390-ffffffff81c9b876: qdisc_create.constprop.0 (STB_LOCAL)
ffffffff81f05874-ffffffff81f05894: qdisc_create.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e57880)
Location: net/sched/sch_api.c:1189
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81e57880-ffffffff81e57da8: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb1bc0)
Location: net/sched/sch_api.c:1223
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81eb1bc0-ffffffff81eb210d: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f74670)
Location: net/sched/sch_api.c:1252
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81f74670-ffffffff81f74bbc: qdisc_create (STB_LOCAL)
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
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3ec28)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffff800010c3ec28-ffff800010c3f0cc: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d50668)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
c0d50668-c0d50b54: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d38fc0)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
c000000000d38fc0-c000000000d395e4: qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007aeacc)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffe0007aeacc-ffffffe0007aee8a: qdisc_create (STB_LOCAL)
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
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81932620-ffffffff81932aa3: qdisc_create (STB_LOCAL)
ffffffff819332bd-ffffffff819332dc: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff818ec120-ffffffff818ec5a3: qdisc_create (STB_LOCAL)
ffffffff818ecdbd-ffffffff818ecddc: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff819837b0-ffffffff81983c33: qdisc_create (STB_LOCAL)
ffffffff8198444d-ffffffff8198446c: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct Qdisc *qdisc_create(struct net_device *dev, struct netdev_queue *dev_queue, struct Qdisc *p, u32 parent, u32 handle, struct nlattr **tca, int *errp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1148
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff819a5d00-ffffffff819a6180: qdisc_create (STB_LOCAL)
ffffffff819a698d-ffffffff819a69ac: qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
