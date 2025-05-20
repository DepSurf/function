# Function: <code>task_set_no_new_privs</code>

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
In kernel/fork.c (ffffffff8107f215)
Location: include/linux/sched.h:2163
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff81095e46)
Location: include/linux/sched.h:2163
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/seccomp.c (ffffffff8113bbf0)
Location: include/linux/sched.h:2163
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
In kernel/fork.c (ffffffff810813cb)
Location: include/linux/sched.h:2306
Inline: True
```
```
In kernel/sys.c (ffffffff810991ee)
Location: include/linux/sched.h:2306
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/seccomp.c (ffffffff811443aa)
Location: include/linux/sched.h:2306
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
In kernel/fork.c (ffffffff81085e30)
Location: include/linux/sched.h:2398
Inline: True
```
```
In kernel/sys.c (ffffffff8109e19e)
Location: include/linux/sched.h:2398
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/seccomp.c (ffffffff8114e25e)
Location: include/linux/sched.h:2398
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
In kernel/fork.c (ffffffff81082819)
Location: include/linux/sched.h:1341
Inline: True
```
```
In kernel/sys.c (ffffffff8109b78b)
Location: include/linux/sched.h:1341
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/seccomp.c (ffffffff8115090e)
Location: include/linux/sched.h:1341
Inline: True
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
In kernel/fork.c (ffffffff81089659)
Location: include/linux/sched.h:1371
Inline: True
```
```
In kernel/sys.c (ffffffff810a247c)
Location: include/linux/sched.h:1371
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/seccomp.c (ffffffff8115cb48)
Location: include/linux/sched.h:1371
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
In kernel/fork.c (ffffffff8108cfe2)
Location: include/linux/sched.h:1464
Inline: True
```
```
In kernel/sys.c (ffffffff810a8874)
Location: include/linux/sched.h:1464
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/seccomp.c (ffffffff8116bef7)
Location: include/linux/sched.h:1464
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
In kernel/fork.c (ffffffff81094b16)
Location: include/linux/sched.h:1470
Inline: True
```
```
In kernel/sys.c (ffffffff810b1559)
Location: include/linux/sched.h:1470
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/seccomp.c (ffffffff81179907)
Location: include/linux/sched.h:1470
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
In kernel/fork.c (ffffffff810992c6)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b724e)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/seccomp.c (ffffffff811860a1)
Location: include/linux/sched.h:1543
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/fork.c (ffffffff8109f8be)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bd6c1)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/seccomp.c (ffffffff811923ae)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/fork.c (ffffffff810a4627)
Location: include/linux/sched.h:1578
Inline: True
Inline callers:
  - kernel/fork.c:copy_seccomp
```
```
In kernel/sys.c (ffffffff810c4ebd)
Location: include/linux/sched.h:1578
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/seccomp.c (ffffffff811a6f59)
Location: include/linux/sched.h:1578
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/fork.c (ffffffff8109fad7)
Location: include/linux/sched.h:1636
Inline: True
Inline callers:
  - kernel/fork.c:copy_seccomp
```
```
In kernel/sys.c (ffffffff810c02ed)
Location: include/linux/sched.h:1636
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/seccomp.c (ffffffff811a44ff)
Location: include/linux/sched.h:1636
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/fork.c (ffffffff810a3962)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810c1d06)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/seccomp.c (ffffffff811a4ff6)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/fork.c (ffffffff810b522c)
Location: include/linux/sched.h:1755
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810d4610)
Location: include/linux/sched.h:1755
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/seccomp.c (ffffffff811ce746)
Location: include/linux/sched.h:1755
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/fork.c (ffffffff810cae23)
Location: include/linux/sched.h:1780
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810ed55b)
Location: include/linux/sched.h:1780
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/seccomp.c (ffffffff81202856)
Location: include/linux/sched.h:1780
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/fork.c (ffffffff810e8434)
Location: include/linux/sched.h:1807
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff8110e97b)
Location: include/linux/sched.h:1807
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/seccomp.c (ffffffff8124a6a6)
Location: include/linux/sched.h:1807
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/fork.c (ffffffff810f4093)
Location: include/linux/sched.h:1816
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff8111a835)
Location: include/linux/sched.h:1816
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/seccomp.c (ffffffff812619a6)
Location: include/linux/sched.h:1816
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/fork.c (ffffffff810fd455)
Location: include/linux/sched.h:1710
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff811242a5)
Location: include/linux/sched.h:1710
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/seccomp.c (ffffffff8127bba6)
Location: include/linux/sched.h:1710
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f48a0)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffff80001011a0c8)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_prctl
```
```
In kernel/seccomp.c (ffff800010209d68)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0352d74)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (c036e624)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In kernel/seccomp.c (c0448820)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013a2b8)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (c000000000161a58)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In kernel/seccomp.c (c000000000286f44)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c072a)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffe0000d4b66)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In kernel/seccomp.c (ffffffe00016b98c)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
```
</details>
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
In kernel/fork.c (ffffffff810991de)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b7a31)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/seccomp.c (ffffffff8118a9ce)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/fork.c (ffffffff81087c2e)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810a6371)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/seccomp.c (ffffffff8117daf8)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/fork.c (ffffffff8109918e)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b6f91)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/seccomp.c (ffffffff8118879e)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/fork.c (ffffffff810a0dc7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bf311)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/seccomp.c (ffffffff8119610c)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
</details>
</li>
</ul>

## Differences
