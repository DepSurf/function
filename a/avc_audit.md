# Function: <code>avc_audit</code>

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
Location: security/selinux/include/avc.h:129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_perm_flags
```
```
In security/selinux/hooks.c (ffffffff81346fd1)
Location: security/selinux/include/avc.h:129
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
In security/selinux/avc.c (ffffffff81376dd4)
Location: security/selinux/include/avc.h:129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8137c85b)
Location: security/selinux/include/avc.h:129
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8139330b)
Location: security/selinux/include/avc.h:129
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff813a94e7)
Location: security/selinux/include/avc.h:129
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:130
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff813cf4a7)
Location: security/selinux/include/avc.h:130
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:126
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff813fc132)
Location: security/selinux/include/avc.h:126
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:126
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8141885d)
Location: security/selinux/include/avc.h:126
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:126
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8144662d)
Location: security/selinux/include/avc.h:126
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff814601bd)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff814b2ad9)
Location: security/selinux/include/avc.h:125
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
In security/selinux/avc.c (ffffffff814cc4de)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff814cfe59)
Location: security/selinux/include/avc.h:125
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
In security/selinux/avc.c (ffffffff814d2b0e)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff814d6569)
Location: security/selinux/include/avc.h:125
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
In security/selinux/avc.c (ffffffff8152b7de)
Location: security/selinux/include/avc.h:124
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8152efa9)
Location: security/selinux/include/avc.h:124
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
In security/selinux/avc.c (ffffffff815c142a)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff815c5b21)
Location: security/selinux/include/avc.h:125
Inline: True
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff81672765)
Location: security/selinux/include/avc.h:125
Inline: True
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
Location: security/selinux/include/avc.h:122
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff816aac3c)
Location: security/selinux/include/avc.h:122
Inline: True
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
Location: security/selinux/include/avc.h:119
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff816e7ccc)
Location: security/selinux/include/avc.h:119
Inline: True
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffff80001054d904)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (c07065a8)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (c0000000006ab680)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffe0003a79a6)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8145879d)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff814491cd)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8145483d)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
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
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
```
```
In security/selinux/hooks.c (ffffffff8146f21d)
Location: security/selinux/include/avc.h:125
Inline: True
Inline callers:
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
</ul>

## Differences
