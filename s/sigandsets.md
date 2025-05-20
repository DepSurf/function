# Function: <code>sigandsets</code>

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
In kernel/signal.c (ffffffff8108cf25)
Location: include/linux/signal.h:117
Inline: True
Inline callers:
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:SyS_sigpending
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
In kernel/signal.c (ffffffff81094edc)
Location: include/linux/signal.h:132
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff81099edc)
Location: include/linux/signal.h:149
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff8109703c)
Location: include/linux/signal.h:127
Inline: True
Inline callers:
  - kernel/signal.c:compat_SyS_sigpending
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff8109a0c6)
Location: include/linux/signal.h:142
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff8109cfad)
Location: include/linux/signal.h:144
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810a52bd)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810a9f82)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810b0562)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810b91db)
Location: include/linux/signal.h:158
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810b448b)
Location: include/linux/signal.h:158
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810b609c)
Location: include/linux/signal.h:160
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810c8f2c)
Location: include/linux/signal.h:160
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810e04c2)
Location: include/linux/signal.h:159
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff81100b59)
Location: include/linux/signal.h:159
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff811096f9)
Location: include/linux/signal.h:159
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff81113099)
Location: include/linux/signal.h:160
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffff80001010b5fc)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (c03655f8)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (c000000000152d58)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffe0000d148a)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:__se_sys_rt_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810aa8d2)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff8109927c)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810a9e32)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
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
In kernel/signal.c (ffffffff810b0f19)
Location: include/linux/signal.h:150
Inline: True
Inline callers:
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:flush_sigqueue_mask
```
</details>
</li>
</ul>

## Differences
