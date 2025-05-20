# Function: <code>test_and_clear_tsk_thread_flag</code>

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
In arch/x86/kernel/step.c (ffffffff8103deb2)
Location: include/linux/sched.h:2869
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103dcd2)
Location: include/linux/sched.h:3146
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In mm/oom_kill.c (ffffffff811a4f75)
Location: include/linux/sched.h:3146
Inline: True
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
In arch/x86/kernel/step.c (ffffffff8103d59b)
Location: include/linux/sched.h:3302
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
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
In arch/x86/kernel/step.c (ffffffff8103b5eb)
Location: include/linux/sched.h:1497
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff810f8e09)
Location: include/linux/sched.h:1497
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/step.c (ffffffff8103e00b)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff81103829)
Location: include/linux/sched.h:1531
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/step.c (ffffffff8103f5bb)
Location: include/linux/sched.h:1653
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810436a7)
Location: include/linux/sched.h:1653
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In kernel/livepatch/transition.c (ffffffff8110c558)
Location: include/linux/sched.h:1653
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103a315)
Location: include/linux/sched.h:1666
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff81040bbb)
Location: include/linux/sched.h:1666
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff81117d48)
Location: include/linux/sched.h:1666
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103c8d5)
Location: include/linux/sched.h:1739
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff8104329b)
Location: include/linux/sched.h:1739
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff81122089)
Location: include/linux/sched.h:1739
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103d095)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff810439fb)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff8112e6a9)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103ff35)
Location: include/linux/sched.h:1782
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff8104729b)
Location: include/linux/sched.h:1782
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff8113c859)
Location: include/linux/sched.h:1782
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff8103fe75)
Location: include/linux/sched.h:1843
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff81046af0)
Location: include/linux/sched.h:1843
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff81136f69)
Location: include/linux/sched.h:1843
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff81041805)
Location: include/linux/sched.h:1865
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff81048520)
Location: include/linux/sched.h:1865
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff81137c39)
Location: include/linux/sched.h:1865
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff81047aa5)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff8104ee60)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff8115a989)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff81050bf5)
Location: include/linux/sched.h:2004
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff8105a0b0)
Location: include/linux/sched.h:2004
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff8118423c)
Location: include/linux/sched.h:2004
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff8105e155)
Location: include/linux/sched.h:2031
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff81067ac0)
Location: include/linux/sched.h:2031
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff811bf4cc)
Location: include/linux/sched.h:2031
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff8105f805)
Location: include/linux/sched.h:2039
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff81069370)
Location: include/linux/sched.h:2039
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff811d1fac)
Location: include/linux/sched.h:2039
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/x86/kernel/process.c (ffffffff81066965)
Location: include/linux/sched.h:1941
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff810707e0)
Location: include/linux/sched.h:1941
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff811e6c2c)
Location: include/linux/sched.h:1941
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
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
In arch/arm64/kernel/fpsimd.c (ffff8000100882c0)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:sve_set_vector_length
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f3a60)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/process.c (ffffffff8103d215)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff81043b7b)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff81126c89)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8102c8c5)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff810331ab)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff811196e9)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103d055)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff810439bb)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff81124b79)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
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
In arch/x86/kernel/process.c (ffffffff8103e0e5)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/step.c (ffffffff81044dbb)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In kernel/livepatch/transition.c (ffffffff8113098c)
Location: include/linux/sched.h:1732
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
</details>
</li>
</ul>

## Differences
