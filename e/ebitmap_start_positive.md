# Function: <code>ebitmap_start_positive</code>

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
In security/selinux/ss/ebitmap.c (ffffffff8134e099)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff813518b2)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81356f97)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/selinux/ss/mls.c (ffffffff8135b891)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_convert_context
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
In security/selinux/ss/ebitmap.c (ffffffff813840b9)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81387aa8)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8138e8e0)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff81392504)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff8139ab49)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff8139df68)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813a5500)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff813a9134)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff813b120c)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff813b3f08)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813bbfb8)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff813bfbd3)
Location: security/selinux/ss/ebitmap.h:46
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff813d72fc)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff813da058)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813e2128)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff813e5d73)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff814078ef)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff8140a3d8)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81412efd)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff81416975)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff8142343f)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81426688)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8142f444)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff81432e8d)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff81450fcc)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff814542e3)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8145cdf5)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814608c9)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff8146adac)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff8146e083)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81476ba5)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8147a679)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff814bf256)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff814c2a57)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814cc207)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814cfc28)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff814dcc76)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff814e0587)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814e95f1)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814ed158)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff814e35b6)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff814e7d87)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814f0164)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814f3ef8)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff8153c9a6)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff815416c7)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8154a6ce)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8154e8a1)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff815d4335)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff815d982e)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff815e33eb)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff815e797d)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff81682475)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff8168760e)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8169265d)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8169706d)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff816ba5f5)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816bf9df)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff816cabca)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff816cf57c)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff816f7085)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816fc21f)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81707809)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8170bb9c)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffff800010559b44)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffff80001055d158)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffff80001056680c)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffff80001056ac28)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (c070e394)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (c0711a24)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (c071addc)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (c071e7d8)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (c0000000006b7dac)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (c0000000006bcd04)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (c0000000006c9460)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (c0000000006ce8bc)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffe0003b0b9a)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffe0003b56d4)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffe0003bc7ca)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffe0003bfa7e)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff8146338c)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81466663)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8146f185)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff81472c59)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff81453dbc)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81457093)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8145fba5)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff81463679)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff8145f42c)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81462703)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8146b225)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8146ecf9)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff81476c3c)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81479f03)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814829b7)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff81486569)
Location: security/selinux/ss/ebitmap.h:47
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
</ul>

## Differences
