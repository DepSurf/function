# Function: <code>blk_queue_bypass_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_bypass_end(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b89c0)
Location: block/blk-core.c:506
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff813b89c0-ffffffff813b8a33: blk_queue_bypass_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_bypass_end(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fc7b0)
Location: block/blk-core.c:506
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff813fc7b0-ffffffff813fc823: blk_queue_bypass_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_bypass_end(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416150)
Location: block/blk-core.c:507
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff81416150-ffffffff814161c3: blk_queue_bypass_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_bypass_end(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81423730)
Location: block/blk-core.c:576
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff81423730-ffffffff81423784: blk_queue_bypass_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_bypass_end(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ebe0)
Location: block/blk-core.c:616
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff8144ebe0-ffffffff8144ec34: blk_queue_bypass_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_bypass_end(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814816f0)
Location: block/blk-core.c:677
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff814816f0-ffffffff81481743: blk_queue_bypass_end (STB_GLOBAL)
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
