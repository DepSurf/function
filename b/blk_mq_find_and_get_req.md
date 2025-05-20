# Function: <code>blk_mq_find_and_get_req</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request *blk_mq_find_and_get_req(struct blk_mq_tags *tags, unsigned int bitnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81578e70)
Location: block/blk-mq-tag.c:202
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff81578e70-ffffffff81578ef4: blk_mq_find_and_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request *blk_mq_find_and_get_req(struct blk_mq_tags *tags, unsigned int bitnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815de0a0)
Location: block/blk-mq-tag.c:203
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff815de0a0-ffffffff815de12b: blk_mq_find_and_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request *blk_mq_find_and_get_req(struct blk_mq_tags *tags, unsigned int bitnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8168bfa0)
Location: block/blk-mq-tag.c:249
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff8168bfa0-ffffffff8168c016: blk_mq_find_and_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request *blk_mq_find_and_get_req(struct blk_mq_tags *tags, unsigned int bitnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174a710)
Location: block/blk-mq-tag.c:245
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff8174a710-ffffffff8174a786: blk_mq_find_and_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request *blk_mq_find_and_get_req(struct blk_mq_tags *tags, unsigned int bitnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81786df0)
Location: block/blk-mq-tag.c:252
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff81786df0-ffffffff81786e66: blk_mq_find_and_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request *blk_mq_find_and_get_req(struct blk_mq_tags *tags, unsigned int bitnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817c94d0)
Location: block/blk-mq-tag.c:252
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff817c94d0-ffffffff817c9546: blk_mq_find_and_get_req (STB_LOCAL)
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
