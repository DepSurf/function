# Function: <code>get_cert_list</code>

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
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/modsign_uefi.c (ffffffff81fa9fdc)
Location: kernel/modsign_uefi.c:28
Inline: False
Direct callers:
  - kernel/modsign_uefi.c:load_uefi_certs
  - kernel/modsign_uefi.c:load_uefi_certs
  - kernel/modsign_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff81fa9fdc-ffffffff81faa0c2: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/modsign_uefi.c (ffffffff81fe5fe8)
Location: kernel/modsign_uefi.c:28
Inline: False
Direct callers:
  - kernel/modsign_uefi.c:load_uefi_certs
  - kernel/modsign_uefi.c:load_uefi_certs
  - kernel/modsign_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff81fe5fe8-ffffffff81fe60ce: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff820cd9c2)
Location: certs/load_uefi.c:38
Inline: False
Direct callers:
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff820cd9c2-ffffffff820cdaaf: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff826d63f2)
Location: certs/load_uefi.c:38
Inline: False
Direct callers:
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff826d63f2-ffffffff826d64e5: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, void **cert_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff827009b7)
Location: certs/load_uefi.c:38
Inline: False
Direct callers:
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff827009b7-ffffffff82700b08: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff828b77fc)
Location: certs/load_uefi.c:38
Inline: False
Direct callers:
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
  - certs/load_uefi.c:load_uefi_certs
```
```
In security/integrity/platform_certs/load_uefi.c (ffffffff828cf7e0)
Location: security/integrity/platform_certs/load_uefi.c:41
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828b77fc-ffffffff828b78ef: get_cert_list (STB_LOCAL)
ffffffff828cf7e0-ffffffff828cf91e: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, void **cert_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828e94dc)
Location: security/integrity/platform_certs/load_uefi.c:41
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828e94dc-ffffffff828e961a: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, void **cert_list, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828f1f88)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828f1f88-ffffffff828f20d6: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff82d06fc4)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff82d06fc4-ffffffff82d070e1: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff82ff43f1)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff82ff43f1-ffffffff82ff450e: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff831fefd2)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff831fefd2-ffffffff831ff0ef: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff832e63c4)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff832e63c4-ffffffff832e64e1: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff8349d3c5)
Location: security/integrity/platform_certs/load_uefi.c:64
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff8349d3c5-ffffffff8349d4f6: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff83ed4f50)
Location: security/integrity/platform_certs/load_uefi.c:65
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff83ed4f50-ffffffff83ed509a: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff836fa0b0)
Location: security/integrity/platform_certs/load_uefi.c:65
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff836fa0b0-ffffffff836fa1fa: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff8392d570)
Location: security/integrity/platform_certs/load_uefi.c:65
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff8392d570-ffffffff8392d6ba: get_cert_list (STB_LOCAL)
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
int get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, void **cert_list, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffff80001146c33c)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffff80001146c33c-ffff80001146c4b4: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, void **cert_list, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (c1544fd8)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
c1544fd8-c1545128: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *get_cert_list(u8 *key, long unsigned int keylen, uint64_t *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_powerpc.c (c00000000139b170)
Location: security/integrity/platform_certs/load_powerpc.c:21
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_powerpc.c:load_powerpc_certs
  - security/integrity/platform_certs/load_powerpc.c:load_powerpc_certs
```
**Symbols:**

```
c00000000139b170-c00000000139b28c: get_cert_list (STB_LOCAL)
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
int get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, void **cert_list, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828dae3c)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828dae3c-ffffffff828daf8a: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, void **cert_list, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828d3558)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828d3558-ffffffff828d36a6: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, void **cert_list, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828edbb0)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828edbb0-ffffffff828edcfe: get_cert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_cert_list(efi_char16_t *name, efi_guid_t *guid, long unsigned int *size, void **cert_list, efi_status_t *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828f2fd2)
Location: security/integrity/platform_certs/load_uefi.c:37
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
**Symbols:**

```
ffffffff828f2fd2-ffffffff828f3120: get_cert_list (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void **cert_list</code>
</li>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void **cert_list</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void **cert_list</code>
</li>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>efi_status_t *status</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void **cert_list</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, guid, size, cert_list, status</code> ➡️ <code>name, guid, size, status</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *key</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int keylen</code>
</li>
<li>
<b>Param removed. </b>
<code>efi_char16_t *name</code>
</li>
<li>
<b>Param removed. </b>
<code>efi_guid_t *guid</code>
</li>
<li>
<b>Param removed. </b>
<code>void **cert_list</code>
</li>
<li>
<b>Param removed. </b>
<code>efi_status_t *status</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int *size</code> ➡️ <code>uint64_t *size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
