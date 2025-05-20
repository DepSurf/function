# Function: <code>ext4_valid_inum</code>

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
In fs/ext4/inode.c (ffffffff812962fc)
Location: fs/ext4/ext4.h:1435
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/namei.c (ffffffff812a49ad)
Location: fs/ext4/ext4.h:1435
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/inode.c (ffffffff812c38ec)
Location: fs/ext4/ext4.h:1532
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/namei.c (ffffffff812d3bef)
Location: fs/ext4/ext4.h:1532
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/inode.c (ffffffff812d8f9c)
Location: fs/ext4/ext4.h:1537
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/namei.c (ffffffff812e992f)
Location: fs/ext4/ext4.h:1537
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/inode.c (ffffffff812ff665)
Location: fs/ext4/ext4.h:1542
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/namei.c (ffffffff813190fb)
Location: fs/ext4/ext4.h:1542
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/inode.c (ffffffff81323e15)
Location: fs/ext4/ext4.h:1501
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/namei.c (ffffffff8133d83b)
Location: fs/ext4/ext4.h:1501
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff8136bdd8)
Location: fs/ext4/ext4.h:1511
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff813842a8)
Location: fs/ext4/ext4.h:1524
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff813adac0)
Location: fs/ext4/ext4.h:1541
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff813c6a00)
Location: fs/ext4/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff81412f10)
Location: fs/ext4/ext4.h:1604
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff81426503)
Location: fs/ext4/ext4.h:1692
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff8142d083)
Location: fs/ext4/ext4.h:1701
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff81480f93)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff81503f0a)
Location: fs/ext4/ext4.h:1767
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
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
In fs/ext4/namei.c (ffffffff8159eaba)
Location: fs/ext4/ext4.h:1777
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
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
In fs/ext4/namei.c (ffffffff815d53ba)
Location: fs/ext4/ext4.h:1772
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
```
In fs/ext4/xattr.c (ffffffff816072b0)
Location: fs/ext4/ext4.h:1772
Inline: True
Inline callers:
  - fs/ext4/xattr.c:check_xattrs
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
In fs/ext4/namei.c (ffffffff8160da5a)
Location: fs/ext4/ext4.h:1791
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
```
In fs/ext4/xattr.c (ffffffff8163fff0)
Location: fs/ext4/ext4.h:1791
Inline: True
Inline callers:
  - fs/ext4/xattr.c:check_xattrs
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
In fs/ext4/namei.c (ffff80001049e510)
Location: fs/ext4/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (c06602d0)
Location: fs/ext4/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (c0000000005c9fb4)
Location: fs/ext4/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffe000320f6c)
Location: fs/ext4/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff813befe0)
Location: fs/ext4/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff813afa70)
Location: fs/ext4/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff813bc570)
Location: fs/ext4/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
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
In fs/ext4/namei.c (ffffffff813d1570)
Location: fs/ext4/ext4.h:1568
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_get_parent
```
</details>
</li>
</ul>

## Differences
