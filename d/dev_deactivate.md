# Function: <code>dev_deactivate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81741e10)
Location: net/sched/sch_generic.c:896
Inline: False
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81741e10-ffffffff81741e7a: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817aecc0)
Location: net/sched/sch_generic.c:923
Inline: False
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff817aecc0-ffffffff817aed2a: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817de340)
Location: net/sched/sch_generic.c:931
Inline: False
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff817de340-ffffffff817de3aa: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fd990)
Location: net/sched/sch_generic.c:931
Inline: False
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff817fd990-ffffffff817fd9fa: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187b5c0)
Location: net/sched/sch_generic.c:965
Inline: False
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8187b5c0-ffffffff8187b62a: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cdb90)
Location: net/sched/sch_generic.c:1197
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff818cda80-ffffffff818cdaea: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f8dd0)
Location: net/sched/sch_generic.c:1236
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff818f8cc0-ffffffff818f8d2a: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819585a0)
Location: net/sched/sch_generic.c:1231
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81958490-ffffffff819584fa: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198ea50)
Location: net/sched/sch_generic.c:1228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8198e940-ffffffff8198e9aa: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6683b)
Location: net/sched/sch_generic.c:1252
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a66710-ffffffff81a66774: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6e91b)
Location: net/sched/sch_generic.c:1239
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a6e7f0-ffffffff81a6e854: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a571ab)
Location: net/sched/sch_generic.c:1285
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a57080-ffffffff81a570e1: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b1000b)
Location: net/sched/sch_generic.c:1315
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81b0feb0-ffffffff81b0ff11: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c971c5)
Location: net/sched/sch_generic.c:1357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81c97050-ffffffff81c970bb: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e52fd5)
Location: net/sched/sch_generic.c:1369
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81e52e40-ffffffff81e52eab: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eae854)
Location: net/sched/sch_generic.c:1377
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81eae6c0-ffffffff81eae72b: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f712e1)
Location: net/sched/sch_generic.c:1381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81f71140-ffffffff81f711b4: dev_deactivate (STB_GLOBAL)
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
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c3a47c)
Location: net/sched/sch_generic.c:1228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffff800010c3a350-ffff800010c3a3bc: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4c634)
Location: net/sched/sch_generic.c:1228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
c0d4c4fc-c0d4c57c: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d33530)
Location: net/sched/sch_generic.c:1228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
c000000000d333a0-c000000000d33428: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007ab560)
Location: net/sched/sch_generic.c:1228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffe0007ab496-ffffffe0007ab4e0: dev_deactivate (STB_GLOBAL)
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
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192e8c0)
Location: net/sched/sch_generic.c:1228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8192e7b0-ffffffff8192e81a: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e83c0)
Location: net/sched/sch_generic.c:1228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff818e82b0-ffffffff818e831a: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197fa50)
Location: net/sched/sch_generic.c:1228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8197f940-ffffffff8197f9aa: dev_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dev_deactivate(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a1fb0)
Location: net/sched/sch_generic.c:1228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_qdisc_change_tx_queue_len
Direct callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff819a1ea0-ffffffff819a1f0a: dev_deactivate (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
