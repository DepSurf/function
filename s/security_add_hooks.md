# Function: <code>security_add_hooks</code>

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
In security/commoncap.c (ffffffff81f982a3)
Location: include/linux/lsm_hooks.h:1850
Inline: True
Inline callers:
  - security/commoncap.c:capability_add_hooks
```
```
In security/selinux/hooks.c (ffffffff81f986b7)
Location: include/linux/lsm_hooks.h:1850
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81f98b9a)
Location: include/linux/lsm_hooks.h:1850
Inline: True
```
```
In security/tomoyo/tomoyo.c (ffffffff81f9912b)
Location: include/linux/lsm_hooks.h:1850
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
```
In security/apparmor/lsm.c (ffffffff81f9976e)
Location: include/linux/lsm_hooks.h:1850
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff81f99904)
Location: include/linux/lsm_hooks.h:1850
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_add_hooks
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
In security/commoncap.c (ffffffff81fc2f43)
Location: include/linux/lsm_hooks.h:1857
Inline: True
Inline callers:
  - security/commoncap.c:capability_add_hooks
```
```
In security/selinux/hooks.c (ffffffff81fc3352)
Location: include/linux/lsm_hooks.h:1857
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81fc384b)
Location: include/linux/lsm_hooks.h:1857
Inline: True
```
```
In security/tomoyo/tomoyo.c (ffffffff81fc3dfa)
Location: include/linux/lsm_hooks.h:1857
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
```
In security/apparmor/lsm.c (ffffffff81fc44e3)
Location: include/linux/lsm_hooks.h:1857
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff81fc467e)
Location: include/linux/lsm_hooks.h:1857
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_add_hooks
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
In security/commoncap.c (ffffffff81fff98f)
Location: include/linux/lsm_hooks.h:1892
Inline: True
Inline callers:
  - security/commoncap.c:capability_add_hooks
```
```
In security/selinux/hooks.c (ffffffff81fffd9e)
Location: include/linux/lsm_hooks.h:1892
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8200025c)
Location: include/linux/lsm_hooks.h:1892
Inline: True
```
```
In security/tomoyo/tomoyo.c (ffffffff820007ee)
Location: include/linux/lsm_hooks.h:1892
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
```
In security/apparmor/lsm.c (ffffffff82000f0e)
Location: include/linux/lsm_hooks.h:1892
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff820010b5)
Location: include/linux/lsm_hooks.h:1892
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_add_hooks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff820e2f6a)
Location: security/security.c:280
Inline: False
Direct callers:
  - security/commoncap.c:capability_add_hooks
  - security/smack/smack_lsm.c:smack_init
  - security/yama/yama_lsm.c:yama_add_hooks
```
**Symbols:**

```
ffffffff820e2f6a-ffffffff820e304f: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff826ebc23)
Location: security/security.c:295
Inline: False
Direct callers:
  - security/commoncap.c:capability_add_hooks
  - security/smack/smack_lsm.c:smack_init
  - security/yama/yama_lsm.c:yama_add_hooks
```
**Symbols:**

```
ffffffff826ebc23-ffffffff826ebd08: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82715f56)
Location: security/security.c:167
Inline: False
Direct callers:
  - security/commoncap.c:capability_add_hooks
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_add_hooks
```
**Symbols:**

```
ffffffff82715f56-ffffffff8271605b: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828cda00)
Location: security/security.c:433
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff828cda00-ffffffff828cdb97: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828e7435)
Location: security/security.c:429
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
```
**Symbols:**

```
ffffffff828e7435-ffffffff828e75de: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828effa9)
Location: security/security.c:456
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
ffffffff828effa9-ffffffff828f00ca: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, struct lsm_id *lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82d051c2)
Location: security/security.c:519
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
ffffffff82d051c2-ffffffff82d052b5: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, struct lsm_id *lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82ff258f)
Location: security/security.c:521
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
  - security/bpf/hooks.c:bpf_lsm_init
```
**Symbols:**

