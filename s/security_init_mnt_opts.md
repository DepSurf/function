# Function: <code>security_init_mnt_opts</code>

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
In security/selinux/hooks.c (ffffffff81347667)
Location: include/linux/security.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/smack/smack_lsm.c (ffffffff813609c9)
Location: include/linux/security.h:161
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
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
In security/selinux/hooks.c (ffffffff8137f39b)
Location: include/linux/security.h:163
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/smack/smack_lsm.c (ffffffff81397989)
Location: include/linux/security.h:163
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
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
In security/selinux/hooks.c (ffffffff81395e2b)
Location: include/linux/security.h:163
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/smack/smack_lsm.c (ffffffff813ae569)
Location: include/linux/security.h:163
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
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
In security/selinux/hooks.c (ffffffff813abef6)
Location: include/linux/security.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/smack/smack_lsm.c (ffffffff813c3489)
Location: include/linux/security.h:177
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
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
In security/selinux/hooks.c (ffffffff813d1f66)
Location: include/linux/security.h:176
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/smack/smack_lsm.c (ffffffff813e9749)
Location: include/linux/security.h:176
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
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
In security/selinux/hooks.c (ffffffff81401732)
Location: include/linux/security.h:174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/smack/smack_lsm.c (ffffffff8141a678)
Location: include/linux/security.h:174
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
