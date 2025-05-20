# Function: <code>tcf_proto_create</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81802a34)
Location: net/sched/cls_api.c:130
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
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
In net/sched/cls_api.c (ffffffff81880d24)
Location: net/sched/cls_api.c:123
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
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
In net/sched/cls_api.c (ffffffff818d451c)
Location: net/sched/cls_api.c:125
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffff81900fe5)
Location: net/sched/cls_api.c:155
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffff819621ac)
Location: net/sched/cls_api.c:180
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffff81999371)
Location: net/sched/cls_api.c:250
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_proto *tcf_proto_create(const char *kind, u32 protocol, u32 prio, struct tcf_chain *chain, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6c4f0)
Location: net/sched/cls_api.c:251
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a6c4f0-ffffffff81a6c5ce: tcf_proto_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_proto *tcf_proto_create(const char *kind, u32 protocol, u32 prio, struct tcf_chain *chain, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a74fc0)
Location: net/sched/cls_api.c:251
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a74fc0-ffffffff81a7509e: tcf_proto_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a625d4)
Location: net/sched/cls_api.c:251
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b1b8ca)
Location: net/sched/cls_api.c:251
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca2c63)
Location: net/sched/cls_api.c:268
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e60498)
Location: net/sched/cls_api.c:270
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ebb57c)
Location: net/sched/cls_api.c:372
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7e76f)
Location: net/sched/cls_api.c:372
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffff800010c460a4)
Location: net/sched/cls_api.c:250
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (c0d55f24)
Location: net/sched/cls_api.c:250
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (c000000000d40ab0)
Location: net/sched/cls_api.c:250
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffe0007b3522)
Location: net/sched/cls_api.c:250
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffff819391e1)
Location: net/sched/cls_api.c:250
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffff818f2ce1)
Location: net/sched/cls_api.c:250
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffff8198a371)
Location: net/sched/cls_api.c:250
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffff819ab6e0)
Location: net/sched/cls_api.c:250
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
</ul>
