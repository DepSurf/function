# Function: <code>rt_mutex_waiter_less</code>

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
In kernel/locking/rtmutex.c (ffffffff810cacfa)
Location: kernel/locking/rtmutex.c:160
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
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
In kernel/locking/rtmutex.c (ffffffff810cf861)
Location: kernel/locking/rtmutex.c:162
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff810d6241)
Location: kernel/locking/rtmutex.c:226
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff810d5181)
Location: kernel/locking/rtmutex.c:234
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff810dd030)
Location: kernel/locking/rtmutex.c:234
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff810e56d9)
Location: kernel/locking/rtmutex.c:234
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff810f0c69)
Location: kernel/locking/rtmutex.c:234
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff810f9384)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff81105174)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff8110ff68)
Location: kernel/locking/rtmutex.c:233
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff8110d118)
Location: kernel/locking/rtmutex.c:233
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff81c36f3d)
Location: kernel/locking/rtmutex.c:232
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
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
In kernel/locking/rtmutex_api.c (ffffffff81d554ad)
Location: kernel/locking/rtmutex.c:310
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27123)
Location: kernel/locking/rtmutex.c:312
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d2be3)
Location: kernel/locking/rtmutex.c:349
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
</details>
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
In kernel/locking/rtmutex.c (ffff80001016add8)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (c03b6958)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (c0000000001c26c0)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffe00010b44a)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff810fe484)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff810ee684)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff810fb644)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/locking/rtmutex.c (ffffffff81106814)
Location: kernel/locking/rtmutex.c:235
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
</details>
</li>
</ul>

## Differences
