# Function: <code>aa_dfa_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81379620)
Location: security/apparmor/match.c:377
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81379620-ffffffff813796d6: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813b23b0)
Location: security/apparmor/match.c:381
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff813b23b0-ffffffff813b2466: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813c9570)
Location: security/apparmor/match.c:381
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff813c9570-ffffffff813c9626: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813dec40)
Location: security/apparmor/match.c:381
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff813dec40-ffffffff813decfa: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814055e0)
Location: security/apparmor/match.c:381
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff814055e0-ffffffff8140569a: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81436740)
Location: security/apparmor/match.c:444
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81436740-ffffffff8143680b: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814533a0)
Location: security/apparmor/match.c:444
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814533a0-ffffffff8145346b: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81480d10)
Location: security/apparmor/match.c:440
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81480d10-ffffffff81480dea: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8149aa10)
Location: security/apparmor/match.c:455
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff8149aa10-ffffffff8149aaea: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814f3300)
Location: security/apparmor/match.c:479
Inline: False
Direct callers:
  - security/apparmor/match.c:leftmatch_fb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
**Symbols:**

```
ffffffff814f3300-ffffffff814f33df: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff815104d0)
Location: security/apparmor/match.c:479
Inline: False
Direct callers:
  - security/apparmor/match.c:leftmatch_fb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
**Symbols:**

```
ffffffff815104d0-ffffffff815105af: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81516e80)
Location: security/apparmor/match.c:479
Inline: False
Direct callers:
  - security/apparmor/match.c:leftmatch_fb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
**Symbols:**

```
ffffffff81516e80-ffffffff81516f5a: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81574e80)
Location: security/apparmor/match.c:479
Inline: False
Direct callers:
  - security/apparmor/match.c:leftmatch_fb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
**Symbols:**

```
ffffffff81574e80-ffffffff81574f5a: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81612870)
Location: security/apparmor/match.c:479
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/match.c:leftmatch_fb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
**Symbols:**

```
ffffffff81612870-ffffffff81612970: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816c5430)
Location: security/apparmor/match.c:479
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/match.c:leftmatch_fb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
**Symbols:**

```
ffffffff816c5430-ffffffff816c5530: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816fe030)
Location: security/apparmor/match.c:435
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/match.c:leftmatch_fb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/notify.c:notification_match
```
**Symbols:**

```
ffffffff816fe030-ffffffff816fe130: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8173b5c0)
Location: security/apparmor/match.c:435
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/match.c:leftmatch_fb
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/notify.c:notification_match
```
**Symbols:**

```
ffffffff8173b5c0-ffffffff8173b6c0: aa_dfa_match (STB_GLOBAL)
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
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffff800010590b70)
Location: security/apparmor/match.c:455
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffff800010590b70-ffff800010590c80: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c07418a8)
Location: security/apparmor/match.c:455
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
c07418a8-c07419ac: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c000000000704440)
Location: security/apparmor/match.c:455
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
c000000000704440-c0000000007045c8: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffe0003de604)
Location: security/apparmor/match.c:455
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffe0003de604-ffffffe0003de706: aa_dfa_match (STB_GLOBAL)
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
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81492ff0)
Location: security/apparmor/match.c:455
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81492ff0-ffffffff814930ca: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81483a10)
Location: security/apparmor/match.c:455
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81483a10-ffffffff81483aea: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148f090)
Location: security/apparmor/match.c:455
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff8148f090-ffffffff8148f16a: aa_dfa_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa *dfa, unsigned int start, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814a6fa0)
Location: security/apparmor/match.c:455
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_leftmatch
  - security/apparmor/file.c:aa_str_perms
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814a6fa0-ffffffff814a707a: aa_dfa_match (STB_GLOBAL)
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
