# Function: <code>qdisc_put</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f70a0)
Location: net/sched/sch_generic.c:994
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
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff818f70a0-ffffffff818f70c5: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819567c0)
Location: net/sched/sch_generic.c:986
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff819567c0-ffffffff819567e8: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198cc60)
Location: net/sched/sch_generic.c:981
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff8198cc60-ffffffff8198cc88: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a64d30)
Location: net/sched/sch_generic.c:978
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
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81a64d30-ffffffff81a64d74: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6ce60)
Location: net/sched/sch_generic.c:965
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
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81a6ce60-ffffffff81a6cea4: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a55670)
Location: net/sched/sch_generic.c:1009
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
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81a55670-ffffffff81a556b4: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0e1f0)
Location: net/sched/sch_generic.c:1035
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
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81b0e1f0-ffffffff81b0e234: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c95c10)
Location: net/sched/sch_generic.c:1077
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
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81c95c10-ffffffff81c95c84: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e517b0)
Location: net/sched/sch_generic.c:1073
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81e517b0-ffffffff81e51824: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81ead000)
Location: net/sched/sch_generic.c:1081
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81ead000-ffffffff81ead074: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f6faa0)
Location: net/sched/sch_generic.c:1085
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81f6faa0-ffffffff81f6fb14: qdisc_put (STB_GLOBAL)
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
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c38268)
Location: net/sched/sch_generic.c:981
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffff800010c38268-ffff800010c382bc: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4a480)
Location: net/sched/sch_generic.c:981
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
c0d4a480-c0d4a4c4: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d31130)
Location: net/sched/sch_generic.c:981
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
c000000000d31130-c000000000d31180: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007a95ea)
Location: net/sched/sch_generic.c:981
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffe0007a95ea-ffffffe0007a9638: qdisc_put (STB_GLOBAL)
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
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192cad0)
Location: net/sched/sch_generic.c:981
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff8192cad0-ffffffff8192caf8: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e65d0)
Location: net/sched/sch_generic.c:981
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff818e65d0-ffffffff818e65f8: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197dc60)
Location: net/sched/sch_generic.c:981
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff8197dc60-ffffffff8197dc88: qdisc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a01d0)
Location: net/sched/sch_generic.c:981
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
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_block_release
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff819a01d0-ffffffff819a01f8: qdisc_put (STB_GLOBAL)
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
