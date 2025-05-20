# Function: <code>blk_stat_alloc_callback</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814344c0)
Location: block/blk-stat.c:136
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814344c0-ffffffff81434591: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81460150)
Location: block/blk-stat.c:105
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff81460150-ffffffff8146021d: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814939b0)
Location: block/blk-stat.c:101
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814939b0-ffffffff81493a7d: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814adab0)
Location: block/blk-stat.c:101
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814adab0-ffffffff814adb7d: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814dbd40)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814dbd40-ffffffff814dbe0e: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814f5170)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814f5170-ffffffff814f523e: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81555b70)
Location: block/blk-stat.c:103
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff81555b70-ffffffff81555c3e: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff815723c0)
Location: block/blk-stat.c:103
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff815723c0-ffffffff8157248e: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8157a3e0)
Location: block/blk-stat.c:103
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff8157a3e0-ffffffff8157a4ae: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff815df770)
Location: block/blk-stat.c:103
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff815df770-ffffffff815df83e: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8168dea0)
Location: block/blk-stat.c:103
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff8168dea0-ffffffff8168df86: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8174c7a0)
Location: block/blk-stat.c:103
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff8174c7a0-ffffffff8174c886: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81788ee0)
Location: block/blk-stat.c:103
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff81788ee0-ffffffff81788fc6: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff817cb610)
Location: block/blk-stat.c:103
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff817cb610-ffffffff817cb725: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffff8000105f51d0)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffff8000105f51d0-ffff8000105f52b4: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (c07a0d1c)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
c07a0d1c-c07a0e18: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (c00000000078cd00)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
c00000000078cd00-c00000000078ce48: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffe000432f50)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffe000432f50-ffffffe000433020: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814ed750)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814ed750-ffffffff814ed81e: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814ddca0)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814ddca0-ffffffff814ddd6e: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814e97e0)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814e97e0-ffffffff814e98ae: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct blk_stat_callback *blk_stat_alloc_callback(void (*timer_fn)(struct blk_stat_callback *), int (*bucket_fn)(const struct request *), unsigned int buckets, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff815027b0)
Location: block/blk-stat.c:102
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff815027b0-ffffffff8150287e: blk_stat_alloc_callback (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
