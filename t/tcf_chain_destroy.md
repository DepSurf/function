# Function: <code>tcf_chain_destroy</code>

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
void tcf_chain_destroy(struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81801840)
Location: net/sched/cls_api.c:216
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tcf_block_put
```
**Symbols:**

```
ffffffff81801840-ffffffff8180187d: tcf_chain_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcf_chain_destroy(struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187f570)
Location: net/sched/cls_api.c:218
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_remove
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff8187f570-ffffffff8187f5c0: tcf_chain_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcf_chain_destroy(struct tcf_chain *chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d23b0)
Location: net/sched/cls_api.c:234
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff818d23b0-ffffffff818d2400: tcf_chain_destroy (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff818fee32)
Location: net/sched/cls_api.c:238
Inline: True
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
In net/sched/cls_api.c (ffffffff8195e908)
Location: net/sched/cls_api.c:363
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff819951de)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6deff)
Location: net/sched/cls_api.c:416
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a768cf)
Location: net/sched/cls_api.c:416
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff81a5e7cf)
Location: net/sched/cls_api.c:416
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff81b179c8)
Location: net/sched/cls_api.c:416
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff81c9f828)
Location: net/sched/cls_api.c:433
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff81e5baa8)
Location: net/sched/cls_api.c:435
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff81eb81fc)
Location: net/sched/cls_api.c:537
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff81f7b256)
Location: net/sched/cls_api.c:538
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffff800010c41da8)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (c0d53b8c)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (c000000000d3dc40)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffe0007b1656)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff8193504e)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff818eeb4e)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff819861de)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
In net/sched/cls_api.c (ffffffff819a91de)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
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
</ul>
