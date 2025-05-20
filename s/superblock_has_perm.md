# Function: <code>superblock_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813430ca)
Location: security/selinux/hooks.c:1914
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_sb_kern_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81377ff6)
Location: security/selinux/hooks.c:1987
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138ead6)
Location: security/selinux/hooks.c:1995
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int superblock_has_perm(const struct cred *cred, struct super_block *sb, u32 perms, struct common_audit_data *ad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a45c0)
Location: security/selinux/hooks.c:1976
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
**Symbols:**

```
ffffffff813a45c0-ffffffff813a45fb: superblock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int superblock_has_perm(const struct cred *cred, struct super_block *sb, u32 perms, struct common_audit_data *ad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ca6e0)
Location: security/selinux/hooks.c:1990
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
**Symbols:**

```
ffffffff813ca6e0-ffffffff813ca71b: superblock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813f9a8c)
Location: security/selinux/hooks.c:2103
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81415a6c)
Location: security/selinux/hooks.c:1917
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144349c)
Location: security/selinux/hooks.c:1961
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81463c93)
Location: security/selinux/hooks.c:1963
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b909b)
Location: security/selinux/hooks.c:1916
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d6fab)
Location: security/selinux/hooks.c:1925
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814ddf4b)
Location: security/selinux/hooks.c:1985
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815345a3)
Location: security/selinux/hooks.c:1977
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815ca710)
Location: security/selinux/hooks.c:1915
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816779f0)
Location: security/selinux/hooks.c:1914
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816afccf)
Location: security/selinux/hooks.c:1914
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ecc3f)
Location: security/selinux/hooks.c:1954
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010551c98)
Location: security/selinux/hooks.c:1963
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0703fc4)
Location: security/selinux/hooks.c:1963
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a827c)
Location: security/selinux/hooks.c:1963
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003aad86)
Location: security/selinux/hooks.c:1963
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145c273)
Location: security/selinux/hooks.c:1963
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144cca3)
Location: security/selinux/hooks.c:1963
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81458313)
Location: security/selinux/hooks.c:1963
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146d273)
Location: security/selinux/hooks.c:1963
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
