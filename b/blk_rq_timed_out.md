# Function: <code>blk_rq_timed_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_timed_out(struct request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff813c20f0)
Location: block/blk-timeout.c:83
Inline: True
Direct callers:
  - block/blk-timeout.c:blk_rq_timed_out_timer
```
**Symbols:**

```
ffffffff813c20f0-ffffffff813c2147: blk_rq_timed_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_timed_out(struct request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff81406080)
Location: block/blk-timeout.c:83
Inline: True
Direct callers:
  - block/blk-timeout.c:blk_timeout_work
```
**Symbols:**

```
ffffffff81406080-ffffffff814060d7: blk_rq_timed_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_timed_out(struct request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff81420310)
Location: block/blk-timeout.c:83
Inline: True
Direct callers:
  - block/blk-timeout.c:blk_timeout_work
```
**Symbols:**

```
ffffffff81420310-ffffffff81420367: blk_rq_timed_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_timed_out(struct request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff8142e2d0)
Location: block/blk-timeout.c:83
Inline: True
Direct callers:
  - block/blk-timeout.c:blk_timeout_work
```
**Symbols:**

```
ffffffff8142e2d0-ffffffff8142e326: blk_rq_timed_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_timed_out(struct request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff81459500)
Location: block/blk-timeout.c:83
Inline: True
Direct callers:
  - block/blk-timeout.c:blk_timeout_work
```
**Symbols:**

```
ffffffff81459500-ffffffff81459559: blk_rq_timed_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_timed_out(struct request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-timeout.c (ffffffff8148ca60)
Location: block/blk-timeout.c:81
Inline: True
Direct callers:
  - block/blk-timeout.c:blk_timeout_work
```
**Symbols:**

```
ffffffff8148ca60-ffffffff8148caad: blk_rq_timed_out (STB_LOCAL)
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
