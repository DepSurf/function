# Function: <code>machine_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff810504a0)
Location: arch/x86/kernel/reboot.c:743
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff810504a0-ffffffff810504b1: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81050620)
Location: arch/x86/kernel/reboot.c:773
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81050620-ffffffff81050631: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81052e90)
Location: arch/x86/kernel/reboot.c:773
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81052e90-ffffffff81052ea1: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff810529a0)
Location: arch/x86/kernel/reboot.c:791
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff810529a0-ffffffff810529b1: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81056690)
Location: arch/x86/kernel/reboot.c:795
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81056690-ffffffff810566a7: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81059490)
Location: arch/x86/kernel/reboot.c:796
Inline: False
Direct callers:
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81059490-ffffffff810594a7: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8105f140)
Location: arch/x86/kernel/reboot.c:796
Inline: False
Direct callers:
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff8105f140-ffffffff8105f157: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81062550)
Location: arch/x86/kernel/reboot.c:817
Inline: False
Direct callers:
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81062550-ffffffff81062567: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81062dc0)
Location: arch/x86/kernel/reboot.c:817
Inline: False
Direct callers:
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81062dc0-ffffffff81062dd7: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81068e40)
Location: arch/x86/kernel/reboot.c:825
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81068e40-ffffffff81068e57: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8106aa90)
Location: arch/x86/kernel/reboot.c:824
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff8106aa90-ffffffff8106aaa7: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8106b560)
Location: arch/x86/kernel/reboot.c:824
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff8106b560-ffffffff8106b577: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81076050)
Location: arch/x86/kernel/reboot.c:817
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81076050-ffffffff81076067: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81084d80)
Location: arch/x86/kernel/reboot.c:817
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81084d80-ffffffff81084d9f: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81097fd0)
Location: arch/x86/kernel/reboot.c:813
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81097fd0-ffffffff81097fef: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8109b070)
Location: arch/x86/kernel/reboot.c:813
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff8109b070-ffffffff8109b08f: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff810a2770)
Location: arch/x86/kernel/reboot.c:858
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff810a2770-ffffffff810a278f: machine_restart (STB_GLOBAL)
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
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff800010089070)
Location: arch/arm64/kernel/process.c:186
Inline: False
Direct callers:
  - kernel/reboot.c:emergency_restart
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffff800010089070-ffff8000100890ec: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/reboot.c (c030d374)
Location: arch/arm/kernel/reboot.c:136
Inline: False
Direct callers:
  - kernel/reboot.c:emergency_restart
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
c030d374-c030d400: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/setup-common.c (c0000000000300d0)
Location: arch/powerpc/kernel/setup-common.c:153
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec.c:machine_kexec
  - kernel/reboot.c:emergency_restart
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
c0000000000300d0-c000000000030174: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/reset.c (ffffffe0000b656e)
Location: arch/riscv/kernel/reset.c:19
Inline: False
Direct callers:
  - kernel/reboot.c:emergency_restart
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffe0000b656e-ffffffe0000b6590: machine_restart (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff810628b0)
Location: arch/x86/kernel/reboot.c:817
Inline: False
Direct callers:
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff810628b0-ffffffff810628c7: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81052c90)
Location: arch/x86/kernel/reboot.c:817
Inline: False
Direct callers:
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81052c90-ffffffff81052ca7: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81062d60)
Location: arch/x86/kernel/reboot.c:817
Inline: False
Direct callers:
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81062d60-ffffffff81062d77: machine_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void machine_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81064320)
Location: arch/x86/kernel/reboot.c:817
Inline: False
Direct callers:
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_do_poweroff
```
**Symbols:**

```
ffffffff81064320-ffffffff81064337: machine_restart (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
