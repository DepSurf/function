# Function: <code>current_wq_worker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810983a5)
Location: kernel/workqueue_internal.h:60
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:set_worker_desc
```
```
In kernel/async.c (ffffffff810a31e5)
Location: kernel/workqueue_internal.h:60
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109fa7c)
Location: kernel/workqueue_internal.h:60
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810a68f5)
Location: kernel/workqueue_internal.h:60
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a494c)
Location: kernel/workqueue_internal.h:60
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810ac555)
Location: kernel/workqueue_internal.h:60
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1a85)
Location: kernel/workqueue_internal.h:60
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810a9125)
Location: kernel/workqueue_internal.h:60
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
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
In kernel/workqueue.c (ffffffff810a830f)
Location: kernel/workqueue_internal.h:62
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810af9a6)
Location: kernel/workqueue_internal.h:62
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
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
In kernel/workqueue.c (ffffffff810aae47)
Location: kernel/workqueue_internal.h:61
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810b6805)
Location: kernel/workqueue_internal.h:61
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b3ec7)
Location: kernel/workqueue_internal.h:64
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810bfc55)
Location: kernel/workqueue_internal.h:64
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9968)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810c5d85)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bfde8)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810cee65)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7138)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810d8b65)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c24f8)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810d3d05)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4188)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810d5995)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d6db8)
Location: kernel/workqueue_internal.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810e8bb5)
Location: kernel/workqueue_internal.h:66
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f0997)
Location: kernel/workqueue_internal.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff81103685)
Location: kernel/workqueue_internal.h:66
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811126d7)
Location: kernel/workqueue_internal.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff81128d65)
Location: kernel/workqueue_internal.h:66
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111ecd7)
Location: kernel/workqueue_internal.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff81136215)
Location: kernel/workqueue_internal.h:67
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811280f7)
Location: kernel/workqueue_internal.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:delayed_work_timer_fn
  - kernel/workqueue.c:delayed_work_timer_fn
```
```
In kernel/async.c (ffffffff811413c5)
Location: kernel/workqueue_internal.h:67
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011c860)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffff80001012e430)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0371d38)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (c037e954)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000166924)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (c000000000177a60)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d6f4a)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffe0000e29c6)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ba158)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810c91e5)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a8a98)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810b7a05)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b96b8)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810c8715)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c26f8)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/async.c (ffffffff810d0c55)
Location: kernel/workqueue_internal.h:65
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
```
</details>
</li>
</ul>

## Differences
