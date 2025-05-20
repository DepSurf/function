# Function: <code>__traceiter_block_rq_complete</code>

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
int __traceiter_block_rq_complete(void *__data, struct request *rq, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155d750)
Location: include/trace/events/block.h:115
Inline: False
```
**Symbols:**

```
ffffffff8155d750-ffffffff8155d7a1: __traceiter_block_rq_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_block_rq_complete(void *__data, struct request *rq, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81565ff0)
Location: include/trace/events/block.h:115
Inline: False
```
**Symbols:**

```
ffffffff81565ff0-ffffffff8156603f: __traceiter_block_rq_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_block_rq_complete(void *__data, struct request *rq, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ca3c0)
Location: include/trace/events/block.h:115
Inline: False
```
**Symbols:**

```
ffffffff815ca3c0-ffffffff815ca40f: __traceiter_block_rq_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_block_rq_complete(void *__data, struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81675810)
Location: include/trace/events/block.h:147
Inline: False
```
**Symbols:**

```
ffffffff81675810-ffffffff8167586c: __traceiter_block_rq_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_block_rq_complete(void *__data, struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817316d0)
Location: include/trace/events/block.h:147
Inline: False
```
**Symbols:**

```
ffffffff817316d0-ffffffff8173172c: __traceiter_block_rq_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_block_rq_complete(void *__data, struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176d8f0)
Location: include/trace/events/block.h:147
Inline: False
```
**Symbols:**

```
ffffffff8176d8f0-ffffffff8176d94c: __traceiter_block_rq_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_block_rq_complete(void *__data, struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817afb20)
Location: include/trace/events/block.h:149
Inline: False
```
**Symbols:**

```
ffffffff817afb20-ffffffff817afb7c: __traceiter_block_rq_complete (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
</li>
</ul>
</details>
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
