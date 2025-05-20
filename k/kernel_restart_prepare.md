# Function: <code>kernel_restart_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a2960)
Location: kernel/reboot.c:68
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810a2960-ffffffff810a2998: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a6070)
Location: kernel/reboot.c:68
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810a6070-ffffffff810a60a8: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810abcd0)
Location: kernel/reboot.c:68
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810abcd0-ffffffff810abd08: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a88a0)
Location: kernel/reboot.c:68
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810a88a0-ffffffff810a88d8: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810af110)
Location: kernel/reboot.c:68
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810af110-ffffffff810af148: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b5f50)
Location: kernel/reboot.c:68
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810b5f50-ffffffff810b5f88: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810bf1e0)
Location: kernel/reboot.c:69
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810bf1e0-ffffffff810bf218: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c52f0)
Location: kernel/reboot.c:71
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810c52f0-ffffffff810c5328: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810ce3f0)
Location: kernel/reboot.c:71
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810ce3f0-ffffffff810ce428: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d8747)
Location: kernel/reboot.c:71
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810d8160-ffffffff810d8198: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81bdc32a)
Location: kernel/reboot.c:71
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810d3420-ffffffff810d3458: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81bce44d)
Location: kernel/reboot.c:71
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810d5110-ffffffff810d5148: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81ca584f)
Location: kernel/reboot.c:72
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810e8300-ffffffff810e8338: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81e5513f)
Location: kernel/reboot.c:81
Inline: True
Inline callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81102c30-ffffffff81102c74: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81128235)
Location: kernel/reboot.c:81
Inline: True
Inline callers:
  - kernel/reboot.c:kernel_restart
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff811280d0-ffffffff81128114: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff811356e5)
Location: kernel/reboot.c:81
Inline: True
Inline callers:
  - kernel/reboot.c:kernel_restart
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81135580-ffffffff811355c4: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81140745)
Location: kernel/reboot.c:91
Inline: True
Inline callers:
  - kernel/reboot.c:kernel_restart
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff811405e0-ffffffff81140624: kernel_restart_prepare (STB_GLOBAL)
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
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffff80001012de30)
Location: kernel/reboot.c:71
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffff80001012de30-ffff80001012de80: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c037dc70)
Location: kernel/reboot.c:71
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
c037dc70-c037dcb8: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c000000000176d10)
Location: kernel/reboot.c:71
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
c000000000176d10-c000000000176d78: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffe0000e1eaa)
Location: kernel/reboot.c:71
Inline: False
```
**Symbols:**

```
ffffffe0000e1eaa-ffffffe0000e1efa: kernel_restart_prepare (STB_GLOBAL)
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
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c8770)
Location: kernel/reboot.c:71
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810c8770-ffffffff810c87a8: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b6f90)
Location: kernel/reboot.c:71
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810b6f90-ffffffff810b6fc8: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c7ca0)
Location: kernel/reboot.c:71
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810c7ca0-ffffffff810c7cd8: kernel_restart_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kernel_restart_prepare(char *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d0190)
Location: kernel/reboot.c:71
Inline: False
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810d0190-ffffffff810d01c8: kernel_restart_prepare (STB_GLOBAL)
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
