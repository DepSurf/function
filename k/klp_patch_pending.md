# Function: <code>klp_patch_pending</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ca462)
Location: include/linux/livepatch.h:156
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810d1c7d)
Location: include/linux/livepatch.h:182
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/signal.c (ffffffff8109cd32)
Location: include/linux/livepatch.h:178
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810c439b)
Location: include/linux/livepatch.h:178
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff8110c473)
Location: include/linux/livepatch.h:178
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
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
In kernel/signal.c (ffffffff810a4c72)
Location: include/linux/livepatch.h:178
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810cd65b)
Location: include/linux/livepatch.h:178
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff81117c63)
Location: include/linux/livepatch.h:178
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
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
In kernel/signal.c (ffffffff810a9973)
Location: include/linux/livepatch.h:194
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810d5a46)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff81121a9f)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/signal.c (ffffffff810aff63)
Location: include/linux/livepatch.h:194
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810e0056)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff8112e0bf)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/signal.c (ffffffff810b832e)
Location: include/linux/livepatch.h:205
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810e84a0)
Location: include/linux/livepatch.h:205
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff8113c4dd)
Location: include/linux/livepatch.h:205
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
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
In kernel/signal.c (ffffffff810b35de)
Location: include/linux/livepatch.h:205
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810e6090)
Location: include/linux/livepatch.h:205
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff81136bed)
Location: include/linux/livepatch.h:205
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
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
In kernel/sched/idle.c (ffffffff810e805a)
Location: include/linux/livepatch.h:205
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff81137e6f)
Location: include/linux/livepatch.h:205
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/sched/idle.c (ffffffff810ff71a)
Location: include/linux/livepatch.h:205
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff8115abc2)
Location: include/linux/livepatch.h:205
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/sched/build_policy.c (ffffffff81133727)
Location: include/linux/livepatch.h:203
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff81184489)
Location: include/linux/livepatch.h:203
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/sched/build_policy.c (ffffffff8115db47)
Location: include/linux/livepatch.h:203
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff811bf733)
Location: include/linux/livepatch.h:203
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/sched/build_policy.c (ffffffff8116e237)
Location: include/linux/livepatch.h:204
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff811d2213)
Location: include/linux/livepatch.h:204
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/sched/build_policy.c (ffffffff8117b7fc)
Location: include/linux/livepatch.h:204
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff811e6e93)
Location: include/linux/livepatch.h:204
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/signal.c (0)
Location: include/linux/livepatch.h:224
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/livepatch.h:224
Inline: True
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
In kernel/signal.c (0)
Location: include/linux/livepatch.h:224
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/livepatch.h:224
Inline: True
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
In kernel/signal.c (c00000000015225c)
Location: include/linux/livepatch.h:194
Inline: True
```
```
In kernel/sched/idle.c (c00000000018eea8)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (c0000000001f31c0)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/signal.c (0)
Location: include/linux/livepatch.h:224
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/linux/livepatch.h:224
Inline: True
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
In kernel/signal.c (ffffffff810aa2d3)
Location: include/linux/livepatch.h:194
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810da239)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff8112669f)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/signal.c (ffffffff81098c83)
Location: include/linux/livepatch.h:194
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810c922b)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff811190fb)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/signal.c (ffffffff810a9833)
Location: include/linux/livepatch.h:194
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810d6586)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff8112458f)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/signal.c (ffffffff810b1bc3)
Location: include/linux/livepatch.h:194
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810e1e86)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/livepatch/transition.c (ffffffff81130bea)
Location: include/linux/livepatch.h:194
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
</details>
</li>
</ul>

## Differences
