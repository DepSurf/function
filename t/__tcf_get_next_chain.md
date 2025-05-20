# Function: <code>__tcf_get_next_chain</code>

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
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195d320)
Location: net/sched/cls_api.c:1030
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff8195d320-ffffffff8195d3a1: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81993820)
Location: net/sched/cls_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81993820-ffffffff819938a1: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6b8c0)
Location: net/sched/cls_api.c:907
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81a6b8c0-ffffffff81a6b941: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a74030)
Location: net/sched/cls_api.c:909
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81a74030-ffffffff81a740b1: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5cb80)
Location: net/sched/cls_api.c:909
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81a5cb80-ffffffff81a5cc01: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b15d30)
Location: net/sched/cls_api.c:910
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81b15d30-ffffffff81b15db1: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9d310)
Location: net/sched/cls_api.c:927
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81c9d310-ffffffff81c9d39b: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e59800)
Location: net/sched/cls_api.c:929
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81e59800-ffffffff81e5988b: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb5230)
Location: net/sched/cls_api.c:1034
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81eb5230-ffffffff81eb52cd: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f77ef0)
Location: net/sched/cls_api.c:1036
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81f77ef0-ffffffff81f77f78: __tcf_get_next_chain (STB_LOCAL)
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
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c3fbf0)
Location: net/sched/cls_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffff800010c3fbf0-ffff800010c3fcac: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d518ac)
Location: net/sched/cls_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
c0d518ac-c0d5194c: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3a620)
Location: net/sched/cls_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
c000000000d3a620-c000000000d3a724: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007af7b2)
Location: net/sched/cls_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffe0007af7b2-ffffffe0007af82c: __tcf_get_next_chain (STB_LOCAL)
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
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81933690)
Location: net/sched/cls_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81933690-ffffffff81933711: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ed190)
Location: net/sched/cls_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff818ed190-ffffffff818ed211: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81984820)
Location: net/sched/cls_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81984820-ffffffff819848a1: __tcf_get_next_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcf_chain *__tcf_get_next_chain(struct tcf_block *block, struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a6ea0)
Location: net/sched/cls_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff819a6ea0-ffffffff819a6f21: __tcf_get_next_chain (STB_LOCAL)
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
