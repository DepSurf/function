# Function: <code>cfq_cfqq_sync</code>

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
In block/cfq-iosched.c (0)
Location: block/cfq-iosched.c:449
Inline: True
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
In block/cfq-iosched.c (ffffffff8142b08c)
Location: block/cfq-iosched.c:449
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_set_prio_slice
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
In block/cfq-iosched.c (ffffffff81444f55)
Location: block/cfq-iosched.c:450
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_set_prio_slice
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
In block/cfq-iosched.c (ffffffff814540dc)
Location: block/cfq-iosched.c:455
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
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
In block/cfq-iosched.c (ffffffff8147ff59)
Location: block/cfq-iosched.c:456
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
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
In block/cfq-iosched.c (ffffffff814b27c5)
Location: block/cfq-iosched.c:456
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_should_idle
  - block/cfq-iosched.c:cfq_should_idle
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_deactivate_request
  - block/cfq-iosched.c:cfq_activate_request
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
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
