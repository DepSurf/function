# Function: <code>audit_inode</code>

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
In fs/namei.c (ffffffff8121a9ec)
Location: include/linux/audit.h:183
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_mountpoint
```
```
In ipc/mqueue.c (ffffffff8132d2c1)
Location: include/linux/audit.h:183
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
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
In fs/namei.c (ffffffff81241d90)
Location: include/linux/audit.h:286
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
```
In ipc/mqueue.c (ffffffff81361f39)
Location: include/linux/audit.h:286
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
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
In fs/namei.c (ffffffff81254c71)
Location: include/linux/audit.h:286
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
```
In ipc/mqueue.c (ffffffff81378739)
Location: include/linux/audit.h:286
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
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
In fs/namei.c (ffffffff81260cbf)
Location: include/linux/audit.h:285
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
```
In ipc/mqueue.c (ffffffff8138cbc9)
Location: include/linux/audit.h:285
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff81283514)
Location: include/linux/audit.h:277
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
```
In ipc/mqueue.c (ffffffff813b1f79)
Location: include/linux/audit.h:277
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff812aa66a)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffffffff813e07ba)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff812bf804)
Location: include/linux/audit.h:286
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffffffff813fafaa)
Location: include/linux/audit.h:286
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff812dd3cc)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffffffff81427347)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff812eeedc)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffffffff81441077)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff81326488)
Location: include/linux/audit.h:346
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
```
```
In ipc/mqueue.c (ffffffff81491e47)
Location: include/linux/audit.h:346
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff81331928)
Location: include/linux/audit.h:363
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
```
```
In ipc/mqueue.c (ffffffff814af4a7)
Location: include/linux/audit.h:363
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff813382f9)
Location: include/linux/audit.h:363
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
```
```
In ipc/mqueue.c (ffffffff814b52e6)
Location: include/linux/audit.h:363
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff81385d59)
Location: include/linux/audit.h:363
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
```
```
In ipc/mqueue.c (ffffffff8150d9a6)
Location: include/linux/audit.h:363
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff81406c0f)
Location: include/linux/audit.h:389
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
```
```
In ipc/mqueue.c (ffffffff815a03d7)
Location: include/linux/audit.h:389
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff81490fec)
Location: include/linux/audit.h:386
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
```
```
In ipc/mqueue.c (ffffffff81649d37)
Location: include/linux/audit.h:386
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff814c67f1)
Location: include/linux/audit.h:385
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:__filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
```
```
In ipc/mqueue.c (ffffffff81682297)
Location: include/linux/audit.h:385
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff814f90e1)
Location: include/linux/audit.h:384
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:__filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
```
```
In ipc/mqueue.c (ffffffff816be697)
Location: include/linux/audit.h:384
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffff80001039875c)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffff800010529520)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (c057ed34)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (c06e4848)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_open
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
In fs/namei.c (c000000000492a58)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (c000000000675e60)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffe000266358)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffffffe00038d9ac)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_open
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
In fs/namei.c (ffffffff812e74bc)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffffffff81439657)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff812d80fc)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffffffff8142a0c7)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff812e52cc)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffffffff814357f7)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
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
In fs/namei.c (ffffffff812f624c)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
```
```
In ipc/mqueue.c (ffffffff8144d837)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
</details>
</li>
</ul>

## Differences
