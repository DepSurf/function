# Function: <code>rb_erase_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813d9615)
Location: block/blk-throttle.c:425
Inline: True
Inline callers:
  - block/blk-throttle.c:__throtl_dequeue_tg
```
```
In block/cfq-iosched.c (ffffffff813dd74c)
Location: block/cfq-iosched.c:1191
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_del_cfqq_rr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8141f435)
Location: block/blk-throttle.c:419
Inline: True
Inline callers:
  - block/blk-throttle.c:__throtl_dequeue_tg
```
```
In block/cfq-iosched.c (ffffffff81427023)
Location: block/cfq-iosched.c:1214
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_del
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143a9f5)
Location: block/blk-throttle.c:419
Inline: True
Inline callers:
  - block/blk-throttle.c:__throtl_dequeue_tg
```
```
In block/cfq-iosched.c (ffffffff8143eee0)
Location: block/cfq-iosched.c:1205
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_del
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814486ae)
Location: block/blk-throttle.c:634
Inline: True
Inline callers:
  - block/blk-throttle.c:__throtl_dequeue_tg
```
```
In block/cfq-iosched.c (ffffffff8144e25c)
Location: block/cfq-iosched.c:1201
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_del
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
In block/blk-throttle.c (ffffffff8147525e)
Location: block/blk-throttle.c:632
Inline: True
Inline callers:
  - block/blk-throttle.c:__throtl_dequeue_tg
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
In block/blk-throttle.c (ffffffff814a96d0)
Location: block/blk-throttle.c:630
Inline: True
Inline callers:
  - block/blk-throttle.c:__throtl_dequeue_tg
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
