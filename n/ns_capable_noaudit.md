# Function: <code>ns_capable_noaudit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108d2e0)
Location: kernel/capability.c:411
Inline: False
```
**Symbols:**

```
ffffffff8108d2e0-ffffffff8108d2f2: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81092290)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffff81092290-ffffffff810922a2: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f440)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffff8108f440-ffffffff8108f452: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81096300)
Location: kernel/capability.c:413
Inline: False
```
**Symbols:**

```
ffffffff81096300-ffffffff81096312: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810997f0)
Location: kernel/capability.c:413
Inline: False
```
**Symbols:**

```
ffffffff810997f0-ffffffff81099802: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a1b60)
Location: kernel/capability.c:414
Inline: False
```
**Symbols:**

```
ffffffff810a1b60-ffffffff810a1b75: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6590)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffff810a6590-ffffffff810a65a5: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810acb70)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffff810acb70-ffffffff810acb85: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffff810b4b2d-ffffffff810b4b3b: ns_capable_noaudit.cold (STB_LOCAL)
ffffffff810b4920-ffffffff810b4971: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:412
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81bdba2e-ffffffff81bdba3c: ns_capable_noaudit.cold (STB_LOCAL)
ffffffff810afbc0-ffffffff810afc11: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:412
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/seccomp.c:seccomp_set_mode_filter
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81bcdac0-ffffffff81bcdace: ns_capable_noaudit.cold (STB_LOCAL)
ffffffff810b1070-ffffffff810b10c1: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:412
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/seccomp.c:seccomp_set_mode_filter
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81ca4589-ffffffff81ca4597: ns_capable_noaudit.cold (STB_LOCAL)
ffffffff810c3080-ffffffff810c30d1: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:413
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/seccomp.c:seccomp_set_mode_filter
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff81e53e2a-ffffffff81e53e38: ns_capable_noaudit.cold (STB_LOCAL)
ffffffff810da5d0-ffffffff810da628: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa630)
Location: kernel/capability.c:413
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/seccomp.c:seccomp_set_mode_filter
  - fs/xattr.c:simple_xattr_list
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
```
**Symbols:**

```
ffffffff810fa630-ffffffff810fa692: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff811065e0)
Location: kernel/capability.c:399
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/seccomp.c:seccomp_set_mode_filter
  - fs/xattr.c:simple_xattr_list
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff811065e0-ffffffff81106642: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8110ff30)
Location: kernel/capability.c:399
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/seccomp.c:seccomp_set_mode_filter
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:do_statmount
  - fs/xattr.c:simple_xattr_list
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff8110ff30-ffffffff8110ff92: ns_capable_noaudit (STB_GLOBAL)
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
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010105b28)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffff800010105b28-ffff800010105b60: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c0360f3c)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
c0360f3c-c0360f5c: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014d280)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
c00000000014d280-c00000000014d298: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb100)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffe0000cb100-ffffffe0000cb134: ns_capable_noaudit (STB_GLOBAL)
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
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6ee0)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffff810a6ee0-ffffffff810a6ef5: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810958c0)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffff810958c0-ffffffff810958d5: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6440)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffff810a6440-ffffffff810a6455: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ns_capable_noaudit(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ae4f0)
Location: kernel/capability.c:412
Inline: False
```
**Symbols:**

```
ffffffff810ae4f0-ffffffff810ae505: ns_capable_noaudit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
