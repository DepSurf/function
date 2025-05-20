# Function: <code>tcf_chain_get_by_act</code>

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
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fedc0)
Location: net/sched/cls_api.c:315
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff818fedc0-ffffffff818fedda: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195e800)
Location: net/sched/cls_api.c:453
Inline: False
```
**Symbols:**

```
ffffffff8195e800-ffffffff8195e81a: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819950d0)
Location: net/sched/cls_api.c:505
Inline: False
```
**Symbols:**

```
ffffffff819950d0-ffffffff819950ea: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6de00)
Location: net/sched/cls_api.c:520
Inline: False
```
**Symbols:**

```
ffffffff81a6de00-ffffffff81a6de1a: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a767d0)
Location: net/sched/cls_api.c:520
Inline: False
```
**Symbols:**

```
ffffffff81a767d0-ffffffff81a767ea: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5e6d0)
Location: net/sched/cls_api.c:520
Inline: False
```
**Symbols:**

```
ffffffff81a5e6d0-ffffffff81a5e6ea: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b178a0)
Location: net/sched/cls_api.c:520
Inline: False
```
**Symbols:**

```
ffffffff81b178a0-ffffffff81b178ba: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9f6e0)
Location: net/sched/cls_api.c:537
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_check_ctrlact
```
**Symbols:**

```
ffffffff81c9f6e0-ffffffff81c9f706: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5b950)
Location: net/sched/cls_api.c:539
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_check_ctrlact
```
**Symbols:**

```
ffffffff81e5b950-ffffffff81e5b976: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb8070)
Location: net/sched/cls_api.c:642
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_check_ctrlact
```
**Symbols:**

```
ffffffff81eb8070-ffffffff81eb8096: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7b0d0)
Location: net/sched/cls_api.c:643
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_check_ctrlact
```
**Symbols:**

```
ffffffff81f7b0d0-ffffffff81f7b0f6: tcf_chain_get_by_act (STB_GLOBAL)
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
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c41ca0)
Location: net/sched/cls_api.c:505
Inline: False
```
**Symbols:**

```
ffff800010c41ca0-ffff800010c41cdc: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d53a84)
Location: net/sched/cls_api.c:505
Inline: False
```
**Symbols:**

```
c0d53a84-c0d53aa8: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3dae0)
Location: net/sched/cls_api.c:505
Inline: False
```
**Symbols:**

```
c000000000d3dae0-c000000000d3dafc: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b1570)
Location: net/sched/cls_api.c:505
Inline: False
```
**Symbols:**

```
ffffffe0007b1570-ffffffe0007b15a6: tcf_chain_get_by_act (STB_GLOBAL)
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
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81934f40)
Location: net/sched/cls_api.c:505
Inline: False
```
**Symbols:**

```
ffffffff81934f40-ffffffff81934f5a: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818eea40)
Location: net/sched/cls_api.c:505
Inline: False
```
**Symbols:**

```
ffffffff818eea40-ffffffff818eea5a: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819860d0)
Location: net/sched/cls_api.c:505
Inline: False
```
**Symbols:**

```
ffffffff819860d0-ffffffff819860ea: tcf_chain_get_by_act (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcf_chain *tcf_chain_get_by_act(struct tcf_block *block, u32 chain_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a90d0)
Location: net/sched/cls_api.c:505
Inline: False
```
**Symbols:**

```
ffffffff819a90d0-ffffffff819a90ea: tcf_chain_get_by_act (STB_GLOBAL)
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
