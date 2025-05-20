# Function: <code>tcf_chain_create</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81801eb0)
Location: net/sched/cls_api.c:189
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get
```
**Symbols:**

```
ffffffff81801eb0-ffffffff81801f08: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818800b0)
Location: net/sched/cls_api.c:182
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff818800b0-ffffffff81880108: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d3940)
Location: net/sched/cls_api.c:190
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff818d3940-ffffffff818d39a4: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fd950)
Location: net/sched/cls_api.c:202
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff818fd950-ffffffff818fd9b1: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195d3b0)
Location: net/sched/cls_api.c:296
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff8195d3b0-ffffffff8195d43b: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819938b0)
Location: net/sched/cls_api.c:347
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff819938b0-ffffffff8199393e: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6c460)
Location: net/sched/cls_api.c:348
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81a6c460-ffffffff81a6c4ee: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a74e00)
Location: net/sched/cls_api.c:348
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81a74e00-ffffffff81a74e8e: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5d950)
Location: net/sched/cls_api.c:348
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81a5d950-ffffffff81a5d9de: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b16ae0)
Location: net/sched/cls_api.c:348
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81b16ae0-ffffffff81b16b6e: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9e210)
Location: net/sched/cls_api.c:365
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81c9e210-ffffffff81c9e2a8: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5a940)
Location: net/sched/cls_api.c:367
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81e5a940-ffffffff81e5a9d8: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb6780)
Location: net/sched/cls_api.c:469
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81eb6780-ffffffff81eb6818: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f795a0)
Location: net/sched/cls_api.c:469
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81f795a0-ffffffff81f79663: tcf_chain_create (STB_LOCAL)
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
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c3fcb0)
Location: net/sched/cls_api.c:347
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffff800010c3fcb0-ffff800010c3fd44: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d519bc)
Location: net/sched/cls_api.c:347
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
c0d519bc-c0d51a48: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3d110)
Location: net/sched/cls_api.c:347
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
c000000000d3d110-c000000000d3d1d4: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007af8a2)
Location: net/sched/cls_api.c:347
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffe0007af8a2-ffffffe0007af92e: tcf_chain_create (STB_LOCAL)
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
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81933720)
Location: net/sched/cls_api.c:347
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81933720-ffffffff819337ae: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ed220)
Location: net/sched/cls_api.c:347
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff818ed220-ffffffff818ed2ae: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819848b0)
Location: net/sched/cls_api.c:347
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff819848b0-ffffffff8198493e: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_create(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a6f30)
Location: net/sched/cls_api.c:347
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff819a6f30-ffffffff819a6fbe: tcf_chain_create (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
