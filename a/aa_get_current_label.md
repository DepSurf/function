# Function: <code>aa_get_current_label</code>

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
In security/apparmor/domain.c (ffffffff8137e05a)
Location: security/apparmor/include/context.h:130
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff81384076)
Location: security/apparmor/include/context.h:130
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
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
In security/apparmor/domain.c (ffffffff813b77ad)
Location: security/apparmor/include/context.h:130
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff813be2fe)
Location: security/apparmor/include/context.h:130
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff813ceaa6)
Location: security/apparmor/include/context.h:130
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff813d577e)
Location: security/apparmor/include/context.h:130
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff813e2a69)
Location: security/apparmor/include/context.h:150
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff813e9c3f)
Location: security/apparmor/include/context.h:150
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff81409829)
Location: security/apparmor/include/context.h:150
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff8140fcdc)
Location: security/apparmor/include/context.h:150
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff8143ae7b)
Location: security/apparmor/include/cred.h:91
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff814422d3)
Location: security/apparmor/include/cred.h:91
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff81457ca7)
Location: security/apparmor/include/cred.h:105
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff8145f1fa)
Location: security/apparmor/include/cred.h:105
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff81485454)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff8148c67f)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff8149f374)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff814a653f)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff814f89e3)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff815013d5)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff81515b23)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff815215b5)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff8151c4a3)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff815279a5)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff8157a573)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff81585c35)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_label *aa_get_current_label();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816186ab)
Location: security/apparmor/include/cred.h:88
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff816267a7)
Location: security/apparmor/include/cred.h:88
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_inode_init_security
Direct callers:
  - security/apparmor/lsm.c:apparmor_d_instantiate
```
**Symbols:**

```
ffffffff81622a90-ffffffff81622b4f: aa_get_current_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_label *aa_get_current_label();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816cb5df)
Location: security/apparmor/include/cred.h:88
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff816da647)
Location: security/apparmor/include/cred.h:88
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_inode_init_security
Direct callers:
  - security/apparmor/lsm.c:apparmor_d_instantiate
```
**Symbols:**

```
ffffffff816d66a0-ffffffff816d675f: aa_get_current_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_label *aa_get_current_label();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff817040e3)
Location: security/apparmor/include/cred.h:88
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff81713637)
Location: security/apparmor/include/cred.h:88
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_inode_init_security
Direct callers:
  - security/apparmor/lsm.c:apparmor_d_instantiate
```
**Symbols:**

```
ffffffff8170f2c0-ffffffff8170f37b: aa_get_current_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_label *aa_get_current_label();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81741992)
Location: security/apparmor/include/cred.h:88
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff81752897)
Location: security/apparmor/include/cred.h:88
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_inode_init_security
Direct callers:
  - security/apparmor/lsm.c:apparmor_d_instantiate
```
**Symbols:**

```
ffffffff8174dd90-ffffffff8174de4e: aa_get_current_label (STB_LOCAL)
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
In security/apparmor/domain.c (ffff8000105951a0)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffff80001059b26c)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (c07461b4)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (c074c25c)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (c00000000070a504)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (c000000000712d38)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffe0003e21f8)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffe0003e918a)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff81497954)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff8149eb1f)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff81488374)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff8148f53f)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff814939f4)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff8149abbf)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
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
In security/apparmor/domain.c (ffffffff814aba16)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/lsm.c (ffffffff814b3409)
Location: security/apparmor/include/cred.h:101
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
