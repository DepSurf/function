# Function: <code>audit_file</code>

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
In fs/open.c (ffffffff8120aea9)
Location: include/linux/audit.h:193
Inline: True
Inline callers:
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fchown
```
```
In fs/xattr.c (ffffffff81232ee8)
Location: include/linux/audit.h:193
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fremovexattr
```
```
In ipc/mqueue.c (ffffffff8132d742)
Location: include/linux/audit.h:193
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
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
In fs/open.c (ffffffff8123105c)
Location: include/linux/audit.h:296
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
```
```
In fs/xattr.c (ffffffff8125b834)
Location: include/linux/audit.h:296
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In ipc/mqueue.c (ffffffff81362719)
Location: include/linux/audit.h:296
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
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
In fs/open.c (ffffffff8124360c)
Location: include/linux/audit.h:296
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
```
```
In fs/xattr.c (ffffffff8126ede4)
Location: include/linux/audit.h:296
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In ipc/mqueue.c (ffffffff81378f09)
Location: include/linux/audit.h:296
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
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
In fs/open.c (ffffffff8124ed50)
Location: include/linux/audit.h:295
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
```
```
In fs/xattr.c (ffffffff8127c5f4)
Location: include/linux/audit.h:295
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In ipc/mqueue.c (ffffffff8138c61f)
Location: include/linux/audit.h:295
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff81270cd0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
```
```
In fs/xattr.c (ffffffff8129f094)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In ipc/mqueue.c (ffffffff813b19cf)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff8129693b)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffff812c53e9)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff813e2523)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff812ab72b)
Location: include/linux/audit.h:296
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffff812da5e9)
Location: include/linux/audit.h:296
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff813fcf73)
Location: include/linux/audit.h:296
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff812c7f2b)
Location: include/linux/audit.h:342
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffff812f8bb9)
Location: include/linux/audit.h:342
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff814295bd)
Location: include/linux/audit.h:342
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff812d993b)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffff8130a7e9)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff814432ed)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff8130f6fb)
Location: include/linux/audit.h:352
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffff813437e9)
Location: include/linux/audit.h:352
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff81493f7d)
Location: include/linux/audit.h:352
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff8131b9ab)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/xattr.c (ffffffff8134ffa9)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff814b18dd)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff81321afb)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/xattr.c (ffffffff81356a58)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff814b775d)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff8136efdb)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/xattr.c (ffffffff813a5438)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff815100cd)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff813ed95c)
Location: include/linux/audit.h:395
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/xattr.c (ffffffff81428a80)
Location: include/linux/audit.h:395
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff815a21a7)
Location: include/linux/audit.h:395
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff8147607c)
Location: include/linux/audit.h:392
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/xattr.c (ffffffff814b60e0)
Location: include/linux/audit.h:392
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff8164bc77)
Location: include/linux/audit.h:392
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff814aa99c)
Location: include/linux/audit.h:391
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/xattr.c (ffffffff814ea910)
Location: include/linux/audit.h:391
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff816843b1)
Location: include/linux/audit.h:391
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff814dbe3c)
Location: include/linux/audit.h:390
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/xattr.c (ffffffff8151e7b0)
Location: include/linux/audit.h:390
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff816c07d8)
Location: include/linux/audit.h:390
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffff80001037ec88)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffff8000103be264)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/xattr.c:__arm64_sys_fremovexattr
  - fs/xattr.c:__arm64_sys_flistxattr
  - fs/xattr.c:__arm64_sys_fgetxattr
  - fs/xattr.c:__arm64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffff80001052af80)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (c05695b4)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (c059c2b8)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In ipc/mqueue.c (c06e32ac)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (c0000000004749d0)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (c0000000004bcdd8)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In ipc/mqueue.c (c000000000676738)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffe0002548e2)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffe00027fdfc)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffe00038e06a)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
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
In fs/open.c (ffffffff812d1f1b)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffff81302dc9)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff8143b8cd)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff812c2b9b)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffff812f39e9)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff8142c33d)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff812cfd2b)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffff81300bb9)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff81437a6d)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In fs/open.c (ffffffff812e0b3b)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/xattr.c (ffffffff81311ef9)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In ipc/mqueue.c (ffffffff8144dfed)
Location: include/linux/audit.h:335
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
</ul>

## Differences
