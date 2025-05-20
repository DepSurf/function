# Function: <code>__blk_end_request_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __blk_end_request_all(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bb140)
Location: block/blk-core.c:2915
Inline: True
Direct callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff813bb140-ffffffff813bb176: __blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __blk_end_request_all(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fef10)
Location: block/blk-core.c:2887
Inline: True
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_peek_request
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff813fef10-ffffffff813fef46: __blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __blk_end_request_all(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418940)
Location: block/blk-core.c:2884
Inline: True
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_peek_request
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff81418940-ffffffff81418976: __blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __blk_end_request_all(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425ed0)
Location: block/blk-core.c:2999
Inline: True
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_peek_request
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff81425ed0-ffffffff81425f2c: __blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __blk_end_request_all(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81451040)
Location: block/blk-core.c:3223
Inline: True
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_peek_request
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff81451040-ffffffff8145109c: __blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __blk_end_request_all(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814842c0)
Location: block/blk-core.c:3368
Inline: True
Direct callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_peek_request
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-exec.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff814842c0-ffffffff81484301: __blk_end_request_all (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
