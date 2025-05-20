# Function: <code>aa_check_perms</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81378c10)
Location: security/apparmor/lib.c:447
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff81378c10-ffffffff81378cf5: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813b1980)
Location: security/apparmor/lib.c:447
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff813b1980-ffffffff813b1a75: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813c8b40)
Location: security/apparmor/lib.c:447
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff813c8b40-ffffffff813c8c35: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813de2e0)
Location: security/apparmor/lib.c:425
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff813de2e0-ffffffff813de3d9: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81404c70)
Location: security/apparmor/lib.c:422
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff81404c70-ffffffff81404d69: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81435d30)
Location: security/apparmor/lib.c:422
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff81435d30-ffffffff81435e29: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81452950)
Location: security/apparmor/lib.c:433
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff81452950-ffffffff81452a49: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81480310)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff81480310-ffffffff81480402: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8149a010)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff8149a010-ffffffff8149a102: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814f2770)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814f2770-ffffffff814f2865: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8150f970)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff8150f970-ffffffff8150fa65: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81516350)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81516350-ffffffff81516446: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81574350)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81574350-ffffffff81574446: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81611b90)
Location: security/apparmor/lib.c:397
Inline: False
Direct callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:profile_ptrace_perm
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/ipc.c:profile_signal_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff81611b90-ffffffff81611c99: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct apparmor_audit_data *ad, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816c48b0)
Location: security/apparmor/lib.c:489
Inline: False
Direct callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:profile_ptrace_perm
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/ipc.c:profile_signal_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/lsm.c:apparmor_task_prctl
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff816c48b0-ffffffff816c4999: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct apparmor_audit_data *ad, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816fd480)
Location: security/apparmor/lib.c:489
Inline: False
Direct callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:profile_ptrace_perm
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/ipc.c:profile_signal_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/lsm.c:apparmor_task_prctl
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_profile_af_perm
```
**Symbols:**

```
ffffffff816fd480-ffffffff816fd56b: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct apparmor_audit_data *ad, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8173a9e0)
Location: security/apparmor/lib.c:489
Inline: False
Direct callers:
  - security/apparmor/capability.c:profile_capable
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:profile_ptrace_perm
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/ipc.c:profile_signal_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_inet.c:do_perms
```
**Symbols:**

```
ffffffff8173a9e0-ffffffff8173aacb: aa_check_perms (STB_GLOBAL)
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
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffff800010590020)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffff800010590020-ffff800010590168: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c0740db8)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
c0740db8-c0740ed4: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c0000000007034c0)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
c0000000007034c0-c000000000703658: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffe0003ddb9c)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffe0003ddb9c-ffffffe0003ddca4: aa_check_perms (STB_GLOBAL)
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
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814925f0)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff814925f0-ffffffff814926e2: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81483010)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff81483010-ffffffff81483102: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8148e690)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff8148e690-ffffffff8148e782: aa_check_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_check_perms(struct aa_profile *profile, struct aa_perms *perms, u32 request, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814a65a0)
Location: security/apparmor/lib.c:429
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_ptrace_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:do_perms
```
**Symbols:**

```
ffffffff814a65a0-ffffffff814a6692: aa_check_perms (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct apparmor_audit_data *ad</code>
</li>
<li>
<b>Param removed. </b>
<code>struct common_audit_data *sa</code>
</li>
</ul>
</details>
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
