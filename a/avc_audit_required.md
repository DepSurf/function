# Function: <code>avc_audit_required</code>

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
In security/selinux/avc.c (ffffffff81341593)
Location: security/selinux/include/avc.h:68
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_perm_flags
```
```
In security/selinux/hooks.c (ffffffff813455d6)
Location: security/selinux/include/avc.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
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
In security/selinux/avc.c (ffffffff81376dd4)
Location: security/selinux/include/avc.h:68
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8137aec9)
Location: security/selinux/include/avc.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff8138d704)
Location: security/selinux/include/avc.h:68
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff81391319)
Location: security/selinux/include/avc.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff813a33f4)
Location: security/selinux/include/avc.h:68
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff813a7ab9)
Location: security/selinux/include/avc.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff813c91f4)
Location: security/selinux/include/avc.h:69
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff813cd289)
Location: security/selinux/include/avc.h:69
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff813f8aa7)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff81400fd1)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff81414557)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8141d35a)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff81441d6b)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8144ad63)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff8145b82b)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff814649b3)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff814ae9f9)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff814b6be8)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
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
In security/selinux/avc.c (ffffffff814cc4de)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff814d48b8)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
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
In security/selinux/avc.c (ffffffff814d2b0e)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff814db697)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
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
In security/selinux/avc.c (ffffffff8152b7de)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff81534735)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
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
In security/selinux/avc.c (ffffffff815c142a)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff815ca8c6)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
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
In security/selinux/avc.c (ffffffff8166d9f4)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff81677bb6)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
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
In security/selinux/avc.c (ffffffff816a6111)
Location: security/selinux/include/avc.h:63
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff816afe8e)
Location: security/selinux/include/avc.h:63
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
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
In security/selinux/avc.c (ffffffff816e2b51)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff816ece11)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
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
In security/selinux/avc.c (ffff800010547fb8)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffff800010552a68)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (c06fdc04)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (c0705d44)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (c00000000069f13c)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (c0000000006aa878)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffe0003a33f6)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffe0003ab888)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff81453e0b)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8145cf93)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff8144484b)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8144d9c3)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff8144feab)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff81459033)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/avc.c (ffffffff8146737b)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8146d9f3)
Location: security/selinux/include/avc.h:64
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
</ul>

## Differences
