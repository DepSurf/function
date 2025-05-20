# Function: <code>blk_end_request_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_end_request_all(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba8d0)
Location: block/blk-core.c:2838
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_softirq_done
  - block/bsg-lib.c:bsg_request_fn
  - drivers/block/xen-blkfront.c:blkif_recover
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:dm_softirq_done
```
**Symbols:**

```
ffffffff813ba8d0-ffffffff813ba906: blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_end_request_all(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe660)
Location: block/blk-core.c:2810
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
```
**Symbols:**

```
ffffffff813fe660-ffffffff813fe696: blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_end_request_all(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418040)
Location: block/blk-core.c:2807
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_destroy_job
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
```
**Symbols:**

```
ffffffff81418040-ffffffff81418076: blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_end_request_all(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425db0)
Location: block/blk-core.c:2955
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_job_put
```
**Symbols:**

```
ffffffff81425db0-ffffffff81425dee: blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_end_request_all(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450f20)
Location: block/blk-core.c:3179
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_teardown_job
```
**Symbols:**

```
ffffffff81450f20-ffffffff81450f5e: blk_end_request_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_end_request_all(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814841c0)
Location: block/blk-core.c:3324
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_teardown_job
```
**Symbols:**

```
ffffffff814841c0-ffffffff814841f0: blk_end_request_all (STB_GLOBAL)
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
