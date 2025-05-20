# Function: <code>get_desc_base</code>

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
In arch/x86/events/core.c (ffffffff81004e74)
Location: arch/x86/include/asm/desc.h:283
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/include/asm/desc.h:283
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c079)
Location: arch/x86/include/asm/desc.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
```
```
In arch/x86/kernel/tls.c (0)
Location: arch/x86/include/asm/desc.h:283
Inline: True
```
```
In arch/x86/kernel/step.c (ffffffff8103dbab)
Location: arch/x86/include/asm/desc.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
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
In arch/x86/events/core.c (ffffffff810050b1)
Location: arch/x86/include/asm/desc.h:283
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/tls.c (ffffffff8103d347)
Location: arch/x86/include/asm/desc.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff8103da01)
Location: arch/x86/include/asm/desc.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
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
In arch/x86/events/core.c (ffffffff810050cf)
Location: arch/x86/include/asm/desc.h:283
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/tls.c (ffffffff8103cc37)
Location: arch/x86/include/asm/desc.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff8103d2f0)
Location: arch/x86/include/asm/desc.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
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
In arch/x86/events/core.c (ffffffff81004f39)
Location: arch/x86/include/asm/desc.h:390
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/tls.c (ffffffff8103ac77)
Location: arch/x86/include/asm/desc.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff8103b340)
Location: arch/x86/include/asm/desc.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
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
In arch/x86/events/core.c (ffffffff810051e9)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/tls.c (ffffffff8103d6a7)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff8103dd69)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81983598)
Location: arch/x86/include/asm/desc.h:366
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
In arch/x86/events/core.c (ffffffff8100597d)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/tls.c (ffffffff8103ec17)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff8103f309)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff819dfb48)
Location: arch/x86/include/asm/desc.h:366
Inline: True
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
In arch/x86/events/core.c (ffffffff8100587b)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff8102d376)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff81040207)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff81040909)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1aa08)
Location: arch/x86/include/asm/desc.h:366
Inline: True
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
In arch/x86/events/core.c (ffffffff8100596b)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff8102f096)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff810428a7)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff81042fb9)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a8a72e)
Location: arch/x86/include/asm/desc.h:366
Inline: True
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
In arch/x86/events/core.c (ffffffff81005a3b)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff8102f9f6)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff81043017)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff81043719)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ac19ee)
Location: arch/x86/include/asm/desc.h:366
Inline: True
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
In arch/x86/events/core.c (ffffffff8100698d)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff810321cb)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff8104688e)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
```
In arch/x86/kernel/step.c (ffffffff81046f99)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff815fdf2a)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
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
In arch/x86/events/core.c (ffffffff810058bd)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff810330c4)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff810464fa)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/kernel/step.c (ffffffff810467e9)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81622e1a)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
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
In arch/x86/events/core.c (ffffffff8100576d)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff81034b54)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff81047f18)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/kernel/step.c (ffffffff81048209)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff816065aa)
Location: arch/x86/include/asm/desc.h:361
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
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
In arch/x86/events/core.c (ffffffff81005dcd)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff81039e62)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff8104e828)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/kernel/step.c (ffffffff8104eb19)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81674fea)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
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
In arch/x86/events/core.c (ffffffff81005150)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff81040e1e)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff810599d6)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/kernel/step.c (ffffffff81059d15)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff8178fa30)
Location: arch/x86/include/asm/desc.h:382
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
In arch/x86/events/core.c (ffffffff81005c60)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a4ee)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff81067376)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/kernel/step.c (ffffffff810676d5)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204d5a0)
Location: arch/x86/include/asm/desc.h:382
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
In arch/x86/events/core.c (ffffffff81005410)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff8104ad2e)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff810684ca)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff81068f75)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff820cbdf5)
Location: arch/x86/include/asm/desc.h:382
Inline: True
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
In arch/x86/events/core.c (ffffffff8100ab10)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff81051f9e)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff8106f94a)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff810703e5)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a6625)
Location: arch/x86/include/asm/desc.h:382
Inline: True
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
In arch/x86/events/core.c (ffffffff81005a3b)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fb56)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff81043197)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff81043899)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a6083e)
Location: arch/x86/include/asm/desc.h:366
Inline: True
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
In arch/x86/events/core.c (ffffffff8100411b)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff8101f576)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff810327b7)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff81032eb9)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1d8ef)
Location: arch/x86/include/asm/desc.h:366
Inline: True
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
In arch/x86/events/core.c (ffffffff810059fb)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff8102f9b6)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff81042fd7)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff810436d9)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81accc2e)
Location: arch/x86/include/asm/desc.h:366
Inline: True
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
In arch/x86/events/core.c (ffffffff81005b5b)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/events/core.c:get_segment_base
```
```
In arch/x86/kernel/process_64.c (ffffffff81030806)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsgsbase_read_task
```
```
In arch/x86/kernel/tls.c (ffffffff81044227)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/kernel/step.c (ffffffff81044ad9)
Location: arch/x86/include/asm/desc.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:convert_ip_to_linear
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ad913e)
Location: arch/x86/include/asm/desc.h:366
Inline: True
```
</details>
</li>
</ul>

## Differences
