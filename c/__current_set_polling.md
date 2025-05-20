# Function: <code>__current_set_polling</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038fa6)
Location: include/linux/sched.h:2986
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810500cf)
Location: include/linux/sched.h:2986
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810c3deb)
Location: include/linux/sched.h:2986
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In drivers/idle/intel_idle.c (ffffffff8147942c)
Location: include/linux/sched.h:2986
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle_freeze
```
```
In drivers/cpuidle/driver.c (ffffffff816bc070)
Location: include/linux/sched.h:2986
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81037fe6)
Location: include/linux/sched.h:3263
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810502b7)
Location: include/linux/sched.h:3263
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810c7aea)
Location: include/linux/sched.h:3263
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In drivers/idle/intel_idle.c (ffffffff814c7963)
Location: include/linux/sched.h:3263
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/driver.c (ffffffff8171d980)
Location: include/linux/sched.h:3263
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff818d3b56)
Location: include/linux/sched.h:3432
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3d40)
Location: include/linux/sched.h:3432
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810cd912)
Location: include/linux/sched.h:3432
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814e987d)
Location: include/linux/sched.h:3432
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/driver.c (ffffffff818d4040)
Location: include/linux/sched.h:3432
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff8190ac96)
Location: include/linux/sched/idle.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8190aea0)
Location: include/linux/sched/idle.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810ca322)
Location: include/linux/sched/idle.h:21
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814f549d)
Location: include/linux/sched/idle.h:21
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/driver.c (ffffffff8190b1d0)
Location: include/linux/sched/idle.h:21
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81995006)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81995213)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810d1b40)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff81535d20)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81995560)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff819f1585)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819f1771)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810c4265)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff8156b8c1)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff819f1ab5)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81a2c9b5)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cc11)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810cd51c)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff81583441)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2cfd4)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81a9cb15)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd7f)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810d5915)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b8c)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a9d146)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81ad4365)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad45cf)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810dff25)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff815d4dcc)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81ad4996)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81bcc455)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068af0)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/idle.c (ffffffff810e840d)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff8167e912)
Location: include/linux/sched/idle.h:22
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81bcc954)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81c45155)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a790)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/idle.c (ffffffff810e5ffd)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff8169d612)
Location: include/linux/sched/idle.h:22
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c454b4)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81c383d5)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b257)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/idle.c (ffffffff810e7fba)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff81680399)
Location: include/linux/sched/idle.h:22
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c38734)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81d56c65)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d74)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/idle.c (ffffffff810ff67a)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff816f5106)
Location: include/linux/sched/idle.h:22
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81d57014)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81f28ed5)
Location: include/linux/sched/idle.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810847cb)
Location: include/linux/sched/idle.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/build_policy.c (ffffffff8113368a)
Location: include/linux/sched/idle.h:26
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff81821a3b)
Location: include/linux/sched/idle.h:26
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81f299e3)
Location: include/linux/sched/idle.h:26
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff820d4bc5)
Location: include/linux/sched/idle.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a5b)
Location: include/linux/sched/idle.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/build_policy.c (ffffffff8115daaa)
Location: include/linux/sched/idle.h:26
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff8195272b)
Location: include/linux/sched/idle.h:26
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff820d5843)
Location: include/linux/sched/idle.h:26
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff82142fb0)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff82143144)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/build_policy.c (ffffffff8116e19a)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff8214367a)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff82144017)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff822256a0)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8222584c)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/build_policy.c (ffffffff8117b75a)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff82225d8a)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff82226737)
Location: include/linux/sched/idle.h:28
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In kernel/sched/idle.c (0)
Location: include/linux/sched/idle.h:59
Inline: True
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
In kernel/sched/idle.c (0)
Location: include/linux/sched/idle.h:59
Inline: True
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
In kernel/sched/idle.c (c00000000018ec98)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (0)
Location: include/linux/sched/idle.h:59
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
In arch/x86/kernel/process.c (ffffffff81a731d5)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a7343f)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810da115)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff815c8b1c)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a73806)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81a2f595)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7ef)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810c9105)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b8c)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2fb80)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81adf5e5)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf84f)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810d6455)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff815c90ac)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81adfc16)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/process.c (ffffffff81aebd75)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aec01f)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810e1d55)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff815e2f0c)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81aec416)
Location: include/linux/sched/idle.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
</details>
</li>
</ul>

## Differences
