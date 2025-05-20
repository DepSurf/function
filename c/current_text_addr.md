# Function: <code>current_text_addr</code>

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
In kernel/kexec_core.c (ffffffff8110da35)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In net/ipv4/tcp_input.c (ffffffff8176c216)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81775c66)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
```
```
In net/ipv4/tcp_timer.c (ffffffff8177a332)
Location: arch/x86/include/asm/processor.h:46
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d391)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: arch/x86/include/asm/processor.h:46
Inline: True
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
In kernel/kexec_core.c (ffffffff8111545b)
Location: arch/x86/include/asm/processor.h:46
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817dd23d)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff817e50bc)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff817e7355)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb43c)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: arch/x86/include/asm/processor.h:46
Inline: True
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
In kernel/kexec_core.c (ffffffff8111cb7b)
Location: arch/x86/include/asm/processor.h:46
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8180d38a)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81815547)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81817991)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181bdb0)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: arch/x86/include/asm/processor.h:46
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
In kernel/kexec_core.c (ffffffff8111d6ee)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_setup_regs
```
```
In net/ipv4/tcp_input.c (ffffffff8182da99)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff818358cc)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff818380ea)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c598)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: arch/x86/include/asm/processor.h:46
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81841c8f)
Location: arch/x86/include/asm/processor.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/kexec_core.c (ffffffff81128e3d)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_setup_regs
```
```
In net/ipv4/tcp_input.c (ffffffff818ac938)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff818b4e1e)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7821)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbcc3)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: arch/x86/include/asm/processor.h:49
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff818c14cf)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In kernel/kexec_core.c (ffffffff81136a3a)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
```
In net/ipv4/tcp_input.c (ffffffff81902127)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8190a4d2)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d1be)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911723)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: arch/x86/include/asm/processor.h:49
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff8191705f)
Location: arch/x86/include/asm/processor.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
