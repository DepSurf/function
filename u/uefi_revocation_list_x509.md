# Function: <code>uefi_revocation_list_x509</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uefi_revocation_list_x509(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff831ff4c4)
Location: security/integrity/platform_certs/keyring_handler.c:61
Inline: False
```
**Symbols:**

```
ffffffff831ff4c4-ffffffff831ff4f7: uefi_revocation_list_x509 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uefi_revocation_list_x509(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff832e68ad)
Location: security/integrity/platform_certs/keyring_handler.c:61
Inline: False
```
**Symbols:**

```
ffffffff832e68ad-ffffffff832e68e0: uefi_revocation_list_x509 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uefi_revocation_list_x509(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8349d911)
Location: security/integrity/platform_certs/keyring_handler.c:40
Inline: False
```
**Symbols:**

```
ffffffff8349d911-ffffffff8349d94e: uefi_revocation_list_x509 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uefi_revocation_list_x509(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff83ed5560)
Location: security/integrity/platform_certs/keyring_handler.c:40
Inline: False
```
**Symbols:**

```
ffffffff83ed5560-ffffffff83ed559d: uefi_revocation_list_x509 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uefi_revocation_list_x509(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff836fa6c0)
Location: security/integrity/platform_certs/keyring_handler.c:40
Inline: False
```
**Symbols:**

```
ffffffff836fa6c0-ffffffff836fa6fd: uefi_revocation_list_x509 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uefi_revocation_list_x509(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8392db80)
Location: security/integrity/platform_certs/keyring_handler.c:40
Inline: False
```
**Symbols:**

```
ffffffff8392db80-ffffffff8392dbbd: uefi_revocation_list_x509 (STB_LOCAL)
```
</details>
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
