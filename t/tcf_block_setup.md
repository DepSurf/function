# Function: <code>tcf_block_setup</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195ee70)
Location: net/sched/cls_api.c:1611
Inline: True
```
**Symbols:**

```
ffffffff8195ee70-ffffffff8195f075: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819962d0)
Location: net/sched/cls_api.c:1537
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_cmd
```
**Symbols:**

```
ffffffff819962d0-ffffffff81996520: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6eeb0)
Location: net/sched/cls_api.c:1500
Inline: True
```
**Symbols:**

```
ffffffff81a6eeb0-ffffffff81a6eedd: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a77880)
Location: net/sched/cls_api.c:1501
Inline: True
```
**Symbols:**

```
ffffffff81a77880-ffffffff81a778ad: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5fd00)
Location: net/sched/cls_api.c:1501
Inline: True
```
**Symbols:**

```
ffffffff81a5fd00-ffffffff81a5fec8: tcf_block_setup (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81b191d8)
Location: net/sched/cls_api.c:1502
Inline: True
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
In net/sched/cls_api.c (ffffffff81ca08f3)
Location: net/sched/cls_api.c:1519
Inline: True
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
In net/sched/cls_api.c (ffffffff81e5c903)
Location: net/sched/cls_api.c:1521
Inline: True
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
In net/sched/cls_api.c (ffffffff81eb94bc)
Location: net/sched/cls_api.c:1627
Inline: True
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
In net/sched/cls_api.c (ffffffff81f7c60c)
Location: net/sched/cls_api.c:1657
Inline: True
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
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c42b78)
Location: net/sched/cls_api.c:1537
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_cmd
```
**Symbols:**

```
ffff800010c42b78-ffff800010c42e04: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d54164)
Location: net/sched/cls_api.c:1537
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_offload_cmd
  - net/sched/cls_api.c:tc_indr_block_call
  - net/sched/cls_api.c:tc_indr_block_cmd
```
**Symbols:**

```
c0d54164-c0d543dc: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3e580)
Location: net/sched/cls_api.c:1537
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_cmd
```
**Symbols:**

```
c000000000d3e580-c000000000d3e998: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b1bd0)
Location: net/sched/cls_api.c:1537
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_cmd
```
**Symbols:**

```
ffffffe0007b1bd0-ffffffe0007b1da6: tcf_block_setup (STB_LOCAL)
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
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81936140)
Location: net/sched/cls_api.c:1537
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_cmd
```
**Symbols:**

```
ffffffff81936140-ffffffff81936390: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818efc40)
Location: net/sched/cls_api.c:1537
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_cmd
```
**Symbols:**

```
ffffffff818efc40-ffffffff818efe90: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819872d0)
Location: net/sched/cls_api.c:1537
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_cmd
```
**Symbols:**

```
ffffffff819872d0-ffffffff81987520: tcf_block_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tcf_block_setup(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9790)
Location: net/sched/cls_api.c:1537
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_cmd
```
**Symbols:**

```
ffffffff819a9790-ffffffff819a99e0: tcf_block_setup (STB_LOCAL)
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
