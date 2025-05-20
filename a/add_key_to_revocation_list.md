# Function: <code>add_key_to_revocation_list</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int add_key_to_revocation_list(const char *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:160
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509
```
**Symbols:**

```
ffffffff81bd86ff-ffffffff81bd8731: add_key_to_revocation_list.cold (STB_LOCAL)
ffffffff8125c2d0-ffffffff8125c316: add_key_to_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int add_key_to_revocation_list(const char *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:160
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509
```
**Symbols:**

```
ffffffff81cb9d56-ffffffff81cb9d88: add_key_to_revocation_list.cold (STB_LOCAL)
ffffffff81298180-ffffffff812981c6: add_key_to_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int add_key_to_revocation_list(const char *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:259
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509
```
**Symbols:**

```
ffffffff81e6b344-ffffffff81e6b388: add_key_to_revocation_list.cold (STB_LOCAL)
ffffffff812ee710-ffffffff812ee756: add_key_to_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_key_to_revocation_list(const char *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff81358bf0)
Location: certs/blacklist.c:259
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509
```
**Symbols:**

```
ffffffff81358bf0-ffffffff81358c87: add_key_to_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_key_to_revocation_list(const char *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff8138a510)
Location: certs/blacklist.c:262
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509
```
**Symbols:**

```
ffffffff8138a510-ffffffff8138a5a7: add_key_to_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_key_to_revocation_list(const char *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff813b4030)
Location: certs/blacklist.c:262
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_revocation_list_x509
```
**Symbols:**

```
ffffffff813b4030-ffffffff813b40c7: add_key_to_revocation_list (STB_GLOBAL)
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
