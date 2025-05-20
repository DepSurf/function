# Function: <code>flex_array_get_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *flex_array_get_ptr(struct flex_array *fa, unsigned int element_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff813fad40)
Location: lib/flex_array.c:345
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_insertf
  - security/selinux/ss/avtab.c:avtab_insert_nonunique
  - security/selinux/ss/avtab.c:avtab_search
  - security/selinux/ss/avtab.c:avtab_search_node
  - security/selinux/ss/avtab.c:avtab_destroy
  - security/selinux/ss/avtab.c:avtab_hash_eval
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
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
**Symbols:**

```
ffffffff813fad40-ffffffff813fad57: flex_array_get_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *flex_array_get_ptr(struct flex_array *fa, unsigned int element_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff81441f60)
Location: lib/flex_array.c:345
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_insertf
  - security/selinux/ss/avtab.c:avtab_hash_eval
  - security/selinux/ss/avtab.c:avtab_destroy
  - security/selinux/ss/avtab.c:avtab_search_node
  - security/selinux/ss/avtab.c:avtab_search
  - security/selinux/ss/avtab.c:avtab_insert_nonunique
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
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
**Symbols:**

```
ffffffff81441f60-ffffffff81441f77: flex_array_get_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *flex_array_get_ptr(struct flex_array *fa, unsigned int element_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff8145f170)
Location: lib/flex_array.c:345
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_insertf
  - security/selinux/ss/avtab.c:avtab_hash_eval
  - security/selinux/ss/avtab.c:avtab_destroy
  - security/selinux/ss/avtab.c:avtab_search_node
  - security/selinux/ss/avtab.c:avtab_search
  - security/selinux/ss/avtab.c:avtab_insert_nonunique
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
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
**Symbols:**

```
ffffffff8145f170-ffffffff8145f187: flex_array_get_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *flex_array_get_ptr(struct flex_array *fa, unsigned int element_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff814644b0)
Location: lib/flex_array.c:345
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_insertf
  - security/selinux/ss/avtab.c:avtab_hash_eval
  - security/selinux/ss/avtab.c:avtab_search_node
  - security/selinux/ss/avtab.c:avtab_search
  - security/selinux/ss/avtab.c:avtab_insert_nonunique
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
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
**Symbols:**

```
ffffffff814644b0-ffffffff814644c7: flex_array_get_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *flex_array_get_ptr(struct flex_array *fa, unsigned int element_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff81490430)
Location: lib/flex_array.c:345
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_insertf
  - security/selinux/ss/avtab.c:avtab_hash_eval
  - security/selinux/ss/avtab.c:avtab_search_node
  - security/selinux/ss/avtab.c:avtab_search
  - security/selinux/ss/avtab.c:avtab_insert_nonunique
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
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
**Symbols:**

```
ffffffff81490430-ffffffff81490447: flex_array_get_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *flex_array_get_ptr(struct flex_array *fa, unsigned int element_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff814c5230)
Location: lib/flex_array.c:345
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_insertf
  - security/selinux/ss/avtab.c:avtab_hash_eval
  - security/selinux/ss/avtab.c:avtab_search_node
  - security/selinux/ss/avtab.c:avtab_search
  - security/selinux/ss/avtab.c:avtab_insert_nonunique
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
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
**Symbols:**

```
ffffffff814c5230-ffffffff814c5247: flex_array_get_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *flex_array_get_ptr(struct flex_array *fa, unsigned int element_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff814d9930)
Location: lib/flex_array.c:345
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_write
  - security/selinux/ss/avtab.c:avtab_insertf
  - security/selinux/ss/avtab.c:avtab_hash_eval
  - security/selinux/ss/avtab.c:avtab_search_node
  - security/selinux/ss/avtab.c:avtab_search
  - security/selinux/ss/avtab.c:avtab_insert_nonunique
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:type_attribute_bounds_av
  - security/selinux/ss/services.c:type_attribute_bounds_av
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
**Symbols:**

```
ffffffff814d9930-ffffffff814d9943: flex_array_get_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
