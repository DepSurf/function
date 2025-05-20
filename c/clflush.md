# Function: <code>clflush</code>

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
In arch/x86/kernel/process.c (ffffffff810390ed)
Location: arch/x86/include/asm/special_insns.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810500f9)
Location: arch/x86/include/asm/special_insns.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81052838)
Location: arch/x86/include/asm/special_insns.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff81068189)
Location: arch/x86/include/asm/special_insns.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:tce_free
```
```
In drivers/idle/intel_idle.c (ffffffff81479456)
Location: arch/x86/include/asm/special_insns.h:191
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle_freeze
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
In arch/x86/kernel/process.c (ffffffff81038123)
Location: arch/x86/include/asm/special_insns.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81050255)
Location: arch/x86/include/asm/special_insns.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105298c)
Location: arch/x86/include/asm/special_insns.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff81067f52)
Location: arch/x86/include/asm/special_insns.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff814c78ff)
Location: arch/x86/include/asm/special_insns.h:229
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff818d3c7e)
Location: arch/x86/include/asm/special_insns.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3cf4)
Location: arch/x86/include/asm/special_insns.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81055295)
Location: arch/x86/include/asm/special_insns.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106bba2)
Location: arch/x86/include/asm/special_insns.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff814e982f)
Location: arch/x86/include/asm/special_insns.h:208
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff8190acf5)
Location: arch/x86/include/asm/special_insns.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8190ae54)
Location: arch/x86/include/asm/special_insns.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054b9b)
Location: arch/x86/include/asm/special_insns.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106af62)
Location: arch/x86/include/asm/special_insns.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff814f544f)
Location: arch/x86/include/asm/special_insns.h:212
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff81995068)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819951c4)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81058967)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106f862)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff81535ccf)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff819f15cf)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819f1724)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b5d3)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff81072732)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff8156b86e)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff81a2ca01)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cbc4)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106125d)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff81078782)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff815833ee)
Location: arch/x86/include/asm/special_insns.h:213
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff81a9cb5f)
Location: arch/x86/include/asm/special_insns.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd24)
Location: arch/x86/include/asm/special_insns.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064915)
Location: arch/x86/include/asm/special_insns.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c2f2)
Location: arch/x86/include/asm/special_insns.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b2f)
Location: arch/x86/include/asm/special_insns.h:222
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff81ad43af)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad4574)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064f95)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107d3e2)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff815d4d6f)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff81bcc49b)
Location: arch/x86/include/asm/special_insns.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068a96)
Location: arch/x86/include/asm/special_insns.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b6c3)
Location: arch/x86/include/asm/special_insns.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8167e8b6)
Location: arch/x86/include/asm/special_insns.h:208
Inline: True
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
In arch/x86/kernel/process.c (ffffffff81c451be)
Location: arch/x86/include/asm/special_insns.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a736)
Location: arch/x86/include/asm/special_insns.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d363)
Location: arch/x86/include/asm/special_insns.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5b6)
Location: arch/x86/include/asm/special_insns.h:210
Inline: True
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
In arch/x86/kernel/process.c (ffffffff81c3843b)
Location: arch/x86/include/asm/special_insns.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b1fd)
Location: arch/x86/include/asm/special_insns.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106ddd3)
Location: arch/x86/include/asm/special_insns.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8168033d)
Location: arch/x86/include/asm/special_insns.h:210
Inline: True
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
In arch/x86/kernel/process.c (ffffffff81d56cc8)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d1d)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff810795e3)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff816f50ad)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
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
In arch/x86/kernel/process.c (ffffffff81f28f4a)
Location: arch/x86/include/asm/special_insns.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81084766)
Location: arch/x86/include/asm/special_insns.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088473)
Location: arch/x86/include/asm/special_insns.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff818219d6)
Location: arch/x86/include/asm/special_insns.h:199
Inline: True
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
In arch/x86/kernel/process.c (ffffffff820d4c3e)
Location: arch/x86/include/asm/special_insns.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810979f6)
Location: arch/x86/include/asm/special_insns.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bf33)
Location: arch/x86/include/asm/special_insns.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff819526c6)
Location: arch/x86/include/asm/special_insns.h:199
Inline: True
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
In arch/x86/kernel/process.c (ffffffff8214302a)
Location: arch/x86/include/asm/special_insns.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff821430d9)
Location: arch/x86/include/asm/special_insns.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bdfd)
Location: arch/x86/include/asm/special_insns.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8214360e)
Location: arch/x86/include/asm/special_insns.h:178
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff82225717)
Location: arch/x86/include/asm/special_insns.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff822257be)
Location: arch/x86/include/asm/special_insns.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a33fd)
Location: arch/x86/include/asm/special_insns.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff82225d1e)
Location: arch/x86/include/asm/special_insns.h:178
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81a7321f)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a733e4)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064a85)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c3e2)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff815c8abf)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff81a2f5df)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f794)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054d5a)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106baff)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b2f)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff81adf62f)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf7f4)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064f35)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c392)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff815c904f)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/process.c (ffffffff81aebdbf)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aebfc4)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81066515)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107e492)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In drivers/idle/intel_idle.c (ffffffff815e2eaf)
Location: arch/x86/include/asm/special_insns.h:198
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
</details>
</li>
</ul>

## Differences
