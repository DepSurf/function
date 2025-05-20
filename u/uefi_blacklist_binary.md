# Function: <code>uefi_blacklist_binary</code>

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
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff820cdcbd)
Location: certs/load_uefi.c:93
Inline: False
```
**Symbols:**

```
ffffffff820cdcbd-ffffffff820cdd24: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff826d66f3)
Location: certs/load_uefi.c:93
Inline: False
```
**Symbols:**

```
ffffffff826d66f3-ffffffff826d675a: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff827007a9)
Location: certs/load_uefi.c:102
Inline: False
```
**Symbols:**

```
ffffffff827007a9-ffffffff82700810: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/load_uefi.c (ffffffff828b7aff)
Location: certs/load_uefi.c:93
Inline: False
```
```
In security/integrity/platform_certs/load_uefi.c (ffffffff828cfbe7)
Location: security/integrity/platform_certs/load_uefi.c:113
Inline: False
```
**Symbols:**

```
ffffffff828b7aff-ffffffff828b7b66: uefi_blacklist_binary (STB_LOCAL)
ffffffff828cfbe7-ffffffff828cfc04: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff828e98eb)
Location: security/integrity/platform_certs/load_uefi.c:113
Inline: False
```
**Symbols:**

```
ffffffff828e98eb-ffffffff828e9908: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f2441)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffffffff828f2441-ffffffff828f245e: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82d07401)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffffffff82d07401-ffffffff82d0741e: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff82ff48c0)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffffffff82ff48c0-ffffffff82ff48dd: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff831ff581)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffffffff831ff581-ffffffff831ff59e: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff832e696a)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffffffff832e696a-ffffffff832e6987: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8349d94e)
Location: security/integrity/platform_certs/keyring_handler.c:31
Inline: False
```
**Symbols:**

```
ffffffff8349d94e-ffffffff8349d975: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff83ed55b0)
Location: security/integrity/platform_certs/keyring_handler.c:31
Inline: False
```
**Symbols:**

```
ffffffff83ed55b0-ffffffff83ed55d7: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff836fa710)
Location: security/integrity/platform_certs/keyring_handler.c:31
Inline: False
```
**Symbols:**

```
ffffffff836fa710-ffffffff836fa737: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff8392dbd0)
Location: security/integrity/platform_certs/keyring_handler.c:31
Inline: False
```
**Symbols:**

```
ffffffff8392dbd0-ffffffff8392dbf7: uefi_blacklist_binary (STB_LOCAL)
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
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffff80001146c848)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffff80001146c848-ffff80001146c884: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (c15454a4)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
c15454a4-c15454d0: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (c00000000139b528)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
c00000000139b528-c00000000139b550: uefi_blacklist_binary (STB_LOCAL)
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
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828db2f5)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffffffff828db2f5-ffffffff828db312: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828d3a11)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffffffff828d3a11-ffffffff828d3a2e: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828ee069)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffffffff828ee069-ffffffff828ee086: uefi_blacklist_binary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uefi_blacklist_binary(const char *source, const void *data, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/keyring_handler.c (ffffffff828f348b)
Location: security/integrity/platform_certs/keyring_handler.c:52
Inline: False
```
**Symbols:**

```
ffffffff828f348b-ffffffff828f34a8: uefi_blacklist_binary (STB_LOCAL)
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
