# Function: <code>blk_mq_put_dispatch_budget</code>

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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145d4ee)
Location: block/blk-mq.h:142
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8146106a)
Location: block/blk-mq.h:142
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814903d9)
Location: block/blk-mq.h:157
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff81494936)
Location: block/blk-mq.h:157
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aa73a)
Location: block/blk-mq.h:198
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814aea6b)
Location: block/blk-mq.h:198
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8241)
Location: block/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814dcd0d)
Location: block/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f15f3)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814f617d)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154fed6)
Location: block/blk-mq.h:182
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff81556a76)
Location: block/blk-mq.h:182
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c3f3)
Location: block/blk-mq.h:190
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff815734f3)
Location: block/blk-mq.h:190
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573b2a)
Location: block/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8157b641)
Location: block/blk-mq.h:191
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da54a)
Location: block/blk-mq.h:193
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff815e09cd)
Location: block/blk-mq.h:193
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81687e72)
Location: block/blk-mq.h:193
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8168f5e3)
Location: block/blk-mq.h:193
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81746242)
Location: block/blk-mq.h:194
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8174e103)
Location: block/blk-mq.h:194
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81782a2b)
Location: block/blk-mq.h:244
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_budget_and_tag
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8178a5f3)
Location: block/blk-mq.h:244
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c4d9f)
Location: block/blk-mq.h:244
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_budget_and_tag
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff817ccd53)
Location: block/blk-mq.h:244
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f0c9c)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffff8000105f64f8)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079ccc4)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (c07a1ecc)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000787800)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (c00000000078e890)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f9ae)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffe00043400c)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9bd3)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814ee75d)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814da133)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814decad)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5c63)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814ea7ed)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814febf3)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff815037dd)
Location: block/blk-mq.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
</ul>

## Differences
