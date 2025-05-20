# Function: <code>aa_audit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81376c20)
Location: security/apparmor/audit.c:132
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/mount.c:audit_mount
```
**Symbols:**

```
ffffffff81376c20-ffffffff81376d88: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff813af6e0)
Location: security/apparmor/audit.c:132
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/mount.c:audit_mount
```
**Symbols:**

```
ffffffff813af6e0-ffffffff813af7fd: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff813c6860)
Location: security/apparmor/audit.c:132
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
  - security/apparmor/mount.c:audit_mount
```
**Symbols:**

```
ffffffff813c6860-ffffffff813c697d: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff813dc6f0)
Location: security/apparmor/audit.c:129
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff813dc6f0-ffffffff813dc7ff: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81403160)
Location: security/apparmor/audit.c:129
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff81403160-ffffffff8140326f: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81434110)
Location: security/apparmor/audit.c:129
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff81434110-ffffffff8143422a: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81450e10)
Location: security/apparmor/audit.c:129
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff81450e10-ffffffff81450f2a: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8147e8d0)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff8147e8d0-ffffffff8147e9e8: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff814985d0)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff814985d0-ffffffff814986e8: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff814f0780)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff814f0780-ffffffff814f08a1: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8150da10)
Location: security/apparmor/audit.c:123
Inline: False
Direct callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff8150da10-ffffffff8150db31: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81514420)
Location: security/apparmor/audit.c:123
Inline: False
Direct callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff81514420-ffffffff81514542: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff815722e0)
Location: security/apparmor/audit.c:123
Inline: False
Direct callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff815722e0-ffffffff81572402: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8160f1d0)
Location: security/apparmor/audit.c:166
Inline: False
Direct callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff8160f1d0-ffffffff8160f35f: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct apparmor_audit_data *ad, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816c1560)
Location: security/apparmor/audit.c:166
Inline: False
Direct callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff816c1560-ffffffff816c16f9: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct apparmor_audit_data *ad, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816fa180)
Location: security/apparmor/audit.c:166
Inline: False
Direct callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff816fa180-ffffffff816fa31d: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct apparmor_audit_data *ad, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81736f20)
Location: security/apparmor/audit.c:166
Inline: False
Direct callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff81736f20-ffffffff817370b5: aa_audit (STB_GLOBAL)
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
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffff80001058e158)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffff80001058e158-ffff80001058e2ec: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (c073eff8)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
c073eff8-c073f170: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (c000000000700bc0)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
c000000000700bc0-c000000000700dd0: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffe0003dc1c0)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffe0003dc1c0-ffffffe0003dc308: aa_audit (STB_GLOBAL)
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
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81490bb0)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff81490bb0-ffffffff81490cc8: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff814815d0)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff814815d0-ffffffff814816e8: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8148cc50)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff8148cc50-ffffffff8148cd68: aa_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_audit(int type, struct aa_profile *profile, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff814a4a90)
Location: security/apparmor/audit.c:125
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_may_ptrace
  - security/apparmor/resource.c:audit_resource
  - security/apparmor/file.c:aa_audit_file
```
**Symbols:**

```
ffffffff814a4a90-ffffffff814a4ba8: aa_audit (STB_GLOBAL)
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
