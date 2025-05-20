# Function: <code>blk_complete_reqs</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_complete_reqs(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81572c40)
Location: block/blk-mq.c:571
Inline: False
Direct callers:
  - block/blk-mq.c:blk_softirq_cpu_dead
  - block/blk-mq.c:blk_done_softirq
```
**Symbols:**

```
ffffffff81572c40-ffffffff81572c87: blk_complete_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_complete_reqs(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d7150)
Location: block/blk-mq.c:578
Inline: False
Direct callers:
  - block/blk-mq.c:blk_softirq_cpu_dead
  - block/blk-mq.c:blk_done_softirq
```
**Symbols:**

```
ffffffff815d7150-ffffffff815d7197: blk_complete_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_complete_reqs(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81683200)
Location: block/blk-mq.c:1009
Inline: False
Direct callers:
  - block/blk-mq.c:blk_softirq_cpu_dead
  - block/blk-mq.c:blk_done_softirq
```
**Symbols:**

```
ffffffff81683200-ffffffff8168325b: blk_complete_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_complete_reqs(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81740a20)
Location: block/blk-mq.c:1126
Inline: False
Direct callers:
  - block/blk-mq.c:blk_softirq_cpu_dead
  - block/blk-mq.c:blk_done_softirq
```
**Symbols:**

```
ffffffff81740a20-ffffffff81740a7b: blk_complete_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_complete_reqs(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177cc50)
Location: block/blk-mq.c:1124
Inline: False
Direct callers:
  - block/blk-mq.c:blk_softirq_cpu_dead
  - block/blk-mq.c:blk_done_softirq
```
**Symbols:**

```
ffffffff8177cc50-ffffffff8177ccab: blk_complete_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_complete_reqs(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817bf050)
Location: block/blk-mq.c:1129
Inline: False
Direct callers:
  - block/blk-mq.c:blk_softirq_cpu_dead
  - block/blk-mq.c:blk_done_softirq
```
**Symbols:**

```
ffffffff817bf050-ffffffff817bf0ab: blk_complete_reqs (STB_LOCAL)
```
</details>
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
