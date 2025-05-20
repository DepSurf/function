# Function: <code>qdisc_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81740ef0)
Location: net/sched/sch_generic.c:669
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_api.c:notify_and_destroy
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81740ef0-ffffffff81740f96: qdisc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817add00)
Location: net/sched/sch_generic.c:695
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:notify_and_destroy
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff817add00-ffffffff817addb3: qdisc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817dd380)
Location: net/sched/sch_generic.c:699
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:notify_and_destroy
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff817dd380-ffffffff817dd42c: qdisc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fc9c0)
Location: net/sched/sch_generic.c:699
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:notify_and_destroy
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff817fc9c0-ffffffff817fca69: qdisc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187afd0)
Location: net/sched/sch_generic.c:727
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:notify_and_destroy
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff8187afd0-ffffffff8187b07a: qdisc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cd3b0)
Location: net/sched/sch_generic.c:944
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:notify_and_destroy
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff818cd3b0-ffffffff818cd4eb: qdisc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f6f70)
Location: net/sched/sch_generic.c:962
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff818f6f70-ffffffff818f7098: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819566a0)
Location: net/sched/sch_generic.c:954
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff819566a0-ffffffff819567be: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198cb40)
Location: net/sched/sch_generic.c:949
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff8198cb40-ffffffff8198cc5e: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a64c70)
Location: net/sched/sch_generic.c:954
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff81a64c70-ffffffff81a64d2e: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6cdb0)
Location: net/sched/sch_generic.c:941
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff81a6cdb0-ffffffff81a6ce5c: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a555c0)
Location: net/sched/sch_generic.c:985
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff81a555c0-ffffffff81a5566c: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0e140)
Location: net/sched/sch_generic.c:1011
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff81b0e140-ffffffff81b0e1ee: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c95b40)
Location: net/sched/sch_generic.c:1053
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff81c95b40-ffffffff81c95c0d: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e516d0)
Location: net/sched/sch_generic.c:1049
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff81e516d0-ffffffff81e5179d: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eae400)
Location: net/sched/sch_generic.c:1073
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81eae400-ffffffff81eae423: qdisc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f70e70)
Location: net/sched/sch_generic.c:1077
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_graft
```
**Symbols:**

```
ffffffff81f70e70-ffffffff81f70e93: qdisc_destroy (STB_GLOBAL)
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
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c38130)
Location: net/sched/sch_generic.c:949
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffff800010c38130-ffff800010c38268: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4a34c)
Location: net/sched/sch_generic.c:949
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
c0d4a34c-c0d4a480: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d30f70)
Location: net/sched/sch_generic.c:949
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
c000000000d30f70-c000000000d31130: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007a94c8)
Location: net/sched/sch_generic.c:949
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffe0007a94c8-ffffffe0007a95ea: qdisc_destroy (STB_LOCAL)
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
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192c9b0)
Location: net/sched/sch_generic.c:949
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff8192c9b0-ffffffff8192cace: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e64b0)
Location: net/sched/sch_generic.c:949
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff818e64b0-ffffffff818e65ce: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197db40)
Location: net/sched/sch_generic.c:949
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff8197db40-ffffffff8197dc5e: qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a00b0)
Location: net/sched/sch_generic.c:949
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_generic.c:qdisc_put
```
**Symbols:**

```
ffffffff819a00b0-ffffffff819a01ce: qdisc_destroy (STB_LOCAL)
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
