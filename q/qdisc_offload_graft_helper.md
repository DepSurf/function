# Function: <code>qdisc_offload_graft_helper</code>

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
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fa250)
Location: net/sched/sch_api.c:832
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff818fa250-ffffffff818fa2ea: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81959af0)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81959af0-ffffffff81959b8a: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8198ff90)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8198ff90-ffffffff8199002a: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a675b0)
Location: net/sched/sch_api.c:832
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a675b0-ffffffff81a6764a: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a6fcd0)
Location: net/sched/sch_api.c:834
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a6fcd0-ffffffff81a6fd6a: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a58820)
Location: net/sched/sch_api.c:834
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a58820-ffffffff81a588c3: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b11830)
Location: net/sched/sch_api.c:840
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81b11830-ffffffff81b118d3: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c989c0)
Location: net/sched/sch_api.c:841
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81c989c0-ffffffff81c98aa8: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e549f0)
Location: net/sched/sch_api.c:843
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81e549f0-ffffffff81e54ad8: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb02a0)
Location: net/sched/sch_api.c:851
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81eb02a0-ffffffff81eb0388: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f72d10)
Location: net/sched/sch_api.c:851
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81f72d10-ffffffff81f72df5: qdisc_offload_graft_helper (STB_GLOBAL)
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
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3bf00)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffff800010c3bf00-ffff800010c3bfdc: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4deac)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
c0d4deac-c0d4df74: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d35a50)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
c000000000d35a50-c000000000d35b54: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007acb1a)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffe0007acb1a-ffffffe0007acbc2: qdisc_offload_graft_helper (STB_GLOBAL)
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
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8192fe00)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8192fe00-ffffffff8192fe9a: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818e9900)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff818e9900-ffffffff818e999a: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81980f90)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81980f90-ffffffff8198102a: qdisc_offload_graft_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void qdisc_offload_graft_helper(struct net_device *dev, struct Qdisc *sch, struct Qdisc *new, struct Qdisc *old, enum tc_setup_type type, void *type_data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a3510)
Location: net/sched/sch_api.c:823
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff819a3510-ffffffff819a35aa: qdisc_offload_graft_helper (STB_GLOBAL)
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
