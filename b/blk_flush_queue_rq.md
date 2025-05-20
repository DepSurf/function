# Function: <code>blk_flush_queue_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool blk_flush_queue_rq(struct request *rq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff813bd400)
Location: block/blk-flush.c:133
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff813bd400-ffffffff813bd466: blk_flush_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool blk_flush_queue_rq(struct request *rq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81401330)
Location: block/blk-flush.c:134
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff81401330-ffffffff81401393: blk_flush_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool blk_flush_queue_rq(struct request *rq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8141af80)
Location: block/blk-flush.c:134
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff8141af80-ffffffff8141afda: blk_flush_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_flush_queue_rq(struct request *rq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81428fb0)
Location: block/blk-flush.c:135
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff81428fb0-ffffffff8142900a: blk_flush_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_flush_queue_rq(struct request *rq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814540a0)
Location: block/blk-flush.c:135
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff814540a0-ffffffff814540fa: blk_flush_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_flush_queue_rq(struct request *rq, bool add_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814874e0)
Location: block/blk-flush.c:135
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff814874e0-ffffffff8148753f: blk_flush_queue_rq (STB_LOCAL)
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
In block/blk-flush.c (ffffffff814a18b1)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814cf8e9)
Location: block/blk-flush.c:134
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814e8c49)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff81547bf2)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_kick_flush
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff8156392e)
Location: block/blk-flush.c:134
Inline: True
Inline callers:
  - block/blk-flush.c:blk_kick_flush
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff8156c067)
Location: block/blk-flush.c:134
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff815d0598)
Location: block/blk-flush.c:134
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff8167bd88)
Location: block/blk-flush.c:141
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff81738608)
Location: block/blk-flush.c:141
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In block/blk-flush.c (ffff8000105e6be0)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (c0793a58)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (c00000000077b440)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffe000427cfc)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814e1229)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814d1bb9)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814dd2b9)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814f6119)
Location: block/blk-flush.c:135
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
