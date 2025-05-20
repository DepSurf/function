# Function: <code>ext4_has_feature_casefold</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8139ce18)
Location: fs/ext4/ext4.h:1775
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff813cc167)
Location: fs/ext4/ext4.h:1775
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff813aeea0)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813b5898)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff813e553b)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff813faf45)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8140109b)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff814326b0)
Location: fs/ext4/ext4.h:1929
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff8140d5e8)
Location: fs/ext4/ext4.h:2054
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8141395b)
Location: fs/ext4/ext4.h:2054
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff8144b4e5)
Location: fs/ext4/ext4.h:2054
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff8141384e)
Location: fs/ext4/ext4.h:2063
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81419bce)
Location: fs/ext4/ext4.h:2063
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff81450f2a)
Location: fs/ext4/ext4.h:2063
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff81466b9a)
Location: fs/ext4/ext4.h:2130
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8146cdbe)
Location: fs/ext4/ext4.h:2130
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff814a454b)
Location: fs/ext4/ext4.h:2130
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff814e670c)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814ec74f)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff8152c1d2)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
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
In fs/ext4/inode.c (ffffffff8157fea8)
Location: fs/ext4/ext4.h:2142
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815864cc)
Location: fs/ext4/ext4.h:2142
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff815cb069)
Location: fs/ext4/ext4.h:2142
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
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
In fs/ext4/inode.c (ffffffff815b72f3)
Location: fs/ext4/ext4.h:2136
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815bcc0c)
Location: fs/ext4/ext4.h:2136
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff8160313c)
Location: fs/ext4/ext4.h:2136
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
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
In fs/ext4/inode.c (ffffffff815f008c)
Location: fs/ext4/ext4.h:2154
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815f59ea)
Location: fs/ext4/ext4.h:2154
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff8163bf55)
Location: fs/ext4/ext4.h:2154
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
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
In fs/ext4/inode.c (ffff800010483870)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffff80001048aae0)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffff8000104be7d0)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (c0644d70)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (c064c078)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (c0682124)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (c0000000005a88b0)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (c0000000005b13d4)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (c0000000005f4f50)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffe00030bf0a)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffe000311658)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffe00033a398)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff813a7480)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813ade78)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff813ddb1b)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff81397f10)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139e908)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff813ce59b)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff813a4ce0)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813ab6d8)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff813d7d97)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/inode.c (ffffffff813b93fd)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813c0078)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/super.c (ffffffff813f028b)
Location: fs/ext4/ext4.h:1832
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
</ul>

## Differences
