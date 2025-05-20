# Function: <code>dma_fence_parent</code>

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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
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
In drivers/dma-buf/sw_sync.c (ffffffff816418b6)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
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
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
```
```
In drivers/dma-buf/sync_debug.c (0)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
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
In drivers/dma-buf/sw_sync.c (ffffffff816e6ea5)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff816e73f1)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff8170a165)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8170a781)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff817459dd)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81745ff0)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff81769b5a)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8176a13f)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff8182bd25)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8182c25f)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff8183cd95)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8183d2bf)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff818201b5)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8182044f)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff818aa87f)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff818aab1f)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff819f477c)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff819f5140)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff81b71bac)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81b72620)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff81bc57dc)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81bc6020)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff81c1a1bc)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81c1ab40)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffff80001096b3c0)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffff80001096bcbc)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (c0a41020)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (c0a41810)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (c000000000a23e2c)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (c000000000a246bc)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffe0005d672a)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffe0005d6b4e)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff8171e24a)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8171e82f)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff816f756a)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff816f7c6f)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff8175d01a)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8175d5ff)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/sw_sync.c (ffffffff8177844a)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_timeline_value_str
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_get_timeline_name
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81778c8f)
Location: drivers/dma-buf/sync_debug.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
</details>
</li>
</ul>

## Differences
