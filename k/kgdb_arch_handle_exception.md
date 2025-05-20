# Function: <code>kgdb_arch_handle_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81061530)
Location: arch/x86/kernel/kgdb.c:460
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdbstub_state
```
**Symbols:**

```
ffffffff81061530-ffffffff810615f5: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81061350)
Location: arch/x86/kernel/kgdb.c:461
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff81061350-ffffffff81061415: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81064400)
Location: arch/x86/kernel/kgdb.c:461
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff81064400-ffffffff810644c5: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81063330)
Location: arch/x86/kernel/kgdb.c:461
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff81063330-ffffffff810633f5: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810674b0)
Location: arch/x86/kernel/kgdb.c:461
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff810674b0-ffffffff81067575: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8106a0b0)
Location: arch/x86/kernel/kgdb.c:461
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff8106a0b0-ffffffff8106a177: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8106fe40)
Location: arch/x86/kernel/kgdb.c:456
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff8106fe40-ffffffff8106ff07: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81073f40)
Location: arch/x86/kernel/kgdb.c:439
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff81073f40-ffffffff81074010: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81074f00)
Location: arch/x86/kernel/kgdb.c:439
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff81074f00-ffffffff81074fd0: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8107c110)
Location: arch/x86/kernel/kgdb.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff8107c110-ffffffff8107c1e0: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8107c000)
Location: arch/x86/kernel/kgdb.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff8107c000-ffffffff8107c0d0: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8107d1b0)
Location: arch/x86/kernel/kgdb.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff8107d1b0-ffffffff8107d280: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8108bad0)
Location: arch/x86/kernel/kgdb.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff8108bad0-ffffffff8108bba0: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8109c320)
Location: arch/x86/kernel/kgdb.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff8109c320-ffffffff8109c40d: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810b3000)
Location: arch/x86/kernel/kgdb.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff810b3000-ffffffff810b30ed: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810b6100)
Location: arch/x86/kernel/kgdb.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff810b6100-ffffffff810b61e7: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810bd540)
Location: arch/x86/kernel/kgdb.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff810bd540-ffffffff810bd627: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int exception_vector, int signo, int err_code, char *remcom_in_buffer, char *remcom_out_buffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/kgdb.c (ffff8000100a75d0)
Location: arch/arm64/kernel/kgdb.c:173
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffff8000100a75d0-ffff8000100a76d0: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int exception_vector, int signo, int err_code, char *remcom_in_buffer, char *remcom_out_buffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/kgdb.c (c03158d4)
Location: arch/arm/kernel/kgdb.c:110
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
c03158d4-c031599c: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kgdb_arch_handle_exception(int vector, int signo, int err_code, char *remcom_in_buffer, char *remcom_out_buffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/kgdb.c (c0000000000538c0)
Location: arch/powerpc/kernel/kgdb.c:380
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
c0000000000538c0-c0000000000539f8: kgdb_arch_handle_exception (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81073f00)
Location: arch/x86/kernel/kgdb.c:439
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff81073f00-ffffffff81073fd0: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81063f50)
Location: arch/x86/kernel/kgdb.c:439
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff81063f50-ffffffff81064020: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81073eb0)
Location: arch/x86/kernel/kgdb.c:439
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff81073eb0-ffffffff81073f80: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kgdb_arch_handle_exception(int e_vector, int signo, int err_code, char *remcomInBuffer, char *remcomOutBuffer, struct pt_regs *linux_regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81075f10)
Location: arch/x86/kernel/kgdb.c:439
Inline: True
Direct callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
**Symbols:**

```
ffffffff81075f10-ffffffff81075fe0: kgdb_arch_handle_exception (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int exception_vector</code>
</li>
<li>
<b>Param added. </b>
<code>char *remcom_in_buffer</code>
</li>
<li>
<b>Param added. </b>
<code>char *remcom_out_buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>int e_vector</code>
</li>
<li>
<b>Param removed. </b>
<code>char *remcomInBuffer</code>
</li>
<li>
<b>Param removed. </b>
<code>char *remcomOutBuffer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int exception_vector</code>
</li>
<li>
<b>Param added. </b>
<code>char *remcom_in_buffer</code>
</li>
<li>
<b>Param added. </b>
<code>char *remcom_out_buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>int e_vector</code>
</li>
<li>
<b>Param removed. </b>
<code>char *remcomInBuffer</code>
</li>
<li>
<b>Param removed. </b>
<code>char *remcomOutBuffer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int vector</code>
</li>
<li>
<b>Param added. </b>
<code>char *remcom_in_buffer</code>
</li>
<li>
<b>Param added. </b>
<code>char *remcom_out_buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>int e_vector</code>
</li>
<li>
<b>Param removed. </b>
<code>char *remcomInBuffer</code>
</li>
<li>
<b>Param removed. </b>
<code>char *remcomOutBuffer</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
