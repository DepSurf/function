# Function: <code>queued_to_index</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142364e)
Location: block/blk-mq.c:807
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81431a44)
Location: block/blk-mq.c:849
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145d3bb)
Location: block/blk-mq.c:961
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81490e5b)
Location: block/blk-mq.c:959
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9cf7)
Location: block/blk-mq.c:1033
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814d7ca2)
Location: block/blk-mq.c:1032
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814f101e)
Location: block/blk-mq.c:1048
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int queued_to_index(unsigned int queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e300)
Location: block/blk-mq.c:1047
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff8154e300-ffffffff8154e31d: queued_to_index (STB_LOCAL)
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
In block/blk-mq.c (ffffffff8156e2be)
Location: block/blk-mq.c:1097
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff81575e43)
Location: block/blk-mq.c:1055
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da982)
Location: block/blk-mq.c:1061
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f04b4)
Location: block/blk-mq.c:1048
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (c079c804)
Location: block/blk-mq.c:1048
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (c000000000786e04)
Location: block/blk-mq.c:1048
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffe00042f374)
Location: block/blk-mq.c:1048
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814e95fe)
Location: block/blk-mq.c:1048
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814d9b6e)
Location: block/blk-mq.c:1048
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814e568e)
Location: block/blk-mq.c:1048
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814fe5ee)
Location: block/blk-mq.c:1048
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
