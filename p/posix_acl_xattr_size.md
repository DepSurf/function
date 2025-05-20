# Function: <code>posix_acl_xattr_size</code>

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
In fs/posix_acl.c (0)
Location: include/linux/posix_acl_xattr.h:38
Inline: True
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
In fs/posix_acl.c (ffffffff81299305)
Location: include/linux/posix_acl_xattr.h:34
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
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
In fs/posix_acl.c (ffffffff812add75)
Location: include/linux/posix_acl_xattr.h:17
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff81367dcb)
Location: include/linux/posix_acl_xattr.h:17
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff812bb1f5)
Location: include/linux/posix_acl_xattr.h:17
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff8137c395)
Location: include/linux/posix_acl_xattr.h:17
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff812deae5)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff813a1235)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff8130ac25)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff813d061c)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff81320465)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff813e9b8c)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff81347d25)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff81415cea)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff8135ffc5)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff8142fb3a)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff813a5a05)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff8147f99a)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff813b6745)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff8149b07c)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff813bd725)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff814a02cc)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff8140d4e5)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff814f82ec)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff81482925)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff8158838e)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff815174f8)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff8162e841)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff8154ee1e)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff81666a81)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff81584c5e)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff816a0d91)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffff8000104261b4)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffff80001051452c)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (c05eee18)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (c06cf36c)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (c000000000535448)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (c00000000065c8ac)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffe0002c4ca8)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffe00037e0dc)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff813585a5)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff8142811a)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff81349255)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff81418b9a)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff81356075)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff814242ba)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In fs/posix_acl.c (ffffffff81369745)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_to_xattr
```
```
In fs/fuse/acl.c (ffffffff8143b0fa)
Location: include/linux/posix_acl_xattr.h:18
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
```
</details>
</li>
</ul>

## Differences
