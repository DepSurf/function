# Function: <code>iterate_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81229ba0)
Location: fs/file.c:960
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:__do_SAK
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid
```
**Symbols:**

```
ffffffff81229ba0-ffffffff81229c1e: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252300)
Location: fs/file.c:966
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:__do_SAK
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid
```
**Symbols:**

```
ffffffff81252300-ffffffff81252380: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81265570)
Location: fs/file.c:966
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:__do_SAK
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81265570-ffffffff812655f0: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273340)
Location: fs/file.c:952
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81273340-ffffffff812733c4: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81295c70)
Location: fs/file.c:955
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81295c70-ffffffff81295cf6: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bbce0)
Location: fs/file.c:961
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff812bbce0-ffffffff812bbd62: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d0e10)
Location: fs/file.c:991
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff812d0e10-ffffffff812d0e92: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ede40)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff812ede40-ffffffff812edec7: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ff900)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffff812ff900-ffffffff812ff987: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81338a10)
Location: fs/file.c:1022
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffff81338a10-ffffffff81338a97: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344490)
Location: fs/file.c:1210
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffff81344490-ffffffff81344517: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134a830)
Location: fs/file.c:1221
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8134a830-ffffffff8134a8b3: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813985e0)
Location: fs/file.c:1287
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffff813985e0-ffffffff81398663: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141abd0)
Location: fs/file.c:1289
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:__do_SAK
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8141abd0-ffffffff8141ac6b: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a6930)
Location: fs/file.c:1299
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:__do_SAK
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff814a6930-ffffffff814a69cb: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814db8f0)
Location: fs/file.c:1314
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:__do_SAK
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff814db8f0-ffffffff814db998: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150e020)
Location: fs/file.c:1442
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:__do_SAK
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffff8150e020-ffffffff8150e0c8: iterate_fd (STB_GLOBAL)
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
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b12c0)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffff8000103b12c0-ffff8000103b13a8: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (c05907f4)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
c05907f4-c0590890: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ad080)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
c0000000004ad080-c0000000004ad1b0: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe0002753c4)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffe0002753c4-ffffffe000275484: iterate_fd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f7ee0)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffff812f7ee0-ffffffff812f7f67: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e8b00)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffff812e8b00-ffffffff812e8b87: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f5cf0)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffff812f5cf0-ffffffff812f5d77: iterate_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int iterate_fd(struct files_struct *files, unsigned int n, int (*f)(const void *, struct file *, unsigned int), const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307430)
Location: fs/file.c:997
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:update_classid_task
```
**Symbols:**

```
ffffffff81307430-ffffffff813074be: iterate_fd (STB_GLOBAL)
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
