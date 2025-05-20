# Function: <code>__rt_mutex_lock</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819ef9f5)
Location: kernel/locking/rtmutex.c:1468
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81a2ad45)
Location: kernel/locking/rtmutex.c:1468
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81a9ba35)
Location: kernel/locking/rtmutex.c:1469
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81ad3385)
Location: kernel/locking/rtmutex.c:1467
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81bcb475)
Location: kernel/locking/rtmutex.c:1465
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81c4431e)
Location: kernel/locking/rtmutex.c:1465
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81c3723e)
Location: kernel/locking/rtmutex.c:1379
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex_api.c (ffffffff81d55b53)
Location: kernel/locking/rtmutex.c:1643
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
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
In kernel/locking/rtmutex_api.c (ffffffff81f2794c)
Location: kernel/locking/rtmutex.c:1659
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
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
In kernel/locking/rtmutex_api.c (ffffffff820d343c)
Location: kernel/locking/rtmutex.c:1697
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
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
In kernel/locking/rtmutex_api.c (ffffffff82157728)
Location: kernel/locking/rtmutex.c:1755
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
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
In kernel/locking/rtmutex_api.c (ffffffff8223a578)
Location: kernel/locking/rtmutex.c:1784
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffff800010da5d80)
Location: kernel/locking/rtmutex.c:1467
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (c0e9dbb8)
Location: kernel/locking/rtmutex.c:1467
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (c000000000ee8430)
Location: kernel/locking/rtmutex.c:1467
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffe0008c83aa)
Location: kernel/locking/rtmutex.c:1467
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81a721f5)
Location: kernel/locking/rtmutex.c:1467
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81a2e5c5)
Location: kernel/locking/rtmutex.c:1467
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81ade605)
Location: kernel/locking/rtmutex.c:1467
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
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
In kernel/locking/rtmutex.c (ffffffff81aeaab5)
Location: kernel/locking/rtmutex.c:1467
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
</details>
</li>
</ul>

## Differences
