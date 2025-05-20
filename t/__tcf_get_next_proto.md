# Function: <code>__tcf_get_next_proto</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195e370)
Location: net/sched/cls_api.c:1074
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff8195e370-ffffffff8195e44b: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81996050)
Location: net/sched/cls_api.c:988
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81996050-ffffffff8199612b: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6d440)
Location: net/sched/cls_api.c:951
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81a6d440-ffffffff81a6d555: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a75df0)
Location: net/sched/cls_api.c:953
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81a75df0-ffffffff81a75f05: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5f590)
Location: net/sched/cls_api.c:953
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81a5f590-ffffffff81a5f6a5: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:954
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81b18780-ffffffff81b188b1: __tcf_get_next_proto (STB_LOCAL)
ffffffff81d39184-ffffffff81d391c2: __tcf_get_next_proto.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:971
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81c9ebb0-ffffffff81c9ece4: __tcf_get_next_proto (STB_LOCAL)
ffffffff81f058f6-ffffffff81f05935: __tcf_get_next_proto.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:973
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81e5b380-ffffffff81e5b4b4: __tcf_get_next_proto (STB_LOCAL)
ffffffff820ad749-ffffffff820ad788: __tcf_get_next_proto.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1078
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81eb7140-ffffffff81eb7274: __tcf_get_next_proto (STB_LOCAL)
ffffffff8212e8fb-ffffffff8212e93a: __tcf_get_next_proto.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1080
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81f79ef0-ffffffff81f7a024: __tcf_get_next_proto (STB_LOCAL)
ffffffff82210699-ffffffff822106d8: __tcf_get_next_proto.cold (STB_LOCAL)
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
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c42850)
Location: net/sched/cls_api.c:988
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffff800010c42850-ffff800010c4299c: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d51a48)
Location: net/sched/cls_api.c:988
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
c0d51a48-c0d51b5c: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3cf50)
Location: net/sched/cls_api.c:988
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
c000000000d3cf50-c000000000d3d110: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b0f86)
Location: net/sched/cls_api.c:988
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffe0007b0f86-ffffffe0007b1086: __tcf_get_next_proto (STB_LOCAL)
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
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81935ec0)
Location: net/sched/cls_api.c:988
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81935ec0-ffffffff81935f9b: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ef9c0)
Location: net/sched/cls_api.c:988
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff818ef9c0-ffffffff818efa9b: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81987050)
Location: net/sched/cls_api.c:988
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81987050-ffffffff8198712b: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcf_proto *__tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a6fc0)
Location: net/sched/cls_api.c:988
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff819a6fc0-ffffffff819a709b: __tcf_get_next_proto (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
