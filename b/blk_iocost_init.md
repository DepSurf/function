# Function: <code>blk_iocost_init</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81511ee0)
Location: block/blk-iocost.c:1911
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81511ee0-ffffffff815120d4: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81572ea0)
Location: block/blk-iocost.c:1977
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81572ea0-ffffffff8157308d: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158f7b0)
Location: block/blk-iocost.c:2818
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8158f7b0-ffffffff8158fa0d: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81596740)
Location: block/blk-iocost.c:2825
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81596740-ffffffff815969f2: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815fdd40)
Location: block/blk-iocost.c:2832
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff815fdd40-ffffffff815fe018: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816ae440)
Location: block/blk-iocost.c:2835
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff816ae440-ffffffff816ae767: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (ffffffff8176d120)
Location: block/blk-iocost.c:2842
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8176d120-ffffffff8176d46a: blk_iocost_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_iocost_init(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817acc30)
Location: block/blk-iocost.c:2863
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff817acc30-ffffffff817ace85: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_iocost_init(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817f0a00)
Location: block/blk-iocost.c:2870
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff817f0a00-ffffffff817f0c84: blk_iocost_init (STB_LOCAL)
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
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff8000106155f8)
Location: block/blk-iocost.c:1911
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffff8000106155f8-ffff800010615820: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07bfde0)
Location: block/blk-iocost.c:1911
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
c07bfde0-c07bffc4: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b4d40)
Location: block/blk-iocost.c:1911
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
c0000000007b4d40-c0000000007b5008: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044c76a)
Location: block/blk-iocost.c:1911
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffe00044c76a-ffffffe00044c920: blk_iocost_init (STB_LOCAL)
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
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150a4c0)
Location: block/blk-iocost.c:1911
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8150a4c0-ffffffff8150a6b4: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814fa950)
Location: block/blk-iocost.c:1911
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff814fa950-ffffffff814fab3e: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81506550)
Location: block/blk-iocost.c:1911
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81506550-ffffffff81506744: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_iocost_init(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151f840)
Location: block/blk-iocost.c:1911
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8151f840-ffffffff8151fa2b: blk_iocost_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
