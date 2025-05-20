# Function: <code>aa_dfa_null_transition</code>

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
In security/apparmor/domain.c (ffffffff8137a4b6)
Location: security/apparmor/include/lib.h:106
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
```
```
In security/apparmor/file.c (ffffffff813881ac)
Location: security/apparmor/include/lib.h:106
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff8138ec57)
Location: security/apparmor/include/lib.h:106
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:match_mnt
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/af_unix.c (ffffffff813918b7)
Location: security/apparmor/include/lib.h:106
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_to_local
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
In security/apparmor/domain.c (ffffffff813b335c)
Location: security/apparmor/include/lib.h:106
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
```
```
In security/apparmor/file.c (ffffffff813c2cf6)
Location: security/apparmor/include/lib.h:106
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff813ca312)
Location: security/apparmor/include/lib.h:106
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff813ccf39)
Location: security/apparmor/include/lib.h:106
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
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
In security/apparmor/domain.c (ffffffff813ca51c)
Location: security/apparmor/include/lib.h:107
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
```
```
In security/apparmor/file.c (ffffffff813da1d9)
Location: security/apparmor/include/lib.h:107
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff813e1992)
Location: security/apparmor/include/lib.h:107
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff813e45b9)
Location: security/apparmor/include/lib.h:107
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813dfc61)
Location: security/apparmor/include/lib.h:91
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
```
```
In security/apparmor/file.c (ffffffff813eb334)
Location: security/apparmor/include/lib.h:91
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff813f0622)
Location: security/apparmor/include/lib.h:91
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff813f2109)
Location: security/apparmor/include/lib.h:91
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814064e1)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
```
```
In security/apparmor/file.c (ffffffff81412c74)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff81418682)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff8141a189)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81437ccc)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffffffff81445009)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff8144aae0)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff8144c2b9)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8145488c)
Location: security/apparmor/include/lib.h:84
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffffffff81461ef9)
Location: security/apparmor/include/lib.h:84
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff81467a50)
Location: security/apparmor/include/lib.h:84
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff81469219)
Location: security/apparmor/include/lib.h:84
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81482241)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffffffff8148f1b8)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff81494ac3)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff81496269)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8149bf71)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffffffff814a9078)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff814ae9f3)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff814b0199)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f49cd)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/file.c (ffffffff81506643)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff8150dbc7)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/af_unix.c (ffffffff8150f787)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81511b0d)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/file.c (ffffffff81523742)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff8152aa3c)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/af_unix.c (ffffffff8152c5c7)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8151846d)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/file.c (ffffffff81529935)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff81530c8f)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/af_unix.c (ffffffff81532907)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81576477)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/file.c (ffffffff81587cd5)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff8158f0cf)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/af_unix.c (ffffffff81590e87)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8161454c)
Location: security/apparmor/include/lib.h:90
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/file.c (ffffffff816283d2)
Location: security/apparmor/include/lib.h:90
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff816300b6)
Location: security/apparmor/include/lib.h:90
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/af_unix.c (ffffffff81633aff)
Location: security/apparmor/include/lib.h:90
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_bind_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816c7274)
Location: security/apparmor/include/lib.h:112
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/file.c (ffffffff816dcb0c)
Location: security/apparmor/include/lib.h:112
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff816e4d38)
Location: security/apparmor/include/lib.h:112
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/af_unix.c (ffffffff816e8cdb)
Location: security/apparmor/include/lib.h:112
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8170064f)
Location: security/apparmor/include/lib.h:115
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/file.c (ffffffff8171610b)
Location: security/apparmor/include/lib.h:115
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff8171e392)
Location: security/apparmor/include/lib.h:115
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/af_unix.c (ffffffff81722491)
Location: security/apparmor/include/lib.h:115
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
```
```
In security/apparmor/notify.c (ffffffff81723456)
Location: security/apparmor/include/lib.h:115
Inline: True
Inline callers:
  - security/apparmor/notify.c:notification_match
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8173dc30)
Location: security/apparmor/include/lib.h:114
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/file.c (ffffffff81754bbb)
Location: security/apparmor/include/lib.h:114
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff8175cd78)
Location: security/apparmor/include/lib.h:114
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
  - security/apparmor/mount.c:do_match_mnt
```
```
In security/apparmor/af_unix.c (ffffffff81760cb1)
Location: security/apparmor/include/lib.h:114
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
```
```
In security/apparmor/af_inet.c (ffffffff817622de)
Location: security/apparmor/include/lib.h:114
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:match_addr_label
  - security/apparmor/af_inet.c:match_addr_label
```
```
In security/apparmor/notify.c (ffffffff81764756)
Location: security/apparmor/include/lib.h:114
Inline: True
Inline callers:
  - security/apparmor/notify.c:notification_match
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffff800010591830)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffff80001059fa24)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffff8000105a60ec)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffff8000105a7a88)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c07432f8)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (c07506b0)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (c0756098)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (c0757918)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c00000000070552c)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (c0000000007199b0)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (c000000000722214)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (c0000000007244d0)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffe0003df30a)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffffffe0003eabfc)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffe0003efbe8)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffe0003f1162)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81494551)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffffffff814a1658)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff814a6fd3)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff814a8779)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81484f71)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffffffff81492078)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff814979f3)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff81499199)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814905f1)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffffffff8149d6f8)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff814a3073)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff814a4819)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814a8501)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/domain.c:aa_xattrs_match
```
```
In security/apparmor/file.c (ffffffff814b5c98)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:profile_path_link
```
```
In security/apparmor/mount.c (ffffffff814bb806)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/af_unix.c (ffffffff814bd0a9)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
</details>
</li>
</ul>

## Differences
