# Function: <code>tc_setup_cb_call</code>

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
int tc_setup_cb_call(struct tcf_block *block, struct tcf_exts *exts, enum tc_setup_type type, void *type_data, bool err_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187fe70)
Location: net/sched/cls_api.c:1233
Inline: False
```
**Symbols:**

```
ffffffff8187fe70-ffffffff8187ff8a: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, struct tcf_exts *exts, enum tc_setup_type type, void *type_data, bool err_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d29d0)
Location: net/sched/cls_api.c:1729
Inline: False
```
**Symbols:**

```
ffffffff818d29d0-ffffffff818d2ae8: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fd6f0)
Location: net/sched/cls_api.c:2494
Inline: False
```
**Symbols:**

```
ffffffff818fd6f0-ffffffff818fd781: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195d070)
Location: net/sched/cls_api.c:3154
Inline: False
```
**Symbols:**

```
ffffffff8195d070-ffffffff8195d10a: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81993ec0)
Location: net/sched/cls_api.c:3193
Inline: False
```
**Symbols:**

```
ffffffff81993ec0-ffffffff81993feb: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6cbb0)
Location: net/sched/cls_api.c:3255
Inline: False
```
**Symbols:**

```
ffffffff81a6cbb0-ffffffff81a6ccdb: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a75610)
Location: net/sched/cls_api.c:3254
Inline: False
```
**Symbols:**

```
ffffffff81a75610-ffffffff81a7573b: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5de40)
Location: net/sched/cls_api.c:3255
Inline: False
```
**Symbols:**

```
ffffffff81a5de40-ffffffff81a5df6b: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b17000)
Location: net/sched/cls_api.c:3256
Inline: False
```
**Symbols:**

```
ffffffff81b17000-ffffffff81b1712b: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9ea80)
Location: net/sched/cls_api.c:3285
Inline: False
```
**Symbols:**

```
ffffffff81c9ea80-ffffffff81c9ebac: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5b240)
Location: net/sched/cls_api.c:3285
Inline: False
```
**Symbols:**

```
ffffffff81e5b240-ffffffff81e5b36c: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb7000)
Location: net/sched/cls_api.c:3492
Inline: False
```
**Symbols:**

```
ffffffff81eb7000-ffffffff81eb712c: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f79da0)
Location: net/sched/cls_api.c:3548
Inline: False
```
**Symbols:**

```
ffffffff81f79da0-ffffffff81f79ed5: tc_setup_cb_call (STB_GLOBAL)
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
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c403f8)
Location: net/sched/cls_api.c:3193
Inline: False
```
**Symbols:**

```
ffff800010c403f8-ffff800010c40544: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d52330)
Location: net/sched/cls_api.c:3193
Inline: False
```
**Symbols:**

```
c0d52330-c0d5247c: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3b0f0)
Location: net/sched/cls_api.c:3193
Inline: False
```
**Symbols:**

```
c000000000d3b0f0-c000000000d3b320: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007afe40)
Location: net/sched/cls_api.c:3193
Inline: False
```
**Symbols:**

```
ffffffe0007afe40-ffffffe0007aff78: tc_setup_cb_call (STB_GLOBAL)
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
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81933d30)
Location: net/sched/cls_api.c:3193
Inline: False
```
**Symbols:**

```
ffffffff81933d30-ffffffff81933e5b: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ed830)
Location: net/sched/cls_api.c:3193
Inline: False
```
**Symbols:**

```
ffffffff818ed830-ffffffff818ed95b: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81984ec0)
Location: net/sched/cls_api.c:3193
Inline: False
```
**Symbols:**

```
ffffffff81984ec0-ffffffff81984feb: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_setup_cb_call(struct tcf_block *block, enum tc_setup_type type, void *type_data, bool err_stop, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a76b0)
Location: net/sched/cls_api.c:3193
Inline: False
```
**Symbols:**

```
ffffffff819a76b0-ffffffff819a77db: tc_setup_cb_call (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct tcf_exts *exts</code>
</li>
<li>
<b>Param reordered. </b>
<code>block, exts, type, type_data, err_stop</code> ➡️ <code>block, type, type_data, err_stop</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
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
