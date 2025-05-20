# Function: <code>call_usermodehelper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int call_usermodehelper(char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81096b30)
Location: kernel/kmod.c:616
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup.c:cgroup_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff81096b30-ffffffff81096bd1: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int call_usermodehelper(char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81099ef0)
Location: kernel/kmod.c:616
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup.c:cgroup_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff81099ef0-ffffffff81099f91: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int call_usermodehelper(char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109eea0)
Location: kernel/kmod.c:616
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup.c:cgroup_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff8109eea0-ffffffff8109ef41: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109c1a0)
Location: kernel/kmod.c:647
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff8109c1a0-ffffffff8109c241: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a2ea0)
Location: kernel/umh.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810a2ea0-ffffffff810a2f41: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a9500)
Location: kernel/umh.c:596
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810a9500-ffffffff810a95a1: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b23f0)
Location: kernel/umh.c:617
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810b23f0-ffffffff810b2491: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b7f90)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810b7f90-ffffffff810b803a: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810be490)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810be490-ffffffff810be53a: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c5670)
Location: kernel/umh.c:629
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810c5670-ffffffff810c571a: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c09a0)
Location: kernel/umh.c:472
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810c09a0-ffffffff810c0a4a: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c23a0)
Location: kernel/umh.c:474
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810c23a0-ffffffff810c244a: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810d4ee0)
Location: kernel/umh.c:474
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810d4ee0-ffffffff810d4f8a: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810edea0)
Location: kernel/umh.c:474
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810edea0-ffffffff810edf4f: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8110f370)
Location: kernel/umh.c:486
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff8110f370-ffffffff8110f41f: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff8111b810)
Location: kernel/umh.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff8111b810-ffffffff8111b8bf: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff81125300)
Location: kernel/umh.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff81125300-ffffffff811253de: call_usermodehelper (STB_GLOBAL)
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
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffff80001011ae38)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffff80001011ae38-ffff80001011aedc: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c036f3b8)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
c036f3b8-c036f450: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c000000000162f90)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
c000000000162f90-c000000000163094: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffe0000d53e6)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffe0000d53e6-ffffffe0000d54a0: call_usermodehelper (STB_GLOBAL)
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
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b8800)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810b8800-ffffffff810b88aa: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a7140)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810a7140-ffffffff810a71ea: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b7d60)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810b7d60-ffffffff810b7e0a: call_usermodehelper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_usermodehelper(const char *path, char **argv, char **envp, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c0420)
Location: kernel/umh.c:618
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger
  - kernel/reboot.c:run_cmd
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - security/tomoyo/load_policy.c:tomoyo_load_policy
```
**Symbols:**

```
ffffffff810c0420-ffffffff810c04ca: call_usermodehelper (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *path</code> ➡️ <code>const char *path</code>
</li>
</ul>
</details>
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
