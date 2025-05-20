# Function: <code>ebitmap_next_positive</code>

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
In security/selinux/ss/ebitmap.c (ffffffff8134e0f2)
Location: security/selinux/ss/ebitmap.h:64
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81351871)
Location: security/selinux/ss/ebitmap.h:64
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81356fcb)
Location: security/selinux/ss/ebitmap.h:64
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
In security/selinux/ss/mls.c (ffffffff8135b92b)
Location: security/selinux/ss/ebitmap.h:64
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
In security/selinux/ss/ebitmap.c (ffffffff8138412e)
Location: security/selinux/ss/ebitmap.h:64
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81387b0e)
Location: security/selinux/ss/ebitmap.h:64
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8138e9de)
Location: security/selinux/ss/ebitmap.h:64
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
In security/selinux/ss/mls.c (ffffffff813925f5)
Location: security/selinux/ss/ebitmap.h:64
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
In security/selinux/ss/ebitmap.c (ffffffff8139abbe)
Location: security/selinux/ss/ebitmap.h:64
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff8139dfce)
Location: security/selinux/ss/ebitmap.h:64
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813a55fe)
Location: security/selinux/ss/ebitmap.h:64
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
In security/selinux/ss/mls.c (ffffffff813a9225)
Location: security/selinux/ss/ebitmap.h:64
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
In security/selinux/ss/ebitmap.c (ffffffff813b1283)
Location: security/selinux/ss/ebitmap.h:64
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff813b3f6e)
Location: security/selinux/ss/ebitmap.h:64
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813bc1d3)
Location: security/selinux/ss/ebitmap.h:64
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
In security/selinux/ss/mls.c (ffffffff813bfc69)
Location: security/selinux/ss/ebitmap.h:64
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
In security/selinux/ss/ebitmap.c (ffffffff813d7373)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff813da0be)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813e2343)
Location: security/selinux/ss/ebitmap.h:65
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
In security/selinux/ss/mls.c (ffffffff813e5e09)
Location: security/selinux/ss/ebitmap.h:65
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
In security/selinux/ss/ebitmap.c (ffffffff81407961)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff8140a42b)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81413051)
Location: security/selinux/ss/ebitmap.h:65
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
In security/selinux/ss/mls.c (ffffffff814169f5)
Location: security/selinux/ss/ebitmap.h:65
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
In security/selinux/ss/ebitmap.c (ffffffff814234b1)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff814266db)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8142f598)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff81432f05)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff81451041)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81454361)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8145cf45)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8146093d)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff8146ae21)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff8146e101)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81476cf5)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8147a6ed)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff814bf2c9)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff814c2b27)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814cc362)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814cfca2)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff814dcce9)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff814e0657)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814e974d)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814ed1d2)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff814e3629)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff814e7e54)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814f02a8)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814f3f72)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff8153ca19)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff81541794)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8154a812)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8154e918)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff815d43a5)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff815d992e)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff815e3536)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff815e7a01)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff816824e5)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816876ef)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff816927a8)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff816970f1)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff816ba666)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816bfa9f)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff816cad11)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff816cf600)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff816f70f6)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_and
```
```
In security/selinux/ss/policydb.c (ffffffff816fc2e1)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81707950)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8170bc20)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffff800010559bb4)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffff80001055d1f0)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffff800010566908)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffff80001056ac94)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (c070e414)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (c0711ab8)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (c071af00)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (c071e854)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (c0000000006b7e44)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (c0000000006bcdf4)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (c0000000006c95c4)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (c0000000006ce95c)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffe0003b0bd0)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffe0003b5774)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffe0003bc8d0)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffe0003bface)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff81463401)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff814666e1)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8146f2d5)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff81472ccd)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff81453e31)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81457111)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8145fcf5)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814636ed)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff8145f4a1)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81462781)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8146b375)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff8146ed6d)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/ebitmap.c (ffffffff81476cb1)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
```
```
In security/selinux/ss/policydb.c (ffffffff81479f81)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81482b08)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
```
```
In security/selinux/ss/mls.c (ffffffff814865dd)
Location: security/selinux/ss/ebitmap.h:65
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
</ul>

## Differences
