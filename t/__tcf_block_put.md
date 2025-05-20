# Function: <code>__tcf_block_put</code>

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
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ff290)
Location: net/sched/cls_api.c:827
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff818ff290-ffffffff818ff3fe: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195faa0)
Location: net/sched/cls_api.c:1278
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff8195faa0-ffffffff8195fbf4: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81996b00)
Location: net/sched/cls_api.c:1192
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff81996b00-ffffffff81996c54: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6f060)
Location: net/sched/cls_api.c:1155
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a6f060-ffffffff81a6f1b5: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a77a40)
Location: net/sched/cls_api.c:1156
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a77a40-ffffffff81a77b94: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a60bd0)
Location: net/sched/cls_api.c:1156
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a60bd0-ffffffff81a60d24: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b19e40)
Location: net/sched/cls_api.c:1157
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81b19e40-ffffffff81b19f94: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca0a10)
Location: net/sched/cls_api.c:1174
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81ca0a10-ffffffff81ca0b87: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5ca40)
Location: net/sched/cls_api.c:1176
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81e5ca40-ffffffff81e5cbb7: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb95f0)
Location: net/sched/cls_api.c:1281
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81eb95f0-ffffffff81eb9765: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7c740)
Location: net/sched/cls_api.c:1283
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81f7c740-ffffffff81f7c8c5: __tcf_block_put (STB_LOCAL)
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
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c43bb0)
Location: net/sched/cls_api.c:1192
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffff800010c43bb0-ffff800010c43d4c: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d547b4)
Location: net/sched/cls_api.c:1192
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
c0d547b4-c0d54904: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3ee90)
Location: net/sched/cls_api.c:1192
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
c000000000d3ee90-c000000000d3f0c0: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b20b2)
Location: net/sched/cls_api.c:1192
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffe0007b20b2-ffffffe0007b221c: __tcf_block_put (STB_LOCAL)
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
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81936970)
Location: net/sched/cls_api.c:1192
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff81936970-ffffffff81936ac4: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f0470)
Location: net/sched/cls_api.c:1192
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff818f0470-ffffffff818f05c4: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81987b00)
Location: net/sched/cls_api.c:1192
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff81987b00-ffffffff81987c54: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __tcf_block_put(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9d50)
Location: net/sched/cls_api.c:1192
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_release
```
**Symbols:**

```
ffffffff819a9d50-ffffffff819a9eb8: __tcf_block_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
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