```
ffffffff82ff258f-ffffffff82ff2682: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, struct lsm_id *lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff831fcf6b)
Location: security/security.c:524
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
  - security/bpf/hooks.c:bpf_lsm_init
  - security/landlock/cred.c:landlock_add_cred_hooks
  - security/landlock/ptrace.c:landlock_add_ptrace_hooks
  - security/landlock/fs.c:landlock_add_fs_hooks
```
**Symbols:**

```
ffffffff831fcf6b-ffffffff831fd05e: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, struct lsm_id *lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff832e412d)
Location: security/security.c:524
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
  - security/bpf/hooks.c:bpf_lsm_init
  - security/landlock/cred.c:landlock_add_cred_hooks
  - security/landlock/ptrace.c:landlock_add_ptrace_hooks
  - security/landlock/fs.c:landlock_add_fs_hooks
```
**Symbols:**

```
ffffffff832e412d-ffffffff832e4263: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, struct lsm_id *lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8349ac79)
Location: security/security.c:548
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
  - security/bpf/hooks.c:bpf_lsm_init
  - security/landlock/cred.c:landlock_add_cred_hooks
  - security/landlock/ptrace.c:landlock_add_ptrace_hooks
  - security/landlock/fs.c:landlock_add_fs_hooks
```
**Symbols:**

```
ffffffff8349ac79-ffffffff8349add5: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, struct lsm_id *lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff83ed1950)
Location: security/security.c:587
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
  - security/bpf/hooks.c:bpf_lsm_init
  - security/landlock/cred.c:landlock_add_cred_hooks
  - security/landlock/ptrace.c:landlock_add_ptrace_hooks
  - security/landlock/fs.c:landlock_add_fs_hooks
```
**Symbols:**

```
ffffffff83ed1950-ffffffff83ed1b36: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, struct lsm_id *lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff836f6a30)
Location: security/security.c:595
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
  - security/bpf/hooks.c:bpf_lsm_init
  - security/landlock/cred.c:landlock_add_cred_hooks
  - security/landlock/ptrace.c:landlock_add_ptrace_hooks
  - security/landlock/fs.c:landlock_add_fs_hooks
```
**Symbols:**

```
ffffffff836f6a30-ffffffff836f6c16: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, const struct lsm_id *lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff83929e00)
Location: security/security.c:609
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
  - security/bpf/hooks.c:bpf_lsm_init
  - security/landlock/cred.c:landlock_add_cred_hooks
  - security/landlock/ptrace.c:landlock_add_ptrace_hooks
  - security/landlock/fs.c:landlock_add_fs_hooks
  - security/landlock/net.c:landlock_add_net_hooks
```
**Symbols:**

```
ffffffff83929e00-ffffffff83929f5c: security_add_hooks (STB_GLOBAL)
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
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800011469e78)
Location: security/security.c:456
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
ffff800011469e78-ffff800011469fd0: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c1542a4c)
Location: security/security.c:456
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
c1542a4c-c1542ba4: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000001398260)
Location: security/security.c:456
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
c000000001398260-c000000001398434: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe000024fdc)
Location: security/security.c:456
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
ffffffe000024fdc-ffffffe000025108: security_add_hooks (STB_GLOBAL)
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
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d8e5d)
Location: security/security.c:456
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
ffffffff828d8e5d-ffffffff828d8f7e: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d1579)
Location: security/security.c:456
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
ffffffff828d1579-ffffffff828d169a: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828ebbdd)
Location: security/security.c:456
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
ffffffff828ebbdd-ffffffff828ebcfe: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_add_hooks(struct security_hook_list *hooks, int count, char *lsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828f0ff3)
Location: security/security.c:456
Inline: False
Direct callers:
  - security/commoncap.c:capability_init
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - security/safesetid/lsm.c:safesetid_security_init
  - security/lockdown/lockdown.c:lockdown_lsm_init
```
**Symbols:**

```
ffffffff828f0ff3-ffffffff828f1114: security_add_hooks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsm_id *lsmid</code>
</li>
<li>
<b>Param removed. </b>
<code>char *lsm</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct lsm_id *lsmid</code> ➡️ <code>const struct lsm_id *lsmid</code>
</li>
</ul>
</details>
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
