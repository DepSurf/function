# Function: <code>queue_unplugged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void queue_unplugged(struct request_queue *q, unsigned int depth, bool from_schedule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b56f0)
Location: block/blk-core.c:3192
Inline: False
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
**Symbols:**

```
ffffffff813b56f0-ffffffff813b5795: queue_unplugged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void queue_unplugged(struct request_queue *q, unsigned int depth, bool from_schedule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa570)
Location: block/blk-core.c:3164
Inline: False
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
**Symbols:**

```
ffffffff813fa570-ffffffff813fa60e: queue_unplugged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void queue_unplugged(struct request_queue *q, unsigned int depth, bool from_schedule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413ef0)
Location: block/blk-core.c:3164
Inline: False
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
**Symbols:**

```
ffffffff81413ef0-ffffffff81413f8e: queue_unplugged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void queue_unplugged(struct request_queue *q, unsigned int depth, bool from_schedule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422490)
Location: block/blk-core.c:3267
Inline: False
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
**Symbols:**

```
ffffffff81422490-ffffffff8142252e: queue_unplugged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void queue_unplugged(struct request_queue *q, unsigned int depth, bool from_schedule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d570)
Location: block/blk-core.c:3491
Inline: False
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
**Symbols:**

```
ffffffff8144d570-ffffffff8144d611: queue_unplugged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void queue_unplugged(struct request_queue *q, unsigned int depth, bool from_schedule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81481750)
Location: block/blk-core.c:3628
Inline: False
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
**Symbols:**

```
ffffffff81481750-ffffffff814817fe: queue_unplugged (STB_LOCAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
