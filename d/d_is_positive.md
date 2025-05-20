# Function: <code>d_is_positive</code>

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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:466
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/dcache.h:466
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:466
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/dcache.h:466
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:466
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:466
Inline: True
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:440
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/dcache.h:440
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:440
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8137a0d4)
Location: include/linux/dcache.h:440
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:440
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:440
Inline: True
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:440
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/dcache.h:440
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:440
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813907f4)
Location: include/linux/dcache.h:440
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:440
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:440
Inline: True
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:446
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/dcache.h:446
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:446
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813a6c5a)
Location: include/linux/dcache.h:446
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:446
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:446
Inline: True
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
In kernel/audit_watch.c (0)
Location: include/linux/dcache.h:447
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/dcache.h:447
Inline: True
```
```
In security/security.c (0)
Location: include/linux/dcache.h:447
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813cc6aa)
Location: include/linux/dcache.h:447
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/dcache.h:447
Inline: True
```
```
In security/apparmor/path.c (0)
Location: include/linux/dcache.h:447
Inline: True
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
In kernel/audit_watch.c (ffffffff81159144)
Location: include/linux/dcache.h:448
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812aca15)
Location: include/linux/dcache.h:448
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff813f4983)
Location: include/linux/dcache.h:448
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff814007e0)
Location: include/linux/dcache.h:448
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff8141b759)
Location: include/linux/dcache.h:448
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff814370eb)
Location: include/linux/dcache.h:448
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In kernel/audit_watch.c (ffffffff811660e4)
Location: include/linux/dcache.h:445
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812c1b15)
Location: include/linux/dcache.h:445
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff8140fd53)
Location: include/linux/dcache.h:445
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8141c89e)
Location: include/linux/dcache.h:445
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81437da1)
Location: include/linux/dcache.h:445
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81453d4b)
Location: include/linux/dcache.h:445
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In kernel/audit_watch.c (ffffffff81172c17)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812de07e)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff8143d3b8)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8144a294)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81465a0d)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81481619)
Location: include/linux/dcache.h:443
Inline: True
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
In kernel/audit_watch.c (ffffffff8117eab3)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812efb9e)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff81456e58)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff81463fac)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff8147f8bd)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff8149b349)
Location: include/linux/dcache.h:443
Inline: True
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
In kernel/audit_watch.c (ffffffff8119203c)
Location: include/linux/dcache.h:450
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff81327e4f)
Location: include/linux/dcache.h:450
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff814a9c68)
Location: include/linux/dcache.h:450
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff814b803f)
Location: include/linux/dcache.h:450
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff814d4c7d)
Location: include/linux/dcache.h:450
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff814f3d98)
Location: include/linux/dcache.h:450
Inline: True
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
In kernel/audit_watch.c (ffffffff8118f1cc)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff81334946)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff814c7268)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff814d5d4f)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff814f227d)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81510ef8)
Location: include/linux/dcache.h:451
Inline: True
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
In kernel/audit_watch.c (ffffffff8118fff9)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff8133aa83)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff814cd6a8)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff814dcbb2)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff814f929d)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81517878)
Location: include/linux/dcache.h:454
Inline: True
```
```
In security/landlock/fs.c (ffffffff815386bf)
Location: include/linux/dcache.h:454
Inline: True
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
In kernel/audit_watch.c (ffffffff811b8ed9)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff8138868d)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff815265f8)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff81536082)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff81553e8d)
Location: include/linux/dcache.h:454
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81575878)
Location: include/linux/dcache.h:454
Inline: True
```
```
In security/landlock/fs.c (ffffffff81596eb3)
Location: include/linux/dcache.h:454
Inline: True
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
In kernel/audit_watch.c (ffffffff811ebf0a)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff8140969d)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff815bae88)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff815cc4f9)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff815edd2d)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81613358)
Location: include/linux/dcache.h:444
Inline: True
```
```
In security/landlock/fs.c (ffffffff8163976f)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:check_access_path_dual
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
In kernel/audit_watch.c (ffffffff8123236a)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff81493d4d)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff81666938)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff81679719)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff8169e1cd)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff816c5fa8)
Location: include/linux/dcache.h:444
Inline: True
```
```
In security/landlock/fs.c (ffffffff816f0e1f)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
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
In kernel/audit_watch.c (ffffffff81248ffa)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff814c8dbb)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff8169ef28)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff816b18ab)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff816d6b6d)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff816fed88)
Location: include/linux/dcache.h:444
Inline: True
```
```
In security/landlock/fs.c (ffffffff8172b2ba)
Location: include/linux/dcache.h:444
Inline: True
Inline callers:
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
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
In kernel/audit_watch.c (ffffffff81262e8a)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff814fb67a)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff816db878)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff816ee93e)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
```
```
In security/smack/smack_lsm.c (ffffffff8171341d)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff8173c318)
Location: include/linux/dcache.h:451
Inline: True
```
```
In security/landlock/fs.c (ffffffff8176da72)
Location: include/linux/dcache.h:451
Inline: True
Inline callers:
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
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
In kernel/audit_watch.c (ffff8000101f39dc)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffff8000103992fc)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffff8000105428d0)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffff80001055203c)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffff800010570c30)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffff80001059161c)
Location: include/linux/dcache.h:443
Inline: True
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
In kernel/audit_watch.c (c0433e4c)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (c057f988)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (c06f8878)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (c070433c)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (c07241ac)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (c0742220)
Location: include/linux/dcache.h:443
Inline: True
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
In kernel/audit_watch.c (c000000000268654)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (c000000000493af0)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (c000000000695f04)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (c0000000006a887c)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (c0000000006d749c)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (c00000000070526c)
Location: include/linux/dcache.h:443
Inline: True
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
In kernel/audit_watch.c (ffffffe000166dd0)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffe000266da4)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffe00039f122)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffe0003ab06e)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffe0003c38ea)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffe0003def88)
Location: include/linux/dcache.h:443
Inline: True
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
In kernel/audit_watch.c (ffffffff811770d3)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812e817e)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff8144f438)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8145c58c)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81477e9d)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81493929)
Location: include/linux/dcache.h:443
Inline: True
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
In kernel/audit_watch.c (ffffffff8116a273)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812d8dbe)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff8143fe88)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8144cfbc)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff814688bd)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff81484349)
Location: include/linux/dcache.h:443
Inline: True
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
In kernel/audit_watch.c (ffffffff81174ea3)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812e5f8e)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff8144b4d8)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8145862c)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff81473f3d)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff8148f9c9)
Location: include/linux/dcache.h:443
Inline: True
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
In kernel/audit_watch.c (ffffffff81182783)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In fs/namei.c (ffffffff812f6f0e)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:filename_create
```
```
In security/security.c (ffffffff814628a8)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/security.c:security_inode_rename
  - security/security.c:security_path_rename
```
```
In security/selinux/hooks.c (ffffffff8146d44c)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
```
```
In security/smack/smack_lsm.c (ffffffff8148b84d)
Location: include/linux/dcache.h:443
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_link
```
```
In security/apparmor/path.c (ffffffff814a78d7)
Location: include/linux/dcache.h:443
Inline: True
```
</details>
</li>
</ul>

## Differences
