# Function: <code>__mutex_trylock</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d05d6)
Location: kernel/locking/mutex.c:82
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:__mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
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
In kernel/locking/mutex.c (ffffffff81907b15)
Location: kernel/locking/mutex.c:123
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
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
In kernel/locking/mutex.c (ffffffff81991c05)
Location: kernel/locking/mutex.c:123
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
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
In kernel/locking/mutex.c (ffffffff819ee095)
Location: kernel/locking/mutex.c:123
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
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
In kernel/locking/mutex.c (ffffffff81a29305)
Location: kernel/locking/mutex.c:123
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
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
In kernel/locking/mutex.c (ffffffff81a99995)
Location: kernel/locking/mutex.c:124
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
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
In kernel/locking/mutex.c (ffffffff811035ee)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffff8110e10e)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffff8110b3ce)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffff81c34255)
Location: kernel/locking/mutex.c:140
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
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
In kernel/locking/mutex.c (ffffffff81d52b45)
Location: kernel/locking/mutex.c:144
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
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
In kernel/locking/mutex.c (ffffffff8114dbc3)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
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
In kernel/locking/mutex.c (ffffffff8117cd73)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
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
In kernel/locking/mutex.c (ffffffff8118da4f)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
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
In kernel/locking/mutex.c (ffffffff8119c3ff)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
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
In kernel/locking/mutex.c (ffff8000101687ac)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (c03b4ec0)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (c0000000001c056c)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffe00010a4ca)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffff810fc8fe)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffff810ecb0e)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffff810f9abe)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffff81104c2e)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
</li>
</ul>

## Differences
