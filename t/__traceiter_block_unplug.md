# Function: <code>__traceiter_block_unplug</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_block_unplug(void *__data, struct request_queue *q, unsigned int depth, bool explicit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155da40)
Location: include/trace/events/block.h:401
Inline: False
```
**Symbols:**

```
ffffffff8155da40-ffffffff8155da92: __traceiter_block_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_block_unplug(void *__data, struct request_queue *q, unsigned int depth, bool explicit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815662d0)
Location: include/trace/events/block.h:401
Inline: False
```
**Symbols:**

```
ffffffff815662d0-ffffffff81566320: __traceiter_block_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_block_unplug(void *__data, struct request_queue *q, unsigned int depth, bool explicit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ca6a0)
Location: include/trace/events/block.h:401
Inline: False
```
**Symbols:**

```
ffffffff815ca6a0-ffffffff815ca6f0: __traceiter_block_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_block_unplug(void *__data, struct request_queue *q, unsigned int depth, bool explicit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81675bf0)
Location: include/trace/events/block.h:424
Inline: False
```
**Symbols:**

```
ffffffff81675bf0-ffffffff81675c4c: __traceiter_block_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_block_unplug(void *__data, struct request_queue *q, unsigned int depth, bool explicit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81731b70)
Location: include/trace/events/block.h:424
Inline: False
```
**Symbols:**

```
ffffffff81731b70-ffffffff81731bcc: __traceiter_block_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_block_unplug(void *__data, struct request_queue *q, unsigned int depth, bool explicit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176de90)
Location: include/trace/events/block.h:450
Inline: False
```
**Symbols:**

```
ffffffff8176de90-ffffffff8176deec: __traceiter_block_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_block_unplug(void *__data, struct request_queue *q, unsigned int depth, bool explicit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b00c0)
Location: include/trace/events/block.h:452
Inline: False
```
**Symbols:**

```
ffffffff817b00c0-ffffffff817b011c: __traceiter_block_unplug (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
