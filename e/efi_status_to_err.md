# Function: <code>efi_status_to_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d08f5)
Location: drivers/firmware/efi/vars.c:306
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81733b70)
Location: drivers/firmware/efi/efi.c:788
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff81733b70-ffffffff81733bef: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81766c10)
Location: drivers/firmware/efi/efi.c:820
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff81766c10-ffffffff81766c96: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81785540)
Location: drivers/firmware/efi/efi.c:822
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff81785540-ffffffff817855b0: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff817fb930)
Location: drivers/firmware/efi/efi.c:868
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff817fb930-ffffffff817fb9a0: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818450a0)
Location: drivers/firmware/efi/efi.c:952
Inline: False
Direct callers:
  - certs/load_uefi.c:get_cert_list
  - certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff818450a0-ffffffff818450d7: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818711c0)
Location: drivers/firmware/efi/efi.c:999
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff818711c0-ffffffff818711f7: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818b5440)
Location: drivers/firmware/efi/efi.c:1003
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff818b5440-ffffffff818b5477: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818e7de0)
Location: drivers/firmware/efi/efi.c:993
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff818e7de0-ffffffff818e7e17: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bb0e0)
Location: drivers/firmware/efi/efi.c:907
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff819bb0e0-ffffffff819bb117: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bd340)
Location: drivers/firmware/efi/efi.c:915
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff819bd340-ffffffff819bd377: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819a1ad0)
Location: drivers/firmware/efi/efi.c:915
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff819a1ad0-ffffffff819a1b07: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81a4ea90)
Location: drivers/firmware/efi/efi.c:922
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff81a4ea90-ffffffff81a4eac7: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81bbd710)
Location: drivers/firmware/efi/efi.c:936
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff81bbd710-ffffffff81bbd765: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81d62f00)
Location: drivers/firmware/efi/efi.c:960
Inline: False
Direct callers:
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_get
  - fs/efivarfs/vars.c:efivar_entry_size
  - fs/efivarfs/vars.c:efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff81d62f00-ffffffff81d62f55: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81dcdfd0)
Location: drivers/firmware/efi/efi.c:1027
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_statfs
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_get
  - fs/efivarfs/vars.c:efivar_entry_size
  - fs/efivarfs/vars.c:efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff81dcdfd0-ffffffff81dce025: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81e86b10)
Location: drivers/firmware/efi/efi.c:1064
Inline: False
Direct callers:
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_get
  - fs/efivarfs/vars.c:efivar_entry_size
  - fs/efivarfs/vars.c:efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff81e86b10-ffffffff81e86b65: efi_status_to_err (STB_GLOBAL)
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
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff800010b5af38)
Location: drivers/firmware/efi/efi.c:993
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffff800010b5af38-ffff800010b5af90: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c0c3bb4c)
Location: drivers/firmware/efi/efi.c:993
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
c0c3bb4c-c0c3bb98: efi_status_to_err (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8188ab60)
Location: drivers/firmware/efi/efi.c:993
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff8188ab60-ffffffff8188ab97: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818424e0)
Location: drivers/firmware/efi/efi.c:993
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff818424e0-ffffffff81842517: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818dcc40)
Location: drivers/firmware/efi/efi.c:993
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff818dcc40-ffffffff818dcc77: efi_status_to_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int efi_status_to_err(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818f9750)
Location: drivers/firmware/efi/efi.c:993
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:__efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:__efivar_entry_delete
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/capsule.c:efi_capsule_supported
```
**Symbols:**

```
ffffffff818f9750-ffffffff818f9787: efi_status_to_err (STB_GLOBAL)
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
