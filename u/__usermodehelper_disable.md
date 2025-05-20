# Function: <code>__usermodehelper_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81096c30)
Location: kernel/kmod.c:457
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_power_off
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81096c30-ffffffff81096d5c: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81099ff0)
Location: kernel/kmod.c:457
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81099ff0-ffffffff8109a123: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109efa0)
Location: kernel/kmod.c:457
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff8109efa0-ffffffff8109f0cf: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109c7b0)
Location: kernel/kmod.c:474
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff8109c7b0-ffffffff8109c8e6: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a3040)
Location: kernel/umh.c:305
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810a3040-ffffffff810a3176: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a99d0)
Location: kernel/umh.c:312
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810a99d0-ffffffff810a9b06: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b2910)
Location: kernel/umh.c:316
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810b2910-ffffffff810b2a46: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b84a0)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810b84a0-ffffffff810b85d4: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810be9a0)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810be9a0-ffffffff810bead4: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c5c00)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810c5c00-ffffffff810c5d65: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c0e80)
Location: kernel/umh.c:294
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810c0e80-ffffffff810c0fe5: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c2880)
Location: kernel/umh.c:296
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810c2880-ffffffff810c29e5: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810d53c0)
Location: kernel/umh.c:296
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810d53c0-ffffffff810d5525: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810ee220)
Location: kernel/umh.c:296
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810ee220-ffffffff810ee38e: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8110f730)
Location: kernel/umh.c:297
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff8110f730-ffffffff8110f89e: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8111bbd0)
Location: kernel/umh.c:294
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff8111bbd0-ffffffff8111bd3e: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff811256f0)
Location: kernel/umh.c:294
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff811256f0-ffffffff8112585e: __usermodehelper_disable (STB_GLOBAL)
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
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffff80001011b398)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffff80001011b398-ffff80001011b4f4: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c036f8b8)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
c036f8b8-c036f9f8: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c000000000163120)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
c000000000163120-c0000000001632b4: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffe0000d59a8)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffe0000d59a8-ffffffe0000d5aa2: __usermodehelper_disable (STB_GLOBAL)
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
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b8d10)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810b8d10-ffffffff810b8e44: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a7650)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810a7650-ffffffff810a7784: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b8270)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810b8270-ffffffff810b83a4: __usermodehelper_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __usermodehelper_disable(enum umh_disable_depth depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c05d0)
Location: kernel/umh.c:317
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff810c05d0-ffffffff810c06ff: __usermodehelper_disable (STB_GLOBAL)
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
