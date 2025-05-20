# Function: <code>selinux_file</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a6886)
Location: security/selinux/include/objsec.h:165
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cc2d6)
Location: security/selinux/include/objsec.h:169
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141bdcf)
Location: security/selinux/include/objsec.h:166
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff8144976f)
Location: security/selinux/include/objsec.h:163
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff81463307)
Location: security/selinux/include/objsec.h:153
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff814b7640)
Location: security/selinux/include/objsec.h:157
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff814d5320)
Location: security/selinux/include/objsec.h:156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff814dc110)
Location: security/selinux/include/objsec.h:156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff815355a2)
Location: security/selinux/include/objsec.h:156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff815cb942)
Location: security/selinux/include/objsec.h:156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff81678ae2)
Location: security/selinux/include/objsec.h:156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff816b0d22)
Location: security/selinux/include/objsec.h:156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff816edcd2)
Location: security/selinux/include/objsec.h:157
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffff800010551188)
Location: security/selinux/include/objsec.h:153
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (c0703d2c)
Location: security/selinux/include/objsec.h:153
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (c0000000006a7f4c)
Location: security/selinux/include/objsec.h:153
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffe0003aa54a)
Location: security/selinux/include/objsec.h:153
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff8145b8e7)
Location: security/selinux/include/objsec.h:153
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff8144c317)
Location: security/selinux/include/objsec.h:153
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff81457987)
Location: security/selinux/include/objsec.h:153
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
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
In security/selinux/hooks.c (ffffffff8146c8e7)
Location: security/selinux/include/objsec.h:153
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:file_has_perm
```
</details>
</li>
</ul>

## Differences
