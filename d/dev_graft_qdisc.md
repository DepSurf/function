# Function: <code>dev_graft_qdisc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81740cc0)
Location: net/sched/sch_generic.c:701
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81740cc0-ffffffff81740d30: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817adc80)
Location: net/sched/sch_generic.c:728
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff817adc80-ffffffff817adcf2: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817dd300)
Location: net/sched/sch_generic.c:732
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff817dd300-ffffffff817dd372: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fc950)
Location: net/sched/sch_generic.c:732
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff817fc950-ffffffff817fc9c0: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187a030)
Location: net/sched/sch_generic.c:756
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8187a030-ffffffff8187a085: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cb990)
Location: net/sched/sch_generic.c:982
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff818cb990-ffffffff818cb9e5: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f6c90)
Location: net/sched/sch_generic.c:1021
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff818f6c90-ffffffff818f6ce5: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81956160)
Location: net/sched/sch_generic.c:1016
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81956160-ffffffff819561b5: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198c600)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8198c600-ffffffff8198c655: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a641e0)
Location: net/sched/sch_generic.c:1008
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a641e0-ffffffff81a64235: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6c340)
Location: net/sched/sch_generic.c:995
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a6c340-ffffffff81a6c395: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a54ad0)
Location: net/sched/sch_generic.c:1039
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81a54ad0-ffffffff81a54b25: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0d7c0)
Location: net/sched/sch_generic.c:1065
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81b0d7c0-ffffffff81b0d815: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c94680)
Location: net/sched/sch_generic.c:1107
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81c94680-ffffffff81c946dd: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e50110)
Location: net/sched/sch_generic.c:1103
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81e50110-ffffffff81e5016d: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eab890)
Location: net/sched/sch_generic.c:1111
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81eab890-ffffffff81eab8ed: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f6e330)
Location: net/sched/sch_generic.c:1115
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81f6e330-ffffffff81f6e38d: dev_graft_qdisc (STB_GLOBAL)
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
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c38058)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffff800010c38058-ffff800010c3812c: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d49dd4)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
c0d49dd4-c0d49e2c: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d2fa90)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
c000000000d2fa90-c000000000d2fb58: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007a8df2)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffe0007a8df2-ffffffe0007a8e58: dev_graft_qdisc (STB_GLOBAL)
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
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192c470)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8192c470-ffffffff8192c4c5: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e5f70)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff818e5f70-ffffffff818e5fc5: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197d600)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8197d600-ffffffff8197d655: dev_graft_qdisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct Qdisc *dev_graft_qdisc(struct netdev_queue *dev_queue, struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8199fb70)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff8199fb70-ffffffff8199fbc5: dev_graft_qdisc (STB_GLOBAL)
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
