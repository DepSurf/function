# Function: <code>security_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133cd80)
Location: security/security.c:184
Inline: False
Direct callers:
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability
  - drivers/pci/pci-sysfs.c:pci_read_config
```
**Symbols:**

```
ffffffff8133cd80-ffffffff8133cde0: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813723b0)
Location: security/security.c:185
Inline: False
Direct callers:
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability
```
**Symbols:**

```
ffffffff813723b0-ffffffff81372410: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388ce0)
Location: security/security.c:185
Inline: False
Direct callers:
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability
```
**Symbols:**

```
ffffffff81388ce0-ffffffff81388d40: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139e050)
Location: security/security.c:756
Inline: False
Direct callers:
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability
```
**Symbols:**

```
ffffffff8139e050-ffffffff8139e0b0: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c39e0)
Location: security/security.c:706
Inline: False
Direct callers:
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability
```
**Symbols:**

```
ffffffff813c39e0-ffffffff813c3a46: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f40b0)
Location: security/security.c:283
Inline: False
Direct callers:
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability
```
**Symbols:**

```
ffffffff813f40b0-ffffffff813f4103: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f4e0)
Location: security/security.c:769
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
```
**Symbols:**

```
ffffffff8140f4e0-ffffffff8140f538: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c960)
Location: security/security.c:768
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff8143c960-ffffffff8143c9c3: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814564a0)
Location: security/security.c:802
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff814564a0-ffffffff814564f6: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9260)
Location: security/security.c:945
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff814a9260-ffffffff814a92b6: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6860)
Location: security/security.c:947
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
```
**Symbols:**

```
ffffffff814c6860-ffffffff814c68b6: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc950)
Location: security/security.c:971
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
```
**Symbols:**

```
ffffffff814cc950-ffffffff814cc9a6: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525ad0)
Location: security/security.c:971
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
```
**Symbols:**

```
ffffffff81525ad0-ffffffff81525b26: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b9d40)
Location: security/security.c:970
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/kallsyms.c:kallsyms_show_value
```
**Symbols:**

```
ffffffff815b9d40-ffffffff815b9dbb: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81665580)
Location: security/security.c:968
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/kallsyms.c:kallsyms_show_value
```
**Symbols:**

```
ffffffff81665580-ffffffff816655fb: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169db00)
Location: security/security.c:1076
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ksyms_common.c:kallsyms_show_value
```
**Symbols:**

```
ffffffff8169db00-ffffffff8169db7b: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816da430)
Location: security/security.c:1119
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ksyms_common.c:kallsyms_show_value
```
**Symbols:**

```
ffffffff816da430-ffffffff816da4ab: security_capable (STB_GLOBAL)
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
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541cf0)
Location: security/security.c:802
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffff800010541cf0-ffff800010541d64: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7ccc)
Location: security/security.c:802
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
c06f7ccc-c06f7d38: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006948a0)
Location: security/security.c:802
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
c0000000006948a0-c000000000694984: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e854)
Location: security/security.c:802
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffe00039e854-ffffffe00039e8a8: security_capable (STB_GLOBAL)
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
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ea80)
Location: security/security.c:802
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff8144ea80-ffffffff8144ead6: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f4d0)
Location: security/security.c:802
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff8143f4d0-ffffffff8143f526: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ab20)
Location: security/security.c:802
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_capability_noaudit
  - kernel/capability.c:has_capability
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff8144ab20-ffffffff8144ab76: security_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461ef0)
Location: security/security.c:802
Inline: False
Direct callers:
  - kernel/capability.c:ptracer_capable
  - kernel/capability.c:file_ns_capable
  - kernel/capability.c:has_ns_capability_noaudit
  - kernel/capability.c:has_ns_capability
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81461ef0-ffffffff81461f46: security_capable (STB_GLOBAL)
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
