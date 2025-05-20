# Function: <code>kernel_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a2a30)
Location: kernel/reboot.c:214
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/hibernate.c:power_down
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff810a2a30-ffffffff810a2a83: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a6140)
Location: kernel/reboot.c:214
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/hibernate.c:power_down
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff810a6140-ffffffff810a6193: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810abda0)
Location: kernel/reboot.c:214
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/hibernate.c:power_down
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff810abda0-ffffffff810abdf3: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a8970)
Location: kernel/reboot.c:214
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/hibernate.c:hibernate
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff810a8970-ffffffff810a89c3: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810af1e0)
Location: kernel/reboot.c:241
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/power/hibernate.c:hibernate
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff810af1e0-ffffffff810af233: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:241
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff810b6435-ffffffff810b6467: kernel_restart.cold.2 (STB_LOCAL)
ffffffff810b6020-ffffffff810b604a: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff810bf6d4)
Location: kernel/reboot.c:242
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810bf6c5-ffffffff810bf6f7: kernel_restart.cold.3 (STB_LOCAL)
ffffffff810bf2b0-ffffffff810bf2da: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff810c57f7)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810c57e8-ffffffff810c581b: kernel_restart.cold (STB_LOCAL)
ffffffff810c53d0-ffffffff810c53fb: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff810ce8e4)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810ce8d5-ffffffff810ce908: kernel_restart.cold (STB_LOCAL)
ffffffff810ce4d0-ffffffff810ce4fb: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff810d8747)
Location: kernel/reboot.c:244
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:power_down
```
**Symbols:**

```
ffffffff810d86d5-ffffffff810d870a: kernel_restart.cold (STB_LOCAL)
ffffffff810d8250-ffffffff810d82a3: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff81bdc32a)
Location: kernel/reboot.c:244
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:power_down
```
**Symbols:**

```
ffffffff81bdc2b8-ffffffff81bdc2ed: kernel_restart.cold (STB_LOCAL)
ffffffff810d3510-ffffffff810d3563: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff81bce44d)
Location: kernel/reboot.c:244
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81bce3db-ffffffff81bce410: kernel_restart.cold (STB_LOCAL)
ffffffff810d5200-ffffffff810d5253: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff81ca584f)
Location: kernel/reboot.c:245
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81ca5792-ffffffff81ca57c7: kernel_restart.cold (STB_LOCAL)
ffffffff810e8410-ffffffff810e8463: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff81e5513f)
Location: kernel/reboot.c:254
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81e5506e-ffffffff81e550af: kernel_restart.cold (STB_LOCAL)
ffffffff81102d60-ffffffff81102db2: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81128230)
Location: kernel/reboot.c:265
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81128230-ffffffff811282ca: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff811356e0)
Location: kernel/reboot.c:265
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff811356e0-ffffffff8113577a: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81140740)
Location: kernel/reboot.c:275
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81140740-ffffffff811407da: kernel_restart (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffff80001012df58)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
```
**Symbols:**

```
ffff80001012df58-ffff80001012dfc0: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c037dd8c)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
c037dd8c-c037ddec: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c000000000176ea0)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
```
**Symbols:**

```
c000000000176ea0-c000000000176f30: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffe0000e1fbe)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
```
**Symbols:**

```
ffffffe0000e1fbe-ffffffe0000e2032: kernel_restart (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff810c8c64)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810c8c55-ffffffff810c8c88: kernel_restart.cold (STB_LOCAL)
ffffffff810c8850-ffffffff810c887b: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff810b7484)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810b7475-ffffffff810b74a8: kernel_restart.cold (STB_LOCAL)
ffffffff810b7070-ffffffff810b709b: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff810c8194)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810c8185-ffffffff810c81b8: kernel_restart.cold (STB_LOCAL)
ffffffff810c7d80-ffffffff810c7dab: kernel_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernel_restart(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (ffffffff810d0684)
Location: kernel/reboot.c:244
Inline: True
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810d0675-ffffffff810d06a8: kernel_restart.cold (STB_LOCAL)
ffffffff810d0270-ffffffff810d029b: kernel_restart (STB_GLOBAL)
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
