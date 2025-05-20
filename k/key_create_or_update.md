# Function: <code>key_create_or_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813303b0)
Location: security/keys/key.c:773
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - security/keys/keyctl.c:SyS_add_key
  - security/integrity/digsig.c:integrity_load_x509
```
**Symbols:**

```
ffffffff813303b0-ffffffff8133080a: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81365100)
Location: security/keys/key.c:792
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - security/keys/keyctl.c:SyS_add_key
  - security/integrity/digsig.c:integrity_load_x509
  - crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list
```
**Symbols:**

```
ffffffff81365100-ffffffff81365569: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137b920)
Location: security/keys/key.c:792
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - security/keys/keyctl.c:SyS_add_key
  - security/integrity/digsig.c:integrity_load_x509
  - crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list
```
**Symbols:**

```
ffffffff8137b920-ffffffff8137bd89: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138f4c0)
Location: security/keys/key.c:794
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:SyS_add_key
  - security/integrity/digsig.c:integrity_load_x509
```
**Symbols:**

```
ffffffff8138f4c0-ffffffff8138f912: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b49f0)
Location: security/keys/key.c:800
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:SyS_add_key
  - security/integrity/digsig.c:integrity_load_x509
```
**Symbols:**

```
ffffffff813b49f0-ffffffff813b4e91: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813e51d0)
Location: security/keys/key.c:800
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/integrity/digsig.c:integrity_load_x509
```
**Symbols:**

```
ffffffff813e51d0-ffffffff813e5686: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813ff9a0)
Location: security/keys/key.c:801
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff813ff9a0-ffffffff813ffe56: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142c0b0)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff8142c0b0-ffffffff8142c543: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81445e00)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff81445e00-ffffffff81446293: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81497090)
Location: security/keys/key.c:813
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__do_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff81497090-ffffffff8149761d: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b4b10)
Location: security/keys/key.c:816
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__do_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff814b4b10-ffffffff814b50c9: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814ba960)
Location: security/keys/key.c:816
Inline: False
Direct callers:
  - certs/common.c:load_certificate_list
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__do_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff814ba960-ffffffff814baf16: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81513190)
Location: security/keys/key.c:816
Inline: False
Direct callers:
  - certs/common.c:load_certificate_list
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__do_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff81513190-ffffffff81513746: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff815a55c0)
Location: security/keys/key.c:816
Inline: False
Direct callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__do_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
**Symbols:**

```
ffffffff815a55c0-ffffffff815a5bcf: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8164f3c0)
Location: security/keys/key.c:816
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__do_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
**Symbols:**

```
ffffffff8164f3c0-ffffffff8164f9cf: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81688240)
Location: security/keys/key.c:1003
Inline: False
Direct callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - security/keys/keyctl.c:__do_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
**Symbols:**

```
ffffffff81688240-ffffffff81688267: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c4760)
Location: security/keys/key.c:999
Inline: False
Direct callers:
  - certs/system_keyring.c:add_to_secondary_keyring
  - certs/blacklist.c:add_key_to_revocation_list
  - security/keys/keyctl.c:__do_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
  - block/sed-opal.c:sed_opal_init
  - block/sed-opal.c:sed_ioctl
```
**Symbols:**

```
ffffffff816c4760-ffffffff816c4787: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffff80001052f070)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__arm64_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffff80001052f070-ffff80001052f430: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c06e7350)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__se_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
c06e7350-c06e7780: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c00000000067bc70)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__se_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
c00000000067bc70-c00000000067c194: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffe0003908d8)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__se_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffe0003908d8-ffffffe000390c22: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143e3e0)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff8143e3e0-ffffffff8143e873: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142ee50)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff8142ee50-ffffffff8142f2e3: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143a580)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff8143a580-ffffffff8143aa13: key_create_or_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char *type, const char *description, const void *payload, size_t plen, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814516c0)
Location: security/keys/key.c:808
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:mark_hash_blacklisted
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/integrity/digsig.c:integrity_add_key
```
**Symbols:**

```
ffffffff814516c0-ffffffff81451b53: key_create_or_update (STB_GLOBAL)
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
