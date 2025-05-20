# Function: <code>blk_mq_get_dispatch_budget</code>

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
In block/blk-mq.c (ffffffff8145cb15)
Location: block/blk-mq.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff81460fbb)
Location: block/blk-mq.h:150
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
In block/blk-mq.c (ffffffff81490364)
Location: block/blk-mq.h:165
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8149487e)
Location: block/blk-mq.h:165
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
In block/blk-mq.c (ffffffff814aa70e)
Location: block/blk-mq.h:206
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814ae99e)
Location: block/blk-mq.h:206
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
In block/blk-mq.c (ffffffff814d81d6)
Location: block/blk-mq.h:199
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814dcc3e)
Location: block/blk-mq.h:199
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
In block/blk-mq.c (ffffffff814f1586)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814f60ae)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (ffffffff8154fd44)
Location: block/blk-mq.h:190
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff815569bb)
Location: block/blk-mq.h:190
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
In block/blk-mq.c (ffffffff8156c380)
Location: block/blk-mq.h:196
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8157343e)
Location: block/blk-mq.h:196
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
In block/blk-mq.c (ffffffff81573ace)
Location: block/blk-mq.h:198
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8157b53e)
Location: block/blk-mq.h:198
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
In block/blk-mq.c (ffffffff815da4ee)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff815e08be)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (ffffffff81687e0d)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8168f504)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (ffffffff817461dd)
Location: block/blk-mq.h:201
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8174e024)
Location: block/blk-mq.h:201
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
In block/blk-mq.c (ffffffff817829d2)
Location: block/blk-mq.h:251
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_budget_and_tag
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8178a514)
Location: block/blk-mq.h:251
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
In block/blk-mq.c (ffffffff817c4d42)
Location: block/blk-mq.h:251
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_budget_and_tag
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff817ccc74)
Location: block/blk-mq.h:251
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
In block/blk-mq.c (ffff8000105f0c24)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffff8000105f6430)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (c079cc48)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (c07a1e00)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (c000000000787754)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (c00000000078e780)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (ffffffe00042f96a)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffe000433f78)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (ffffffff814e9b66)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814ee68e)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (ffffffff814da0c6)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814debde)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (ffffffff814e5bf6)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff814ea71e)
Location: block/blk-mq.h:200
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
In block/blk-mq.c (ffffffff814feb86)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-sched.c (ffffffff8150370e)
Location: block/blk-mq.h:200
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
</details>
</li>
</ul>

## Differences
