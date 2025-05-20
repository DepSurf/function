# Function: <code>uefi_blacklist_x509_tbs</code>

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
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff820cdd24)
Location: certs/load_uefi.c:72
Inline: False
```
**Symbols:**

```
ffffffff820cdd24-ffffffff820cdd8b: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff826d675a)
Location: certs/load_uefi.c:72
Inline: False
```
**Symbols:**

```
ffffffff826d675a-ffffffff826d67c1: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff82700810)
Location: certs/load_uefi.c:81
Inline: False
```
**Symbols:**

```
ffffffff82700810-ffffffff82700877: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff828b7b66)
Location: certs/load_uefi.c:72
Inline: False
```
```
In security/integrity/platform_certs/load_uefi.c (ffffffff828cfbca)
Location: security/integrity/platform_certs/load_uefi.c:104
Inline: False
```
**Symbols:**

```
ffffffff828b7b66-ffffffff828b7bcd: uefi_blacklist_x509_tbs (STB_LOCAL)
ffffffff828cfbca-ffffffff828cfbe7: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828e98ce)
Location: security/integrity/platform_certs/load_uefi.c:104
Inline: False
```
**Symbols:**

```
ffffffff828e98ce-ffffffff828e98eb: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f2424)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffffffff828f2424-ffffffff828f2441: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82d073e4)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffffffff82d073e4-ffffffff82d07401: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82ff48a3)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffffffff82ff48a3-ffffffff82ff48c0: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff831ff564)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffffffff831ff564-ffffffff831ff581: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff832e694d)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffffffff832e694d-ffffffff832e696a: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8349d975)
Location: security/integrity/platform_certs/keyring_handler.c:22
Inline: False
```
**Symbols:**

```
ffffffff8349d975-ffffffff8349d99c: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff83ed55f0)
Location: security/integrity/platform_certs/keyring_handler.c:22
Inline: False
```
**Symbols:**

```
ffffffff83ed55f0-ffffffff83ed5617: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff836fa750)
Location: security/integrity/platform_certs/keyring_handler.c:22
Inline: False
```
**Symbols:**

```
ffffffff836fa750-ffffffff836fa777: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8392dc10)
Location: security/integrity/platform_certs/keyring_handler.c:22
Inline: False
```
**Symbols:**

```
ffffffff8392dc10-ffffffff8392dc37: uefi_blacklist_x509_tbs (STB_LOCAL)
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
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffff80001146c80c)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffff80001146c80c-ffff80001146c848: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (c1545478)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
c1545478-c15454a4: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (c00000000139b500)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
c00000000139b500-c00000000139b528: uefi_blacklist_x509_tbs (STB_LOCAL)
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
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828db2d8)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffffffff828db2d8-ffffffff828db2f5: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828d39f4)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffffffff828d39f4-ffffffff828d3a11: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828ee04c)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffffffff828ee04c-ffffffff828ee069: uefi_blacklist_x509_tbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uefi_blacklist_x509_tbs(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f346e)
Location: security/integrity/platform_certs/keyring_handler.c:43
Inline: False
```
**Symbols:**

```
ffffffff828f346e-ffffffff828f348b: uefi_blacklist_x509_tbs (STB_LOCAL)
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
