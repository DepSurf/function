# Function: <code>utsname</code>

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
In kernel/sys.c (ffffffff810937c0)
Location: include/linux/utsname.h:72
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SyS_setdomainname
```
```
In fs/coredump.c (ffffffff8126f966)
Location: include/linux/utsname.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/version.c (ffffffff812834cd)
Location: include/linux/utsname.h:72
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff81513e1a)
Location: include/linux/utsname.h:72
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff81098692)
Location: include/linux/utsname.h:72
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_newuname
```
```
In fs/coredump.c (ffffffff8129b026)
Location: include/linux/utsname.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/version.c (ffffffff812b052d)
Location: include/linux/utsname.h:72
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff81566162)
Location: include/linux/utsname.h:72
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff8109d642)
Location: include/linux/utsname.h:73
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_newuname
```
```
In fs/coredump.c (ffffffff812afc09)
Location: include/linux/utsname.h:73
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/version.c (ffffffff812c5f1d)
Location: include/linux/utsname.h:73
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff815928c2)
Location: include/linux/utsname.h:73
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff8109a4d0)
Location: include/linux/utsname.h:73
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_newuname
```
```
In fs/coredump.c (ffffffff812bcf16)
Location: include/linux/utsname.h:73
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/version.c (ffffffff812d311d)
Location: include/linux/utsname.h:73
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff815a6b66)
Location: include/linux/utsname.h:73
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810a11b0)
Location: include/linux/utsname.h:74
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_newuname
```
```
In fs/coredump.c (ffffffff812e07f3)
Location: include/linux/utsname.h:74
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/version.c (ffffffff812f796d)
Location: include/linux/utsname.h:74
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff8160d466)
Location: include/linux/utsname.h:74
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810a3e05)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff8130caf6)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/version.c (ffffffff81324cd5)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff816464e2)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810acbd5)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff81322509)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/version.c (ffffffff8133be75)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff81665132)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810b22bb)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff8134978d)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffff813640a5)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff828f9e54)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810b898b)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff81361a2d)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffff8137c335)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff82902d57)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810c032b)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff813a7974)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/proc/version.c (ffffffff813c5c45)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff82d19b11)
Location: include/linux/utsname.h:80
Inline: True
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
In kernel/sys.c (ffffffff810bb54b)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff813b8824)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/proc/version.c (ffffffff813d7be5)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff83007815)
Location: include/linux/utsname.h:79
Inline: True
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
In kernel/sys.c (ffffffff810bce9b)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff813bf864)
Location: include/linux/utsname.h:79
Inline: True
```
```
In fs/proc/version.c (ffffffff813dea95)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff83212371)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
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
In kernel/sys.c (ffffffff810cf87b)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff8140f694)
Location: include/linux/utsname.h:79
Inline: True
```
```
In fs/proc/version.c (ffffffff81430405)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff832fb585)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
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
In kernel/sys.c (ffffffff810e8a98)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff814852f6)
Location: include/linux/utsname.h:79
Inline: True
```
```
In fs/proc/version.c (ffffffff814aa0d5)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff834b4072)
Location: include/linux/utsname.h:79
Inline: True
Inline callers:
  - drivers/char/random.c:random_init
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
In kernel/sys.c (ffffffff81109e53)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff81518954)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffff8153fca5)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
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
In kernel/sys.c (ffffffff811161e3)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__do_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff815501d4)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffff81578025)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
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
In kernel/sys.c (ffffffff8111fbd3)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__do_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff81586063)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffff815b0755)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
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
In kernel/sys.c (ffff800010115534)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_setdomainname
  - kernel/sys.c:__arm64_sys_gethostname
  - kernel/sys.c:__arm64_sys_sethostname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffff800010428170)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffff800010448b28)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffff800011495dac)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (c036d690)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_gethostname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (c05f0d34)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/proc/version.c (c060dc94)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (c1596118)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (c00000000015cd24)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_gethostname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__se_sys_olduname
  - kernel/sys.c:__se_sys_olduname
  - kernel/sys.c:__se_sys_olduname
  - kernel/sys.c:__se_sys_olduname
  - kernel/sys.c:__se_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (c0000000005382b8)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (c00000000055f27c)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (c0000000013a83e4)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffe0000d4196)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffe0002c6442)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffe0002de63c)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffe00002f9a0)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810b2cfb)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff8135a00d)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffff81374915)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff828ea53e)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810a162b)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff8134acbd)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffff813653e5)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff828e19cb)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810b225b)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff81357add)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffff813723e5)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff828fe07a)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
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
In kernel/sys.c (ffffffff810ba85b)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
```
```
In fs/coredump.c (ffffffff8136b1bd)
Location: include/linux/utsname.h:80
Inline: True
```
```
In fs/proc/version.c (ffffffff81385dc5)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
  - fs/proc/version.c:version_proc_show
```
```
In drivers/char/random.c (ffffffff82903db9)
Location: include/linux/utsname.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
</details>
</li>
</ul>

## Differences
