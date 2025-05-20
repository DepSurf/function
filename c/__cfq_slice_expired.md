# Function: <code>__cfq_slice_expired</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool timed_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff813e1c60)
Location: block/cfq-iosched.c:2640
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_completed_request
```
**Symbols:**

```
ffffffff813e1c60-ffffffff813e21dd: __cfq_slice_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool timed_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81427e90)
Location: block/cfq-iosched.c:2671
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff81427e90-ffffffff81428410: __cfq_slice_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool timed_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff81440640)
Location: block/cfq-iosched.c:2663
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff81440640-ffffffff81440a36: __cfq_slice_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool timed_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8144f9b0)
Location: block/cfq-iosched.c:2668
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff8144f9b0-ffffffff8144fd5b: __cfq_slice_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool timed_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff8147d4a0)
Location: block/cfq-iosched.c:2644
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff8147d4a0-ffffffff8147da59: __cfq_slice_expired (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __cfq_slice_expired(struct cfq_data *cfqd, struct cfq_queue *cfqq, bool timed_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cfq-iosched.c (ffffffff814b1b80)
Location: block/cfq-iosched.c:2647
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff814b1b80-ffffffff814b214f: __cfq_slice_expired (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
