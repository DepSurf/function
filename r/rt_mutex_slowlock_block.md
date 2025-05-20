# Function: <code>rt_mutex_slowlock_block</code>

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
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d54900)
Location: kernel/locking/rtmutex.c:1472
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
```
**Symbols:**

```
ffffffff81d54900-ffffffff81d54a41: rt_mutex_slowlock_block.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f26460)
Location: kernel/locking/rtmutex.c:1483
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
```
**Symbols:**

```
ffffffff81f26460-ffffffff81f265e1: rt_mutex_slowlock_block.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d1f40)
Location: kernel/locking/rtmutex.c:1521
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
```
**Symbols:**

```
ffffffff820d1f40-ffffffff820d2073: rt_mutex_slowlock_block.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82156360)
Location: kernel/locking/rtmutex.c:1579
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
```
**Symbols:**

```
ffffffff82156360-ffffffff821564eb: rt_mutex_slowlock_block.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff822391a0)
Location: kernel/locking/rtmutex.c:1598
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_wait_proxy_lock
```
**Symbols:**

```
ffffffff822391a0-ffffffff8223932b: rt_mutex_slowlock_block.constprop.0 (STB_LOCAL)
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
