# Function: <code>sym_name</code>

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
In security/selinux/ss/policydb.c (ffffffff813513b2)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81355202)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
```
```
In security/selinux/ss/mls.c (ffffffff8135b86f)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_convert_context
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
In security/selinux/ss/policydb.c (ffffffff81387b94)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813908ac)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff813925b1)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff8139e054)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813a74cc)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff813a91e1)
Location: security/selinux/ss/policydb.h:359
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff813b3ff4)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813bdeaa)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff813bfc2a)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff813da144)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff813e404a)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff813e5dca)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff8140a48b)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8141486d)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff814169b1)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff8142673b)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81430e50)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff81432ecb)
Location: security/selinux/ss/policydb.h:370
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff81458747)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8145e870)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff81460907)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff814724e7)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81478620)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff8147a6b7)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff814c76a1)
Location: security/selinux/ss/policydb.h:371
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:type_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814cdb09)
Location: security/selinux/ss/policydb.h:371
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:security_validtrans_handle_fail
```
```
In security/selinux/ss/mls.c (ffffffff814cfc6d)
Location: security/selinux/ss/policydb.h:371
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff81bf08aa)
Location: security/selinux/ss/policydb.h:380
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:type_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814eb141)
Location: security/selinux/ss/policydb.h:380
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:security_validtrans_handle_fail
```
```
In security/selinux/ss/mls.c (ffffffff814ed19d)
Location: security/selinux/ss/policydb.h:380
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff81be29f7)
Location: security/selinux/ss/policydb.h:380
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:type_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814f1e11)
Location: security/selinux/ss/policydb.h:380
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
```
```
In security/selinux/ss/mls.c (ffffffff814f3f3d)
Location: security/selinux/ss/policydb.h:380
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff81cd4534)
Location: security/selinux/ss/policydb.h:380
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:type_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8154c504)
Location: security/selinux/ss/policydb.h:380
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
```
```
In security/selinux/ss/mls.c (ffffffff8154e8e3)
Location: security/selinux/ss/policydb.h:380
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff81e8745c)
Location: security/selinux/ss/policydb.h:382
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:type_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff815e53b4)
Location: security/selinux/ss/policydb.h:382
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
```
```
In security/selinux/ss/mls.c (ffffffff815e79cc)
Location: security/selinux/ss/policydb.h:382
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff816865a4)
Location: security/selinux/ss/policydb.h:382
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:type_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81694814)
Location: security/selinux/ss/policydb.h:382
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
```
```
In security/selinux/ss/mls.c (ffffffff816970bc)
Location: security/selinux/ss/policydb.h:382
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff816be914)
Location: security/selinux/ss/policydb.h:382
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:type_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff816ccd16)
Location: security/selinux/ss/policydb.h:382
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
```
```
In security/selinux/ss/mls.c (ffffffff816cf5cb)
Location: security/selinux/ss/policydb.h:382
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff816fb134)
Location: security/selinux/ss/policydb.h:385
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:type_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81709316)
Location: security/selinux/ss/policydb.h:385
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
  - security/selinux/ss/services.c:context_struct_to_string
```
```
In security/selinux/ss/mls.c (ffffffff8170bbeb)
Location: security/selinux/ss/policydb.h:385
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffff80001055d278)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffff80001056874c)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffff80001056ac68)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (c0711b14)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (c071c9c4)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
```
```
In security/selinux/ss/mls.c (c071e820)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (c0000000006bc658)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:type_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (c0000000006cbdec)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (c0000000006ce918)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffe0003b57e8)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffe0003bdf02)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffe0003bfade)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff8146aac7)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81470c00)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff81472c97)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff8145b4f7)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff81461620)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff814636b7)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff81466b67)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff8146cca0)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff8146ed37)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
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
In security/selinux/ss/policydb.c (ffffffff8147e347)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
```
```
In security/selinux/ss/services.c (ffffffff814844db)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
```
In security/selinux/ss/mls.c (ffffffff814865a7)
Location: security/selinux/ss/policydb.h:366
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
```
</details>
</li>
</ul>

## Differences
