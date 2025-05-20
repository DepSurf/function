# Function: <code>aa_dfa_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813796e0)
Location: security/apparmor/match.c:425
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff813796e0-ffffffff8137974a: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813b2470)
Location: security/apparmor/match.c:429
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff813b2470-ffffffff813b24f5: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813c9630)
Location: security/apparmor/match.c:429
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff813c9630-ffffffff813c96b5: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813ded00)
Location: security/apparmor/match.c:429
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff813ded00-ffffffff813ded70: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814056a0)
Location: security/apparmor/match.c:429
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff814056a0-ffffffff81405710: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81436810)
Location: security/apparmor/match.c:483
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81436810-ffffffff814368a9: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81453470)
Location: security/apparmor/match.c:483
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81453470-ffffffff81453509: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81480df0)
Location: security/apparmor/match.c:479
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81480df0-ffffffff81480e89: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8149aaf0)
Location: security/apparmor/match.c:494
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff8149aaf0-ffffffff8149ab89: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814f35c0)
Location: security/apparmor/match.c:518
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff814f35c0-ffffffff814f365c: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81510790)
Location: security/apparmor/match.c:518
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81510790-ffffffff8151082c: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81517140)
Location: security/apparmor/match.c:518
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81517140-ffffffff815171e0: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81575140)
Location: security/apparmor/match.c:518
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81575140-ffffffff815751e0: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81612b60)
Location: security/apparmor/match.c:517
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_signal_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_bind_perm
```
**Symbols:**

```
ffffffff81612b60-ffffffff81612c32: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816c5740)
Location: security/apparmor/match.c:517
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_signal_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
```
**Symbols:**

```
ffffffff816c5740-ffffffff816c5812: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816fe520)
Location: security/apparmor/match.c:473
Inline: False
Direct callers:
  - security/apparmor/ipc.c:profile_signal_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/notify.c:notification_match
  - security/apparmor/notify.c:notification_match
```
**Symbols:**

```
ffffffff816fe520-ffffffff816fe5f2: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8173bab0)
Location: security/apparmor/match.c:473
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_profile_capget
  - security/apparmor/capability.c:profile_capable
  - security/apparmor/ipc.c:profile_signal_perm
  - security/apparmor/lib.c:aa_profile_label_perm
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_inet.c:match_addr_label
  - security/apparmor/af_inet.c:match_addr_label
  - security/apparmor/notify.c:notification_match
  - security/apparmor/notify.c:notification_match
```
**Symbols:**

```
ffffffff8173bab0-ffffffff8173bb82: aa_dfa_next (STB_GLOBAL)
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
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffff800010590c80)
Location: security/apparmor/match.c:494
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffff800010590c80-ffff800010590d4c: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c07419ac)
Location: security/apparmor/match.c:494
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
c07419ac-c0741a64: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c0000000007045d0)
Location: security/apparmor/match.c:494
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
c0000000007045d0-c000000000704698: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffe0003de706)
Location: security/apparmor/match.c:494
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffe0003de706-ffffffe0003de7e6: aa_dfa_next (STB_GLOBAL)
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
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814930d0)
Location: security/apparmor/match.c:494
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff814930d0-ffffffff81493169: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81483af0)
Location: security/apparmor/match.c:494
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81483af0-ffffffff81483b89: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148f170)
Location: security/apparmor/match.c:494
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff8148f170-ffffffff8148f209: aa_dfa_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa *dfa, unsigned int state, const char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814a7080)
Location: security/apparmor/match.c:494
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_profile_match_label
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff814a7080-ffffffff814a7119: aa_dfa_next (STB_GLOBAL)
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
