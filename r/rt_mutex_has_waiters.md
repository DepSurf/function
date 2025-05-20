# Function: <code>rt_mutex_has_waiters</code>

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
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex_common.h:41
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
In kernel/locking/rtmutex.c (ffffffff810d047a)
Location: kernel/locking/rtmutex_common.h:41
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff810d6e6b)
Location: kernel/locking/rtmutex_common.h:41
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff810d5ee3)
Location: kernel/locking/rtmutex_common.h:43
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff810ddea3)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff810e64f3)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff810f1a73)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff810fa374)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff81106164)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff81111102)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff8110e2b2)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff81c37792)
Location: kernel/locking/rtmutex_common.h:45
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
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
In kernel/locking/rtmutex_api.c (ffffffff81d55f62)
Location: kernel/locking/rtmutex_common.h:93
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
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
In kernel/locking/rtmutex_api.c (ffffffff81f27f03)
Location: kernel/locking/rtmutex_common.h:93
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
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
In kernel/locking/rtmutex_api.c (ffffffff820d3aa3)
Location: kernel/locking/rtmutex_common.h:93
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82157d23)
Location: kernel/locking/rtmutex_common.h:110
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223ab93)
Location: kernel/locking/rtmutex_common.h:110
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
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
In kernel/locking/rtmutex.c (ffff80001016c4b4)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (c03b7cdc)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (c0000000001c4054)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffe00010c5ba)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff810ff474)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff810ef664)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff810fc634)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
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
In kernel/locking/rtmutex.c (ffffffff81107864)
Location: kernel/locking/rtmutex_common.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_next_owner
  - kernel/locking/rtmutex.c:rt_mutex_proxy_unlock
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
</details>
</li>
</ul>

## Differences
