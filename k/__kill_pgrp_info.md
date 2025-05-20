# Function: <code>__kill_pgrp_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f7a0)
Location: kernel/signal.c:1273
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:SYSC_kill
```
**Symbols:**

```
ffffffff8108f7a0-ffffffff8108f81f: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092820)
Location: kernel/signal.c:1273
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pgrp
```
**Symbols:**

```
ffffffff81092820-ffffffff8109289d: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810977b0)
Location: kernel/signal.c:1279
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pgrp
```
**Symbols:**

```
ffffffff810977b0-ffffffff8109782d: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094ad0)
Location: kernel/signal.c:1297
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pgrp
```
**Symbols:**

```
ffffffff81094ad0-ffffffff81094b54: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b970)
Location: kernel/signal.c:1298
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pgrp
```
**Symbols:**

```
ffffffff8109b970-ffffffff8109b9f4: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f9d0)
Location: kernel/signal.c:1296
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:kill_pgrp
```
**Symbols:**

```
ffffffff8109f9d0-ffffffff8109fa53: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7c80)
Location: kernel/signal.c:1380
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810a7c80-ffffffff810a7d08: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad7f0)
Location: kernel/signal.c:1418
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810ad7f0-ffffffff810ad878: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3e10)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810b3e10-ffffffff810b3e98: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bcf60)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810bcf60-ffffffff810bd020: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8280)
Location: kernel/signal.c:1424
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810b8280-ffffffff810b834d: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9800)
Location: kernel/signal.c:1426
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810b9800-ffffffff810b98cc: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cbe10)
Location: kernel/signal.c:1452
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810cbe10-ffffffff810cbedc: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2ee0)
Location: kernel/signal.c:1453
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810e2ee0-ffffffff810e2fb8: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811033d0)
Location: kernel/signal.c:1454
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff811033d0-ffffffff811034a8: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110f610)
Location: kernel/signal.c:1460
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff8110f610-ffffffff8110f6ec: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81118f90)
Location: kernel/signal.c:1461
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff81118f90-ffffffff81119051: __kill_pgrp_info (STB_GLOBAL)
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
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010fe60)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:kill_pgrp
```
**Symbols:**

```
ffff80001010fe60-ffff80001010fef0: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0367c20)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:kill_pgrp
```
**Symbols:**

```
c0367c20-c0367cb0: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000157560)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:kill_pgrp
```
**Symbols:**

```
c000000000157560-c00000000015763c: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d018a)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:kill_pgrp
```
**Symbols:**

```
ffffffe0000d018a-ffffffe0000d0204: __kill_pgrp_info (STB_GLOBAL)
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
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae180)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810ae180-ffffffff810ae208: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cad0)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff8109cad0-ffffffff8109cb58: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad6e0)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810ad6e0-ffffffff810ad768: __kill_pgrp_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __kill_pgrp_info(int sig, struct kernel_siginfo *info, struct pid *pgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b58f0)
Location: kernel/signal.c:1423
Inline: False
Direct callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
**Symbols:**

```
ffffffff810b58f0-ffffffff810b5978: __kill_pgrp_info (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct siginfo *info</code> ➡️ <code>struct kernel_siginfo *info</code>
</li>
</ul>
</details>
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
