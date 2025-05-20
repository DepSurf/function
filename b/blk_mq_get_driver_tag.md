# Function: <code>blk_mq_get_driver_tag</code>

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
bool blk_mq_get_driver_tag(struct request *rq, struct blk_mq_hw_ctx **hctx, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430fe0)
Location: block/blk-mq.c:857
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff81430fe0-ffffffff814310ff: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq, struct blk_mq_hw_ctx **hctx, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145c950)
Location: block/blk-mq.c:969
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff8145c950-ffffffff8145ca6f: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq, struct blk_mq_hw_ctx **hctx, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814901c0)
Location: block/blk-mq.c:967
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814901c0-ffffffff81490301: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9a40)
Location: block/blk-mq.c:1041
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814a9a40-ffffffff814a9b44: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d79e0)
Location: block/blk-mq.c:1040
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814d79e0-ffffffff814d7adc: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0d60)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814f0d60-ffffffff814f0e5c: blk_mq_get_driver_tag (STB_GLOBAL)
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
In block/blk-mq.c (ffffffff8154fda7)
Location: block/blk-mq-tag.h:55
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156b6a0)
Location: block/blk-mq.c:1129
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
ffffffff8156b6a0-ffffffff8156b724: blk_mq_get_driver_tag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815731e0)
Location: block/blk-mq.c:1087
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
**Symbols:**

```
ffffffff815731e0-ffffffff81573366: blk_mq_get_driver_tag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da140)
Location: block/blk-mq.c:1093
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff815da140-ffffffff815da2c6: blk_mq_get_driver_tag (STB_GLOBAL)
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
In block/blk-mq.c (ffffffff81687e48)
Location: block/blk-mq.h:273
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-sched.c (ffffffff8168f1ad)
Location: block/blk-mq.h:273
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff81746218)
Location: block/blk-mq.h:274
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-sched.c (ffffffff8174dcad)
Location: block/blk-mq.h:274
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff81782a06)
Location: block/blk-mq.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_budget_and_tag
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-sched.c (ffffffff8178a22d)
Location: block/blk-mq.h:324
Inline: True
Inline callers:
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
In block/blk-mq.c (ffffffff817c4d76)
Location: block/blk-mq.h:352
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_budget_and_tag
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-sched.c (ffffffff817cc9a7)
Location: block/blk-mq.h:352
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
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
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f01e8)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffff8000105f01e8-ffff8000105f0338: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079c324)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
c079c324-c079c464: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000786a10)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
c000000000786a10-c000000000786bac: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f144)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffe00042f144-ffffffe00042f21a: blk_mq_get_driver_tag (STB_GLOBAL)
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
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9340)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814e9340-ffffffff814e943c: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d98b0)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814d98b0-ffffffff814d99ac: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e53d0)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814e53d0-ffffffff814e54cc: blk_mq_get_driver_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fe330)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814fe330-ffffffff814fe42c: blk_mq_get_driver_tag (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct blk_mq_hw_ctx **hctx</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wait</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
