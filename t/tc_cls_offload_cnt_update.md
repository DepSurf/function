# Function: <code>tc_cls_offload_cnt_update</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81995b20)
Location: net/sched/cls_api.c:3142
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81995b20-ffffffff81995bbe: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6ca80)
Location: net/sched/cls_api.c:3204
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81a6ca80-ffffffff81a6cb1e: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a75430)
Location: net/sched/cls_api.c:3203
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81a75430-ffffffff81a754ce: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5edc0)
Location: net/sched/cls_api.c:3204
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81a5edc0-ffffffff81a5ee5f: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b18070)
Location: net/sched/cls_api.c:3205
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81b18070-ffffffff81b1810f: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9cfb0)
Location: net/sched/cls_api.c:3234
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81c9cfb0-ffffffff81c9d05b: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e59460)
Location: net/sched/cls_api.c:3234
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81e59460-ffffffff81e5950b: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb4e90)
Location: net/sched/cls_api.c:3441
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81eb4e90-ffffffff81eb4f3b: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f77b50)
Location: net/sched/cls_api.c:3497
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81f77b50-ffffffff81f77bfb: tc_cls_offload_cnt_update (STB_LOCAL)
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
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c43508)
Location: net/sched/cls_api.c:3142
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffff800010c43508-ffff800010c43644: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d513a4)
Location: net/sched/cls_api.c:3142
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
c0d513a4-c0d51468: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3c720)
Location: net/sched/cls_api.c:3142
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
c000000000d3c720-c000000000d3c880: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b0aee)
Location: net/sched/cls_api.c:3142
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffe0007b0aee-ffffffe0007b0bca: tc_cls_offload_cnt_update (STB_LOCAL)
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
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81935990)
Location: net/sched/cls_api.c:3142
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81935990-ffffffff81935a2e: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ef490)
Location: net/sched/cls_api.c:3142
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff818ef490-ffffffff818ef52e: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81986b20)
Location: net/sched/cls_api.c:3142
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff81986b20-ffffffff81986bbe: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tc_cls_offload_cnt_update(struct tcf_block *block, struct tcf_proto *tp, u32 *cnt, u32 *flags, u32 diff, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a6a90)
Location: net/sched/cls_api.c:3142
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
```
**Symbols:**

```
ffffffff819a6a90-ffffffff819a6b28: tc_cls_offload_cnt_update (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
