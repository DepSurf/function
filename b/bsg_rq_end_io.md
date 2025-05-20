# Function: <code>bsg_rq_end_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bsg_rq_end_io(struct request *rq, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff813d58a0)
Location: block/bsg.c:302
Inline: False
```
**Symbols:**

```
ffffffff813d58a0-ffffffff813d593e: bsg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bsg_rq_end_io(struct request *rq, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8141b5a0)
Location: block/bsg.c:302
Inline: False
```
**Symbols:**

```
ffffffff8141b5a0-ffffffff8141b63e: bsg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bsg_rq_end_io(struct request *rq, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81436ae0)
Location: block/bsg.c:302
Inline: False
```
**Symbols:**

```
ffffffff81436ae0-ffffffff81436b7e: bsg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bsg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81444320)
Location: block/bsg.c:296
Inline: False
```
**Symbols:**

```
ffffffff81444320-ffffffff814443be: bsg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bsg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81470bd0)
Location: block/bsg.c:296
Inline: False
```
**Symbols:**

```
ffffffff81470bd0-ffffffff81470c6e: bsg_rq_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bsg_rq_end_io(struct request *rq, blk_status_t status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814a4e70)
Location: block/bsg.c:292
Inline: False
```
**Symbols:**

```
ffffffff814a4e70-ffffffff814a4f3d: bsg_rq_end_io (STB_LOCAL)
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
<b>Param added. </b>
<code>blk_status_t status</code>
</li>
<li>
<b>Param removed. </b>
<code>int uptodate</code>
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
