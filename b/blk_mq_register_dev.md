# Function: <code>blk_mq_register_dev</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_mq_register_dev(struct device *dev, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff81427890)
Location: block/blk-mq-sysfs.c:492
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81427890-ffffffff814279af: blk_mq_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_mq_register_dev(struct device *dev, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff81434ee0)
Location: block/blk-mq-sysfs.c:340
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81434ee0-ffffffff81434f23: blk_mq_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_register_dev(struct device *dev, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff81460af0)
Location: block/blk-mq-sysfs.c:340
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81460af0-ffffffff81460b33: blk_mq_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_register_dev(struct device *dev, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814943c0)
Location: block/blk-mq-sysfs.c:333
Inline: False
```
**Symbols:**

```
ffffffff814943c0-ffffffff81494403: blk_mq_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_register_dev(struct device *dev, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814ae510)
Location: block/blk-mq-sysfs.c:347
Inline: False
```
**Symbols:**

```
ffffffff814ae510-ffffffff814ae553: blk_mq_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_mq_register_dev(struct device *dev, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814dc7b0)
Location: block/blk-mq-sysfs.c:352
Inline: False
```
**Symbols:**

```
ffffffff814dc7b0-ffffffff814dc7f5: blk_mq_register_dev (STB_GLOBAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
</ul>
