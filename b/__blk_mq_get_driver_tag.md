# Function: <code>__blk_mq_get_driver_tag</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81554cb0)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
**Symbols:**

```
ffffffff81554cb0-ffffffff81554db2: __blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156b580)
Location: block/blk-mq.c:1105
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_get_driver_tag
```
**Symbols:**

```
ffffffff8156b580-ffffffff8156b696: __blk_mq_get_driver_tag (STB_LOCAL)
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
In block/blk-mq.c (ffffffff8157325b)
Location: block/blk-mq.c:1063
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_driver_tag
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
In block/blk-mq.c (ffffffff815da1bb)
Location: block/blk-mq.c:1069
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_driver_tag
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __blk_mq_get_driver_tag(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81687c20)
Location: block/blk-mq.c:1624
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81687c20-ffffffff81687dab: __blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __blk_mq_get_driver_tag(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745fd0)
Location: block/blk-mq.c:1785
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81745fd0-ffffffff81746162: __blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __blk_mq_get_driver_tag(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81782810)
Location: block/blk-mq.c:1778
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_get_budget_and_tag
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81782810-ffffffff817829a5: __blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
