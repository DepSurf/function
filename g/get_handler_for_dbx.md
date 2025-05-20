# Function: <code>get_handler_for_dbx</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff820cde1f)
Location: certs/load_uefi.c:126
Inline: True
```
**Symbols:**

```
ffffffff820cde1f-ffffffff820cdef9: get_handler_for_dbx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff826d6855)
Location: certs/load_uefi.c:126
Inline: True
```
**Symbols:**

```
ffffffff826d6855-ffffffff826d692f: get_handler_for_dbx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff827008fb)
Location: certs/load_uefi.c:135
Inline: False
```
**Symbols:**

```
ffffffff827008fb-ffffffff827009b7: get_handler_for_dbx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff828b7c51)
Location: certs/load_uefi.c:126
Inline: False
```
```
In security/integrity/platform_certs/load_uefi.c (ffffffff828cf724)
Location: security/integrity/platform_certs/load_uefi.c:135
Inline: False
```
**Symbols:**

```
ffffffff828b7c51-ffffffff828b7d0d: get_handler_for_dbx (STB_LOCAL)
ffffffff828cf724-ffffffff828cf7e0: get_handler_for_dbx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828e941f)
Location: security/integrity/platform_certs/load_uefi.c:135
Inline: False
```
**Symbols:**

```
ffffffff828e941f-ffffffff828e94dc: get_handler_for_dbx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f24e2)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
ffffffff828f24e2-ffffffff828f259f: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82d0749c)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
ffffffff82d0749c-ffffffff82d07553: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82ff495b)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
ffffffff82ff495b-ffffffff82ff4a12: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff831ff620)
Location: security/integrity/platform_certs/keyring_handler.c:83
Inline: False
```
**Symbols:**

```
ffffffff831ff620-ffffffff831ff714: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff832e6a09)
Location: security/integrity/platform_certs/keyring_handler.c:83
Inline: False
```
**Symbols:**

```
ffffffff832e6a09-ffffffff832e6afd: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8349dac3)
Location: security/integrity/platform_certs/keyring_handler.c:77
Inline: False
```
**Symbols:**

```
ffffffff8349dac3-ffffffff8349dbbd: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff83ed5780)
Location: security/integrity/platform_certs/keyring_handler.c:77
Inline: False
```
**Symbols:**

```
ffffffff83ed5780-ffffffff83ed5873: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff836fa8e0)
Location: security/integrity/platform_certs/keyring_handler.c:77
Inline: False
```
**Symbols:**

```
ffffffff836fa8e0-ffffffff836fa9d3: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8392dee0)
Location: security/integrity/platform_certs/keyring_handler.c:94
Inline: False
```
**Symbols:**

```
ffffffff8392dee0-ffffffff8392dfd3: get_handler_for_dbx (STB_GLOBAL)
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffff80001146c904)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
ffff80001146c904-ffff80001146c9b4: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (c1545564)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
c1545564-c1545624: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (c00000000139b650)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
c00000000139b650-c00000000139b7e8: get_handler_for_dbx (STB_GLOBAL)
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
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828db396)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
ffffffff828db396-ffffffff828db453: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828d3ab2)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
ffffffff828d3ab2-ffffffff828d3b6f: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828ee10a)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
ffffffff828ee10a-ffffffff828ee1c7: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_dbx(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f352c)
Location: security/integrity/platform_certs/keyring_handler.c:73
Inline: False
```
**Symbols:**

```
ffffffff828f352c-ffffffff828f35e9: get_handler_for_dbx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
