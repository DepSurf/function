# Function: <code>dd_insert_request</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814c7e77)
Location: block/mq-deadline.c:491
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814f6707)
Location: block/mq-deadline.c:493
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81514537)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81575387)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815921c4)
Location: block/mq-deadline.c:485
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815992e7)
Location: block/mq-deadline.c:484
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dd_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81601920)
Location: block/mq-deadline.c:659
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81601920-ffffffff81601b85: dd_insert_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (ffffffff816b43c0)
Location: block/mq-deadline.c:712
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff816b43c0-ffffffff816b4680: dd_insert_request.isra.0 (STB_LOCAL)
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
In block/mq-deadline.c (ffffffff81773dc0)
Location: block/mq-deadline.c:770
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81773dc0-ffffffff81774092: dd_insert_request.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:795
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff817b3f90-ffffffff817b435b: dd_insert_request.isra.0 (STB_LOCAL)
ffffffff820f6fd9-ffffffff820f7049: dd_insert_request.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:795
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff817f7f20-ffffffff817f830b: dd_insert_request.isra.0 (STB_LOCAL)
ffffffff821d4739-ffffffff821d483e: dd_insert_request.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffff800010619304)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c07c3c28)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c0000000007b86bc)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffe00044ee74)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff8150cb17)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814fcf47)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81508ba7)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815222a7)
Location: block/mq-deadline.c:483
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
