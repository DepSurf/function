# Function: <code>vc_finish_insn</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff82fd15d4)
Location: arch/x86/kernel/sev-es-shared.c:91
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
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
In arch/x86/kernel/sev.c (ffffffff831dc287)
Location: arch/x86/kernel/sev-shared.c:92
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
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
In arch/x86/kernel/sev.c (ffffffff832bf33d)
Location: arch/x86/kernel/sev-shared.c:92
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
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
In arch/x86/kernel/sev.c (ffffffff8347178b)
Location: arch/x86/kernel/sev-shared.c:189
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
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
In arch/x86/kernel/sev.c (ffffffff83e9896e)
Location: arch/x86/kernel/sev-shared.c:189
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
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
In arch/x86/kernel/sev.c (ffffffff836bc44a)
Location: arch/x86/kernel/sev-shared.c:192
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
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
In arch/x86/kernel/sev.c (ffffffff838eceba)
Location: arch/x86/kernel/sev-shared.c:192
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
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
