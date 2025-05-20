# Function: <code>ext4_jbd2_credits_xattr</code>

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
In fs/ext4/xattr.c (ffffffff812de9a2)
Location: fs/ext4/ext4_jbd2.h:107
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff812e449f)
Location: fs/ext4/ext4_jbd2.h:107
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/crypto_policy.c (ffffffff812e48c8)
Location: fs/ext4/ext4_jbd2.h:107
Inline: True
Inline callers:
  - fs/ext4/crypto_policy.c:ext4_process_policy
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
In fs/ext4/super.c (ffffffff812e73ab)
Location: fs/ext4/ext4_jbd2.h:107
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff8130e692)
Location: fs/ext4/ext4_jbd2.h:107
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff813143af)
Location: fs/ext4/ext4_jbd2.h:107
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/super.c (ffffffff812fcfc2)
Location: fs/ext4/ext4_jbd2.h:107
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffffffff813243d2)
Location: fs/ext4/ext4_jbd2.h:107
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/acl.c (ffffffff8132a38f)
Location: fs/ext4/ext4_jbd2.h:107
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
</details>
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
