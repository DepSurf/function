# Function: <code>tcf_block_get_ext</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81880160)
Location: net/sched/cls_api.c:283
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81880160-ffffffff81880287: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d4a40)
Location: net/sched/cls_api.c:576
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff818d4a40-ffffffff818d4e1a: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ff400)
Location: net/sched/cls_api.c:1044
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff818ff400-ffffffff818ff783: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195fc00)
Location: net/sched/cls_api.c:1422
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff8195fc00-ffffffff8195fff0: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81996c60)
Location: net/sched/cls_api.c:1336
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81996c60-ffffffff819970e0: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6f1c0)
Location: net/sched/cls_api.c:1299
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81a6f1c0-ffffffff81a6f45b: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a77ba0)
Location: net/sched/cls_api.c:1300
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81a77ba0-ffffffff81a77e44: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a63600)
Location: net/sched/cls_api.c:1300
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81a63600-ffffffff81a63a7e: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1301
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81d392a0-ffffffff81d392bb: tcf_block_get_ext.cold (STB_LOCAL)
ffffffff81b1c970-ffffffff81b1cdfc: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1318
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81f05a0d-ffffffff81f05a28: tcf_block_get_ext.cold (STB_LOCAL)
ffffffff81ca0b90-ffffffff81ca1046: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff820ad817-ffffffff820ad832: tcf_block_get_ext.cold (STB_LOCAL)
ffffffff81e5cbd0-ffffffff81e5d086: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1425
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff8212ea0f-ffffffff8212ea2a: tcf_block_get_ext.cold (STB_LOCAL)
ffffffff81eb9780-ffffffff81eb9c31: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_qevent_init
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff822107b3-ffffffff822107c8: tcf_block_get_ext.cold (STB_LOCAL)
ffffffff81f7c8e0-ffffffff81f7ceb0: tcf_block_get_ext (STB_GLOBAL)
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
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c43d50)
Location: net/sched/cls_api.c:1336
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffff800010c43d50-ffff800010c441e0: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d54904)
Location: net/sched/cls_api.c:1336
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
c0d54904-c0d54d70: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3f0c0)
Location: net/sched/cls_api.c:1336
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
c000000000d3f0c0-c000000000d3f6a0: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b221c)
Location: net/sched/cls_api.c:1336
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffe0007b221c-ffffffe0007b262c: tcf_block_get_ext (STB_GLOBAL)
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
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81936ad0)
Location: net/sched/cls_api.c:1336
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81936ad0-ffffffff81936f50: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f05d0)
Location: net/sched/cls_api.c:1336
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff818f05d0-ffffffff818f0a50: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81987c60)
Location: net/sched/cls_api.c:1336
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81987c60-ffffffff819880e0: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_block_get_ext(struct tcf_block **p_block, struct Qdisc *q, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9ec0)
Location: net/sched/cls_api.c:1336
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff819a9ec0-ffffffff819aa350: tcf_block_get_ext (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
