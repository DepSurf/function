# Function: <code>asymmetric_key_id_same</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff813ac2f0)
Location: crypto/asymmetric_keys/asymmetric_type.c:68
Inline: True
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/x509_public_key.c:x509_request_asymmetric_key
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff813ac2f0-ffffffff813ac329: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff813f000d)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff813f0300-ffffffff813f0336: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8140988d)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff81409b80-ffffffff81409bb6: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81416dec)
Location: crypto/asymmetric_keys/asymmetric_type.c:158
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:match_either_id
  - crypto/asymmetric_keys/restrict.c:match_either_id
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff81416cc0-ffffffff81416ce8: asymmetric_key_id_same.part.4 (STB_LOCAL)
ffffffff81416cf0-ffffffff81416d0d: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81441827)
Location: crypto/asymmetric_keys/asymmetric_type.c:160
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:match_either_id
  - crypto/asymmetric_keys/restrict.c:match_either_id
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814416f0-ffffffff81441718: asymmetric_key_id_same.part.4 (STB_LOCAL)
ffffffff81441720-ffffffff8144173d: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81474724)
Location: crypto/asymmetric_keys/asymmetric_type.c:160
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814745a0-ffffffff814745c8: asymmetric_key_id_same.part.5 (STB_LOCAL)
ffffffff814745d0-ffffffff814745ed: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81492364)
Location: crypto/asymmetric_keys/asymmetric_type.c:161
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814921e0-ffffffff81492208: asymmetric_key_id_same.part.5 (STB_LOCAL)
ffffffff81492210-ffffffff8149222d: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814c0023)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814bf810-ffffffff814bf838: asymmetric_key_id_same.part.0 (STB_LOCAL)
ffffffff814bf840-ffffffff814bf85d: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d8e73)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814d8660-ffffffff814d8688: asymmetric_key_id_same.part.0 (STB_LOCAL)
ffffffff814d8690-ffffffff814d86ad: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff815387a0)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
**Symbols:**

```
ffffffff81537fc0-ffffffff81537ff9: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81555600)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
**Symbols:**

```
ffffffff81554e20-ffffffff81554e59: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8155db20)
Location: crypto/asymmetric_keys/asymmetric_type.c:158
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
**Symbols:**

```
ffffffff8155d590-ffffffff8155d5c9: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff815bee30)
Location: crypto/asymmetric_keys/asymmetric_type.c:158
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
**Symbols:**

```
ffffffff815be8b0-ffffffff815be8e9: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81668d57)
Location: crypto/asymmetric_keys/asymmetric_type.c:171
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp_name
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
**Symbols:**

```
ffffffff81668200-ffffffff81668257: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81723567)
Location: crypto/asymmetric_keys/asymmetric_type.c:171
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp_name
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
**Symbols:**

```
ffffffff817228a0-ffffffff817228f7: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8175ebd0)
Location: crypto/asymmetric_keys/asymmetric_type.c:170
Inline: False
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp_name
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
**Symbols:**

```
ffffffff8175ebd0-ffffffff8175ec27: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff817a03c0)
Location: crypto/asymmetric_keys/asymmetric_type.c:170
Inline: False
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp_name
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
**Symbols:**

```
ffffffff817a03c0-ffffffff817a0417: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffff8000105d49b4)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffff8000105d45a0-ffff8000105d4600: asymmetric_key_id_same.part.0 (STB_LOCAL)
ffff8000105d4600-ffff8000105d4648: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (c0782330)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:match_either_id
  - crypto/asymmetric_keys/restrict.c:match_either_id
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
**Symbols:**

```
c0782024-c0782068: asymmetric_key_id_same.part.0 (STB_LOCAL)
c0782068-c0782098: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (c000000000763034)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
c000000000761f60-c000000000761fc8: asymmetric_key_id_same.part.0 (STB_LOCAL)
c000000000761fd0-c000000000762008: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffe000418cbe)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffe000419270-ffffffe0004192d8: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d1453)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814d0c40-ffffffff814d0c68: asymmetric_key_id_same.part.0 (STB_LOCAL)
ffffffff814d0c70-ffffffff814d0c8d: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814c1e73)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814c1660-ffffffff814c1688: asymmetric_key_id_same.part.0 (STB_LOCAL)
ffffffff814c1690-ffffffff814c16ad: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814cd4e3)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814cccd0-ffffffff814cccf8: asymmetric_key_id_same.part.0 (STB_LOCAL)
ffffffff814ccd00-ffffffff814ccd1d: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id *kid1, const struct asymmetric_key_id *kid2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814e5fb3)
Location: crypto/asymmetric_keys/asymmetric_type.c:157
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
Direct callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814e57a0-ffffffff814e57c8: asymmetric_key_id_same.part.0 (STB_LOCAL)
ffffffff814e57d0-ffffffff814e57ed: asymmetric_key_id_same (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
