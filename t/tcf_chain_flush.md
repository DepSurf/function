# Function: <code>tcf_chain_flush</code>

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
void tcf_chain_flush(struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818018c0)
Location: net/sched/cls_api.c:204
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff818018c0-ffffffff818018f5: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187f720)
Location: net/sched/cls_api.c:205
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tcf_block_put_ext
```
**Symbols:**

```
ffffffff8187f720-ffffffff8187f775: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2570)
Location: net/sched/cls_api.c:221
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff818d2570-ffffffff818d25e8: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fef70)
Location: net/sched/cls_api.c:356
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff818fef70-ffffffff818fefed: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195eb10)
Location: net/sched/cls_api.c:529
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff8195eb10-ffffffff8195eb76: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81995440)
Location: net/sched/cls_api.c:581
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff81995440-ffffffff819954f9: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6e4b0)
Location: net/sched/cls_api.c:596
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81a6e4b0-ffffffff81a6e569: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a76cc0)
Location: net/sched/cls_api.c:596
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81a76cc0-ffffffff81a76d79: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5ea50)
Location: net/sched/cls_api.c:596
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81a5ea50-ffffffff81a5eb09: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b17c20)
Location: net/sched/cls_api.c:596
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81b17c20-ffffffff81b17cd9: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9fac0)
Location: net/sched/cls_api.c:613
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81c9fac0-ffffffff81c9fb8d: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5bd90)
Location: net/sched/cls_api.c:615
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81e5bd90-ffffffff81e5be5d: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb8590)
Location: net/sched/cls_api.c:720
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81eb8590-ffffffff81eb865d: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7b660)
Location: net/sched/cls_api.c:720
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81f7b660-ffffffff81f7b72d: tcf_chain_flush (STB_LOCAL)
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
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c42070)
Location: net/sched/cls_api.c:581
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffff800010c42070-ffff800010c4213c: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d53e28)
Location: net/sched/cls_api.c:581
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
c0d53e28-c0d53edc: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3e010)
Location: net/sched/cls_api.c:581
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
c000000000d3e010-c000000000d3e130: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b183c)
Location: net/sched/cls_api.c:581
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffe0007b183c-ffffffe0007b190a: tcf_chain_flush (STB_LOCAL)
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
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819352b0)
Location: net/sched/cls_api.c:581
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff819352b0-ffffffff81935369: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818eedb0)
Location: net/sched/cls_api.c:581
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff818eedb0-ffffffff818eee69: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81986440)
Location: net/sched/cls_api.c:581
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff81986440-ffffffff819864f9: tcf_chain_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain *chain, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9440)
Location: net/sched/cls_api.c:581
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff819a9440-ffffffff819a94f9: tcf_chain_flush (STB_LOCAL)
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
