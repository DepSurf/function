# Function: <code>parse_efi_signature_list</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int parse_efi_signature_list(const void *data, size_t size, struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/efi_parser.c (ffffffff81fc57f2)
Location: crypto/asymmetric_keys/efi_parser.c:27
Inline: False
Direct callers:
  - kernel/modsign_uefi.c:load_uefi_certs
  - kernel/modsign_uefi.c:load_uefi_certs
  - kernel/modsign_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff81fc57f2-ffffffff81fc59d6: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int parse_efi_signature_list(const void *data, size_t size, struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/efi_parser.c (ffffffff82002202)
Location: crypto/asymmetric_keys/efi_parser.c:27
Inline: False
Direct callers:
  - kernel/modsign_uefi.c:load_uefi_certs
  - kernel/modsign_uefi.c:load_uefi_certs
  - kernel/modsign_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff82002202-ffffffff820023e6: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/efi_parser.c (ffffffff820cd87e)
Location: certs/efi_parser.c:41
Inline: False
Direct callers:
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff820cd87e-ffffffff820cd9c2: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/efi_parser.c (ffffffff826d62ae)
Location: certs/efi_parser.c:41
Inline: False
Direct callers:
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff826d62ae-ffffffff826d63f2: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/efi_parser.c (ffffffff82700663)
Location: certs/efi_parser.c:41
Inline: False
Direct callers:
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff82700663-ffffffff827007a9: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/efi_parser.c (ffffffff828b76b6)
Location: certs/efi_parser.c:37
Inline: False
Direct callers:
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828b76b6-ffffffff828b77fc: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff828e9242)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828e9242-ffffffff828e939b: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff828f1e2f)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828f1e2f-ffffffff828f1f88: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff82d06e86)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff82d06e86-ffffffff82d06fc4: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff82ff42b3)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff82ff42b3-ffffffff82ff43f1: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff831fee74)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff831fee74-ffffffff831fefd2: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff832e6266)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff832e6266-ffffffff832e63c4: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff8349d275)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff8349d275-ffffffff8349d3c5: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff83ed4dc0)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff83ed4dc0-ffffffff83ed4f33: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff836f9f20)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff836f9f20-ffffffff836fa093: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff8392d3e0)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff8392d3e0-ffffffff8392d553: parse_efi_signature_list (STB_GLOBAL)
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
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffff80001146c1dc)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffff80001146c1dc-ffff80001146c33c: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (c1544e6c)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
c1544e6c-c1544fd8: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (c00000000139afc4)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_powerpc.c:load_powerpc_certs
  - security/integrity/platform_certs/load_powerpc.c:load_powerpc_certs
```
**Symbols:**

```
c00000000139afc4-c00000000139b170: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff828dace3)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828dace3-ffffffff828dae3c: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff828d33ff)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828d33ff-ffffffff828d3558: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff828eda57)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828eda57-ffffffff828edbb0: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_efi_signature_list(const char *source, const void *data, size_t size, efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/efi_parser.c (ffffffff828f2e79)
Location: security/integrity/platform_certs/efi_parser.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828f2e79-ffffffff828f2fd2: parse_efi_signature_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *source</code>
</li>
<li>
<b>Param added. </b>
<code>efi_element_handler_t (*get_handler_for_guid)(const efi_guid_t *)</code>
</li>
<li>
<b>Param removed. </b>
<code>struct key *keyring</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, size, keyring</code> ➡️ <code>source, data, size, get_handler_for_guid</code>
</li>
</ul>
</details>
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
