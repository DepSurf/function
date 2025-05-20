# Function: <code>blk_mq_put_rq_ref</code>

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
void blk_mq_put_rq_ref(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81575a20)
Location: block/blk-mq.c:912
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff81575a20-ffffffff81575a7f: blk_mq_put_rq_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_put_rq_ref(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d9f30)
Location: block/blk-mq.c:918
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff815d9f30-ffffffff815d9f99: blk_mq_put_rq_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_put_rq_ref(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816879a0)
Location: block/blk-mq.c:1458
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff816879a0-ffffffff81687a0a: blk_mq_put_rq_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_put_rq_ref(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745d30)
Location: block/blk-mq.c:1591
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff81745d30-ffffffff81745db7: blk_mq_put_rq_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_put_rq_ref(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81782540)
Location: block/blk-mq.c:1584
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff81782540-ffffffff817825c7: blk_mq_put_rq_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_put_rq_ref(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c48e0)
Location: block/blk-mq.c:1599
Inline: False
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
  - block/blk-mq-tag.c:bt_iter
```
**Symbols:**

```
ffffffff817c48e0-ffffffff817c4967: blk_mq_put_rq_ref (STB_GLOBAL)
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
