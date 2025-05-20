# Function: <code>__rt_mutex_base_init</code>

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
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55d75)
Location: kernel/locking/rtmutex_common.h:158
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:__rt_mutex_init
  - kernel/locking/rtmutex_api.c:rt_mutex_base_init
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
In kernel/locking/rtmutex_api.c (ffffffff81f27ca5)
Location: kernel/locking/rtmutex_common.h:158
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:__rt_mutex_init
  - kernel/locking/rtmutex_api.c:rt_mutex_base_init
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
In kernel/locking/rtmutex_api.c (ffffffff820d37f5)
Location: kernel/locking/rtmutex_common.h:158
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:__rt_mutex_init
  - kernel/locking/rtmutex_api.c:rt_mutex_base_init
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
In kernel/locking/rtmutex_api.c (ffffffff82157a75)
Location: kernel/locking/rtmutex_common.h:179
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:__rt_mutex_init
  - kernel/locking/rtmutex_api.c:rt_mutex_base_init
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
In kernel/locking/rtmutex_api.c (ffffffff8223a8e5)
Location: kernel/locking/rtmutex_common.h:179
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_init_proxy_locked
  - kernel/locking/rtmutex_api.c:__rt_mutex_init
  - kernel/locking/rtmutex_api.c:rt_mutex_base_init
```
</details>
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
