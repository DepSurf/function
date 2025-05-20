# Function: <code>kexec_unlock</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811fff60)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff81200317)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff81201ddb)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
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
In kernel/kexec_core.c (ffffffff812153c0)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff81215777)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff812171d5)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
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
In kernel/crash_core.c (ffffffff8122a2a2)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_handle_hotplug_event
  - kernel/crash_core.c:crash_check_update_elfcorehdr
```
```
In kernel/kexec_core.c (ffffffff8122d365)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff8122d724)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff8122f0dc)
Location: kernel/kexec_internal.h:26
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
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
