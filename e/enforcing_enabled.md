# Function: <code>enforcing_enabled</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:117
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:117
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:117
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:117
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:117
Inline: True
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:117
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:117
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:117
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:117
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:117
Inline: True
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:118
Inline: True
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:118
Inline: True
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
In security/selinux/avc.c (ffffffff814adff4)
Location: security/selinux/include/security.h:140
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_denied
```
```
In security/selinux/hooks.c (ffffffff814b1b51)
Location: security/selinux/include/security.h:140
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/selinux/selinuxfs.c (ffffffff814bb432)
Location: security/selinux/include/security.h:140
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_read_enforce
```
```
In security/selinux/status.c (ffffffff814be4d1)
Location: security/selinux/include/security.h:140
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/selinux/ss/services.c (ffffffff814ccc2a)
Location: security/selinux/include/security.h:140
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_validtrans_handle_fail
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
In security/selinux/avc.c (ffffffff814cba84)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_denied
```
```
In security/selinux/hooks.c (ffffffff814cef41)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/selinux/selinuxfs.c (ffffffff814d8b72)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_read_enforce
```
```
In security/selinux/status.c (ffffffff814dbef1)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/selinux/ss/services.c (ffffffff814ea3e3)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_validtrans_handle_fail
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
In security/selinux/avc.c (ffffffff814d20ac)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_denied
```
```
In security/selinux/hooks.c (ffffffff814d5741)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/selinux/selinuxfs.c (ffffffff814df4f2)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_read_enforce
```
```
In security/selinux/status.c (ffffffff814e2851)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/selinux/ss/services.c (ffffffff814f0fe2)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
```
```
In security/selinux/ima.c (ffffffff814f5e24)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/avc.c (ffffffff8152ae89)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_denied
```
```
In security/selinux/hooks.c (ffffffff8152e381)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/selinux/selinuxfs.c (ffffffff815384f2)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_read_enforce
```
```
In security/selinux/status.c (ffffffff8153ba02)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/selinux/ss/services.c (ffffffff8154b5d6)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ima.c (ffffffff815508f3)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/avc.c (ffffffff815c0649)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_denied
```
```
In security/selinux/hooks.c (ffffffff815c4f8e)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/selinux/selinuxfs.c (ffffffff815cfc70)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_read_enforce
```
```
In security/selinux/status.c (ffffffff815d324a)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/selinux/ss/services.c (ffffffff815e43f0)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ima.c (ffffffff815e9da3)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/avc.c (ffffffff8166cba9)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_denied
```
```
In security/selinux/hooks.c (ffffffff81671abd)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/selinux/selinuxfs.c (ffffffff8167d750)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_read_enforce
```
```
In security/selinux/status.c (ffffffff8168125a)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/selinux/ss/services.c (ffffffff81693692)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ima.c (ffffffff81699738)
Location: security/selinux/include/security.h:129
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/avc.c (ffffffff816a53b6)
Location: security/selinux/include/security.h:124
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_denied
```
```
In security/selinux/hooks.c (ffffffff816aa29a)
Location: security/selinux/include/security.h:124
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/selinux/selinuxfs.c (ffffffff816b5822)
Location: security/selinux/include/security.h:124
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_read_enforce
```
```
In security/selinux/status.c (ffffffff816b9308)
Location: security/selinux/include/security.h:124
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/selinux/ss/services.c (ffffffff816cbba1)
Location: security/selinux/include/security.h:124
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ima.c (ffffffff816d1c9e)
Location: security/selinux/include/security.h:124
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/avc.c (ffffffff816e1df6)
Location: security/selinux/include/security.h:123
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_denied
```
```
In security/selinux/hooks.c (ffffffff816e709a)
Location: security/selinux/include/security.h:123
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/selinux/selinuxfs.c (ffffffff816f2393)
Location: security/selinux/include/security.h:123
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_read_enforce
```
```
In security/selinux/status.c (ffffffff816f5db8)
Location: security/selinux/include/security.h:123
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/selinux/ss/services.c (ffffffff81708861)
Location: security/selinux/include/security.h:123
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ima.c (ffffffff8170e30e)
Location: security/selinux/include/security.h:123
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:118
Inline: True
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
In security/selinux/avc.c (c06fd15c)
Location: security/selinux/include/security.h:118
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_denied
```
```
In security/selinux/hooks.c (c0701e58)
Location: security/selinux/include/security.h:118
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/selinux/selinuxfs.c (c070b730)
Location: security/selinux/include/security.h:118
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_read_enforce
```
```
In security/selinux/ss/services.c (c071ba28)
Location: security/selinux/include/security.h:118
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
```
```
In security/selinux/ss/status.c (c071eddc)
Location: security/selinux/include/security.h:118
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:118
Inline: True
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:118
Inline: True
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:118
Inline: True
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:118
Inline: True
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:118
Inline: True
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
In security/selinux/avc.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: security/selinux/include/security.h:118
Inline: True
```
</details>
</li>
</ul>

## Differences
