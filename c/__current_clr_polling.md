# Function: <code>__current_clr_polling</code>

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
In arch/x86/kernel/process.c (ffffffff81039023)
Location: include/linux/sched.h:3004
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105012f)
Location: include/linux/sched.h:3004
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810c3ce5)
Location: include/linux/sched.h:3004
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In drivers/idle/intel_idle.c (ffffffff8147948e)
Location: include/linux/sched.h:3004
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle_freeze
```
```
In drivers/cpuidle/driver.c (ffffffff816bc0a4)
Location: include/linux/sched.h:3004
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
In arch/x86/kernel/process.c (ffffffff81038065)
Location: include/linux/sched.h:3281
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105028b)
Location: include/linux/sched.h:3281
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810c7beb)
Location: include/linux/sched.h:3281
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In drivers/idle/intel_idle.c (ffffffff814c7937)
Location: include/linux/sched.h:3281
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/driver.c (ffffffff8171d9b4)
Location: include/linux/sched.h:3281
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
In arch/x86/kernel/process.c (ffffffff818d3bc3)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3d1b)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810cda34)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814e9858)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/driver.c (ffffffff818d4065)
Location: include/linux/sched.h:3450
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
In arch/x86/kernel/process.c (ffffffff8190ad30)
Location: include/linux/sched/idle.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8190ae7b)
Location: include/linux/sched/idle.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810ca445)
Location: include/linux/sched/idle.h:39
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814f5478)
Location: include/linux/sched/idle.h:39
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/driver.c (ffffffff8190b1f0)
Location: include/linux/sched/idle.h:39
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
In arch/x86/kernel/process.c (ffffffff819950a3)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819951eb)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810d1c60)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff81535cf8)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff8199558a)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff819f160a)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819f1749)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810c438c)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff8156b899)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff819f1aca)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81a2ca3c)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cbe9)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810cd64c)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff81583419)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2d05f)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81a9cba3)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd57)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810d5a35)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b64)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a9d1df)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81ad43f3)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad45a7)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810e0045)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff815d4da4)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81ad49e7)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81bcc4e8)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068ac9)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/idle.c (ffffffff810e848f)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff8167e8eb)
Location: include/linux/sched/idle.h:40
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81bcc96a)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81c451ab)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a769)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/idle.c (ffffffff810e607f)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5eb)
Location: include/linux/sched/idle.h:40
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c454ca)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81c38428)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b230)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/idle.c (ffffffff810e8049)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff81680372)
Location: include/linux/sched/idle.h:40
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c3874a)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81d56cb5)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d4d)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/idle.c (ffffffff810ff709)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff816f50df)
Location: include/linux/sched/idle.h:40
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81d5702a)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81f28f2d)
Location: include/linux/sched/idle.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81084796)
Location: include/linux/sched/idle.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/build_policy.c (ffffffff81133718)
Location: include/linux/sched/idle.h:44
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff81821a08)
Location: include/linux/sched/idle.h:44
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81f299f9)
Location: include/linux/sched/idle.h:44
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
In arch/x86/kernel/process.c (ffffffff820d4c1d)
Location: include/linux/sched/idle.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a26)
Location: include/linux/sched/idle.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In kernel/sched/build_policy.c (ffffffff8115db38)
Location: include/linux/sched/idle.h:44
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff819526f8)
Location: include/linux/sched/idle.h:44
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff820d5859)
Location: include/linux/sched/idle.h:44
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
In arch/x86/kernel/process.c (ffffffff82143009)
Location: include/linux/sched/idle.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff82143109)
Location: include/linux/sched/idle.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/build_policy.c (ffffffff8116e228)
Location: include/linux/sched/idle.h:34
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff82143640)
Location: include/linux/sched/idle.h:34
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff82144065)
Location: include/linux/sched/idle.h:34
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
In arch/x86/kernel/process.c (ffffffff822256f6)
Location: include/linux/sched/idle.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff822257f4)
Location: include/linux/sched/idle.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/build_policy.c (ffffffff8117b7ed)
Location: include/linux/sched/idle.h:34
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff82225d50)
Location: include/linux/sched/idle.h:34
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff82226785)
Location: include/linux/sched/idle.h:34
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
Location: include/linux/sched/idle.h:60
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
Location: include/linux/sched/idle.h:60
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
In kernel/sched/idle.c (c00000000018ee78)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
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
Location: include/linux/sched/idle.h:60
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
In arch/x86/kernel/process.c (ffffffff81a73263)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a73417)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810da228)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff815c8af4)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a73857)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81a2f623)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7c7)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810c921a)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b64)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2fbd1)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81adf673)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf827)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810d6575)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff815c9084)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81adfc67)
Location: include/linux/sched/idle.h:40
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
In arch/x86/kernel/process.c (ffffffff81aebe03)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aebff7)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/idle.c (ffffffff810e1e75)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
```
```
In drivers/idle/intel_idle.c (ffffffff815e2ee4)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81aec467)
Location: include/linux/sched/idle.h:40
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
</details>
</li>
</ul>

## Differences
