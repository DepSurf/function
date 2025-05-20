# Function: <code>get_handler_for_db</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff820cdd8b)
Location: certs/load_uefi.c:115
Inline: False
```
**Symbols:**

```
ffffffff820cdd8b-ffffffff820cde1f: get_handler_for_db (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff826d67c1)
Location: certs/load_uefi.c:115
Inline: False
```
**Symbols:**

```
ffffffff826d67c1-ffffffff826d6855: get_handler_for_db (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff82700877)
Location: certs/load_uefi.c:124
Inline: False
```
**Symbols:**

```
ffffffff82700877-ffffffff827008fb: get_handler_for_db (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff828b7bcd)
Location: certs/load_uefi.c:115
Inline: False
```
```
In security/integrity/platform_certs/load_uefi.c (ffffffff828cf6a0)
Location: security/integrity/platform_certs/load_uefi.c:123
Inline: False
```
**Symbols:**

```
ffffffff828b7bcd-ffffffff828b7c51: get_handler_for_db (STB_LOCAL)
ffffffff828cf6a0-ffffffff828cf724: get_handler_for_db (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828e939b)
Location: security/integrity/platform_certs/load_uefi.c:123
Inline: False
```
**Symbols:**

```
ffffffff828e939b-ffffffff828e941f: get_handler_for_db (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f245e)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff828f245e-ffffffff828f24e2: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82d0741e)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff82d0741e-ffffffff82d0749c: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82ff48dd)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff82ff48dd-ffffffff82ff495b: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff831ff59e)
Location: security/integrity/platform_certs/keyring_handler.c:72
Inline: False
```
**Symbols:**

```
ffffffff831ff59e-ffffffff831ff620: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff832e6987)
Location: security/integrity/platform_certs/keyring_handler.c:72
Inline: False
```
**Symbols:**

```
ffffffff832e6987-ffffffff832e6a09: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8349d99c)
Location: security/integrity/platform_certs/keyring_handler.c:51
Inline: False
```
**Symbols:**

```
ffffffff8349d99c-ffffffff8349da28: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff83ed5630)
Location: security/integrity/platform_certs/keyring_handler.c:51
Inline: False
```
**Symbols:**

```
ffffffff83ed5630-ffffffff83ed56b5: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff836fa790)
Location: security/integrity/platform_certs/keyring_handler.c:51
Inline: False
```
**Symbols:**

```
ffffffff836fa790-ffffffff836fa815: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8392dc50)
Location: security/integrity/platform_certs/keyring_handler.c:51
Inline: False
```
**Symbols:**

```
ffffffff8392dc50-ffffffff8392dcd5: get_handler_for_db (STB_GLOBAL)
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
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffff80001146c884)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffff80001146c884-ffff80001146c904: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (c15454d0)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
c15454d0-c1545564: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (c00000000139b550)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
c00000000139b550-c00000000139b650: get_handler_for_db (STB_GLOBAL)
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
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828db312)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff828db312-ffffffff828db396: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828d3a2e)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff828d3a2e-ffffffff828d3ab2: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828ee086)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff828ee086-ffffffff828ee10a: get_handler_for_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
efi_element_handler_t get_handler_for_db(const efi_guid_t *sig_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f34a8)
Location: security/integrity/platform_certs/keyring_handler.c:62
Inline: False
```
**Symbols:**

```
ffffffff828f34a8-ffffffff828f352c: get_handler_for_db (STB_GLOBAL)
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
