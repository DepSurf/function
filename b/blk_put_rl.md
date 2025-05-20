# Function: <code>blk_put_rl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b6683)
Location: include/linux/blk-cgroup.h:463
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fd20b)
Location: include/linux/blk-cgroup.h:463
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414fb4)
Location: include/linux/blk-cgroup.h:454
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
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
In block/blk-core.c (ffffffff8142355b)
Location: include/linux/blk-cgroup.h:454
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144eefb)
Location: include/linux/blk-cgroup.h:450
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8145ac9a)
Location: include/linux/blk-cgroup.h:450
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81481ac2)
Location: include/linux/blk-cgroup.h:468
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8148dd49)
Location: include/linux/blk-cgroup.h:468
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
