# Function: <code>elevator_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int elevator_init(struct request_queue *q, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b31c0)
Location: block/elevator.c:180
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
```
**Symbols:**

```
ffffffff813b31c0-ffffffff813b32be: elevator_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int elevator_init(struct request_queue *q, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f6eb0)
Location: block/elevator.c:180
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
```
**Symbols:**

```
ffffffff813f6eb0-ffffffff813f6fb6: elevator_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int elevator_init(struct request_queue *q, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814108c0)
Location: block/elevator.c:180
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
```
**Symbols:**

```
ffffffff814108c0-ffffffff814109c6: elevator_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int elevator_init(struct request_queue *q, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141e280)
Location: block/elevator.c:185
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq-sched.c:blk_mq_sched_init
```
**Symbols:**

```
ffffffff8141e280-ffffffff8141e3f2: elevator_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int elevator_init(struct request_queue *q, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814490f0)
Location: block/elevator.c:202
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq-sched.c:blk_mq_sched_init
```
**Symbols:**

```
ffffffff814490f0-ffffffff8144927a: elevator_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int elevator_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
```
**Symbols:**

```
ffffffff8147d731-ffffffff8147d76e: elevator_init.cold.30 (STB_LOCAL)
ffffffff8147c4f0-ffffffff8147c598: elevator_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>char *name</code>
</li>
</ul>
</details>
</li>
</ul>
