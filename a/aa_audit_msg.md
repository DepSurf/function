# Function: <code>aa_audit_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81376bf0)
Location: security/apparmor/audit.c:109
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81376bf0-ffffffff81376c14: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff813af725)
Location: security/apparmor/audit.c:109
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff813af6b0-ffffffff813af6d4: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff813c68a5)
Location: security/apparmor/audit.c:109
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff813c6830-ffffffff813c6854: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff813dc72c)
Location: security/apparmor/audit.c:111
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff813dc6c0-ffffffff813dc6e4: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8140319c)
Location: security/apparmor/audit.c:111
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81403130-ffffffff81403154: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8143415a)
Location: security/apparmor/audit.c:111
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff814340e0-ffffffff81434104: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81450e5a)
Location: security/apparmor/audit.c:111
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81450de0-ffffffff81450e04: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8147e91a)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8147e8a0-ffffffff8147e8c5: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8149861a)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff814985a0-ffffffff814985c5: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff814f07ca)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff814f0750-ffffffff814f0775: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8150da5a)
Location: security/apparmor/audit.c:105
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8150d9e0-ffffffff8150da05: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8151446f)
Location: security/apparmor/audit.c:105
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff815143f0-ffffffff81514415: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8157232f)
Location: security/apparmor/audit.c:105
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff815722b0-ffffffff815722d5: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8160f215)
Location: security/apparmor/audit.c:148
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8160f190-ffffffff8160f1c1: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct apparmor_audit_data *ad, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816c15aa)
Location: security/apparmor/audit.c:148
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff816c1520-ffffffff816c1548: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct apparmor_audit_data *ad, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816fa1ca)
Location: security/apparmor/audit.c:148
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff816fa140-ffffffff816fa168: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct apparmor_audit_data *ad, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81736f6e)
Location: security/apparmor/audit.c:148
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:do_setattr
```
**Symbols:**

```
ffffffff81736ee0-ffffffff81736f08: aa_audit_msg (STB_GLOBAL)
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
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffff80001058e1c8)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffff80001058e108-ffff80001058e158: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (c073f068)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
c073efc4-c073eff8: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (c000000000700c4c)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
c000000000700b70-c000000000700bc0: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffe0003dc220)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffe0003dc17a-ffffffe0003dc1c0: aa_audit_msg (STB_GLOBAL)
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
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81490bfa)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff81490b80-ffffffff81490ba5: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8148161a)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff814815a0-ffffffff814815c5: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8148cc9a)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff8148cc20-ffffffff8148cc45: aa_audit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void aa_audit_msg(int type, struct common_audit_data *sa, void (*cb)(struct audit_buffer *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff814a4ada)
Location: security/apparmor/audit.c:107
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
Direct callers:
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_check_perms
  - security/apparmor/lib.c:aa_info_message
  - security/apparmor/policy.c:audit_policy
  - security/apparmor/lsm.c:apparmor_setprocattr
```
**Symbols:**

```
ffffffff814a4a60-ffffffff814a4a85: aa_audit_msg (STB_GLOBAL)
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
