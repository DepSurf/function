# Function: <code>__mutex_unlock_fast</code>

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
In kernel/locking/mutex.c (ffffffff818d0575)
Location: kernel/locking/mutex.c:146
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff81907ab5)
Location: kernel/locking/mutex.c:149
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff81991ba6)
Location: kernel/locking/mutex.c:149
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff819ee215)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff81a29485)
Location: kernel/locking/mutex.c:150
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff81a99b15)
Location: kernel/locking/mutex.c:151
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff81ad1465)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff8110e1b8)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
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
In kernel/locking/mutex.c (ffffffff8110b478)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
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
In kernel/locking/mutex.c (ffffffff8110d298)
Location: kernel/locking/mutex.c:167
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
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
In kernel/locking/mutex.c (ffffffff8112cad8)
Location: kernel/locking/mutex.c:171
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
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
In kernel/locking/mutex.c (ffffffff8114dd30)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
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
In kernel/locking/mutex.c (ffffffff8117cef0)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
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
In kernel/locking/mutex.c (ffffffff8118dba0)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
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
In kernel/locking/mutex.c (ffffffff8119c550)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
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
In kernel/locking/mutex.c (ffff800010da2f70)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (c0e9b5e8)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (c000000000ee5240)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffe0008c6b72)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff81a702d5)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff81a2c6c5)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff81adc6e5)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
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
In kernel/locking/mutex.c (ffffffff81ae8ad5)
Location: kernel/locking/mutex.c:177
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
```
</details>
</li>
</ul>

## Differences
