# Function: <code>__rt_mutex_slowtrylock</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81993107)
Location: kernel/locking/rtmutex.c:1293
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff819ef6f2)
Location: kernel/locking/rtmutex.c:1292
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81a2aa45)
Location: kernel/locking/rtmutex.c:1292
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81a9b742)
Location: kernel/locking/rtmutex.c:1293
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81ad3092)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81bcb222)
Location: kernel/locking/rtmutex.c:1289
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81c440c2)
Location: kernel/locking/rtmutex.c:1289
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81c37458)
Location: kernel/locking/rtmutex.c:1254
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
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
In kernel/locking/rtmutex_api.c (ffffffff81d55c68)
Location: kernel/locking/rtmutex.c:1226
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
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
In kernel/locking/rtmutex_api.c (ffffffff81f27b48)
Location: kernel/locking/rtmutex.c:1238
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
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
In kernel/locking/rtmutex_api.c (ffffffff820d3668)
Location: kernel/locking/rtmutex.c:1276
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
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
In kernel/locking/rtmutex_api.c (ffffffff821578e8)
Location: kernel/locking/rtmutex.c:1334
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
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
In kernel/locking/rtmutex_api.c (ffffffff8223a758)
Location: kernel/locking/rtmutex.c:1353
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
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
In kernel/locking/rtmutex.c (ffff800010da5ae4)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (c0e9d958)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (c000000000ee81b4)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffe0008c8150)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81a71f02)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81a2e2d2)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81ade312)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
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
In kernel/locking/rtmutex.c (ffffffff81aea7c2)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
```
</details>
</li>
</ul>

## Differences
