# Function: <code>cap_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, int audit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8133a0c0)
Location: security/commoncap.c:71
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:selinux_inode_getsecurity
```
**Symbols:**

```
ffffffff8133a0c0-ffffffff8133a128: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, int audit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8136f7c0)
Location: security/commoncap.c:71
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:selinux_inode_getsecurity
```
**Symbols:**

```
ffffffff8136f7c0-ffffffff8136f823: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, int audit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81385fe0)
Location: security/commoncap.c:71
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:selinux_inode_getsecurity
```
**Symbols:**

```
ffffffff81385fe0-ffffffff81386043: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, int audit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8139aac0)
Location: security/commoncap.c:71
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff8139aac0-ffffffff8139ab23: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, int audit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813c0150)
Location: security/commoncap.c:71
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff813c0150-ffffffff813c01b8: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, int audit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813f10c0)
Location: security/commoncap.c:71
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff813f10c0-ffffffff813f1128: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8140c3c0)
Location: security/commoncap.c:70
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff8140c3c0-ffffffff8140c428: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81439530)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff81439530-ffffffff814395a1: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814533a0)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff814533a0-ffffffff81453411: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814a5e36)
Location: security/commoncap.c:65
Inline: True
Inline callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
Direct callers:
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff814a5c00-ffffffff814a5c74: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c3436)
Location: security/commoncap.c:65
Inline: True
Inline callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
Direct callers:
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff814c2f10-ffffffff814c2f84: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c98a6)
Location: security/commoncap.c:65
Inline: True
Inline callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
Direct callers:
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff814c9370-ffffffff814c93e4: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff815223c6)
Location: security/commoncap.c:65
Inline: True
Inline callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
Direct callers:
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff81521e60-ffffffff81521f0a: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff815b60e2)
Location: security/commoncap.c:66
Inline: True
Inline callers:
  - security/commoncap.c:cap_mmap_addr
  - security/commoncap.c:cap_mmap_addr
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
Direct callers:
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
  - security/apparmor/policy.c:aa_policy_admin_capable
```
**Symbols:**

```
ffffffff815b5ad0-ffffffff815b5b9e: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81661232)
Location: security/commoncap.c:67
Inline: True
Inline callers:
  - security/commoncap.c:cap_mmap_addr
  - security/commoncap.c:cap_mmap_addr
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
Direct callers:
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
  - security/apparmor/policy.c:aa_policy_admin_capable
```
**Symbols:**

```
ffffffff81660bd0-ffffffff81660c9e: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/commoncap.c (ffffffff81699d42)
Location: security/commoncap.c:67
Inline: True
Inline callers:
  - security/commoncap.c:cap_mmap_addr
  - security/commoncap.c:cap_mmap_addr
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
Direct callers:
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/policy.c:aa_policy_admin_capable
```
**Symbols:**

```
ffffffff820f2e38-ffffffff820f2e57: cap_capable.cold (STB_LOCAL)
ffffffff81699760-ffffffff8169980e: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/commoncap.c (ffffffff816d6452)
Location: security/commoncap.c:67
Inline: True
Inline callers:
  - security/commoncap.c:cap_mmap_addr
  - security/commoncap.c:cap_mmap_addr
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_capset
Direct callers:
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/policy.c:aa_policy_admin_capable
```
**Symbols:**

```
ffffffff821d00d2-ffffffff821d00f1: cap_capable.cold (STB_LOCAL)
ffffffff816d5e10-ffffffff816d5ebe: cap_capable (STB_GLOBAL)
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
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffff80001053e2f0)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffff80001053e2f0-ffff80001053e3b0: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c06f42b8)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
c06f42b8-c06f4348: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c00000000068e800)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
c00000000068e800-c00000000068e8b8: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffe00039bb34)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffe00039bb34-ffffffe00039bbc4: cap_capable (STB_GLOBAL)
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
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8144b980)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff8144b980-ffffffff8144b9f1: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8143c3d0)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff8143c3d0-ffffffff8143c441: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81447a20)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff81447a20-ffffffff81447a91: cap_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cap_capable(const struct cred *cred, struct user_namespace *targ_ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8145ed70)
Location: security/commoncap.c:65
Inline: True
Direct callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_capset
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/smack/smack_access.c:smack_privileged_cred
```
**Symbols:**

```
ffffffff8145ed70-ffffffff8145ede1: cap_capable (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int opts</code>
</li>
<li>
<b>Param removed. </b>
<code>int audit</code>
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
