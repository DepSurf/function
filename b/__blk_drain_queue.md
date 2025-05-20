# Function: <code>__blk_drain_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __blk_drain_queue(struct request_queue *q, bool drain_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b7af0)
Location: block/blk-core.c:394
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff813b7af0-ffffffff813b7c4f: __blk_drain_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __blk_drain_queue(struct request_queue *q, bool drain_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fb730)
Location: block/blk-core.c:394
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff813fb730-ffffffff813fb8c6: __blk_drain_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __blk_drain_queue(struct request_queue *q, bool drain_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81415120)
Location: block/blk-core.c:395
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff81415120-ffffffff814152b7: __blk_drain_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __blk_drain_queue(struct request_queue *q, bool drain_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422850)
Location: block/blk-core.c:458
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff81422850-ffffffff81422a02: __blk_drain_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __blk_drain_queue(struct request_queue *q, bool drain_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144e850)
Location: block/blk-core.c:491
Inline: False
Direct callers:
  - block/blk-core.c:blk_drain_queue
```
**Symbols:**

```
ffffffff8144e850-ffffffff8144ea02: __blk_drain_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __blk_drain_queue(struct request_queue *q, bool drain_all);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81481800)
Location: block/blk-core.c:552
Inline: True
Direct callers:
  - block/blk-core.c:blk_drain_queue
```
**Symbols:**

```
ffffffff81481800-ffffffff814819b2: __blk_drain_queue (STB_LOCAL)
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
