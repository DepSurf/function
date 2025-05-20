# Function: <code>clear_rt_mutex_waiters</code>

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
In kernel/locking/rtmutex.c (ffffffff818228d8)
Location: kernel/locking/rtmutex.c:60
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
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
In kernel/locking/rtmutex.c (ffffffff810d04a2)
Location: kernel/locking/rtmutex.c:60
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
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
In kernel/locking/rtmutex.c (ffffffff818d1ccf)
Location: kernel/locking/rtmutex.c:60
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81908e98)
Location: kernel/locking/rtmutex.c:62
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81992fa8)
Location: kernel/locking/rtmutex.c:62
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff819ef597)
Location: kernel/locking/rtmutex.c:62
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81a2a8d7)
Location: kernel/locking/rtmutex.c:62
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81a9b5d2)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81ad2f22)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81bcafd2)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81c43e62)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81c35e21)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff81d5462a)
Location: kernel/locking/rtmutex.c:101
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff81f26163)
Location: kernel/locking/rtmutex.c:103
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff820d1c23)
Location: kernel/locking/rtmutex.c:119
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff82155f83)
Location: kernel/locking/rtmutex.c:119
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff82238dc3)
Location: kernel/locking/rtmutex.c:119
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rtmutex.c (ffff800010da56ec)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (c0e9d62c)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (c000000000ee7d70)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffe0008c7ff8)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81a71d92)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81a2e162)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81ade1a2)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
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
In kernel/locking/rtmutex.c (ffffffff81aea642)
Location: kernel/locking/rtmutex.c:63
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
</details>
</li>
</ul>

## Differences
