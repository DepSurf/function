# Function: <code>hlist_is_singular_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f27eb)
Location: include/linux/list.h:686
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
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
In kernel/time/timer.c (ffffffff810f996b)
Location: include/linux/list.h:702
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
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
In kernel/time/timer.c (ffffffff810fbe9b)
Location: include/linux/list.h:715
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
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
In kernel/time/timer.c (ffffffff8110678b)
Location: include/linux/list.h:716
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
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
In kernel/time/timer.c (ffffffff81113102)
Location: include/linux/list.h:716
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
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
In kernel/time/timer.c (ffffffff8111d412)
Location: include/linux/list.h:769
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
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
In kernel/time/timer.c (ffffffff811280db)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (ffffffff81952b4b)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (ffffffff8113407b)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (ffffffff81988e9b)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (ffffffff811441fb)
Location: include/linux/list.h:923
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60b3c)
Location: include/linux/list.h:923
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (ffffffff811407ab)
Location: include/linux/list.h:950
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122f9d8)
Location: include/linux/list.h:950
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
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
In kernel/time/timer.c (ffffffff8114192b)
Location: include/linux/list.h:950
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81224f78)
Location: include/linux/list.h:950
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
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
In kernel/time/timer.c (ffffffff81164e6b)
Location: include/linux/list.h:950
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125ceb8)
Location: include/linux/list.h:950
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
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
In kernel/time/timer.c (ffffffff81198a3b)
Location: include/linux/list.h:996
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a6f5c)
Location: include/linux/list.h:996
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
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
In kernel/time/timer.c (ffffffff811d6deb)
Location: include/linux/list.h:996
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8130540c)
Location: include/linux/list.h:996
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
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
In kernel/time/timer.c (ffffffff811eb27b)
Location: include/linux/list.h:1011
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81334370)
Location: include/linux/list.h:1011
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
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
In kernel/time/timer.c (ffffffff812012ab)
Location: include/linux/list.h:1100
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81358a5c)
Location: include/linux/list.h:1100
Inline: True
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
In kernel/time/timer.c (ffff80001019eadc)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (ffff800010c315d0)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (c03e748c)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (c0d47f90)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (c0000000001fc444)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (c000000000d2a130)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (ffffffe00012bd42)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a6fcc)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (ffffffff8112c82b)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (ffffffff81928d0b)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (ffffffff8111f09b)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (ffffffff818e2abb)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (ffffffff8112a54b)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (ffffffff81979e9b)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
In kernel/time/timer.c (ffffffff81137b0b)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In net/core/bpf_sk_storage.c (ffffffff8199c3cb)
Location: include/linux/list.h:829
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
</details>
</li>
</ul>

## Differences
