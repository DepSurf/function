# Function: <code>x509_load_certificate_list</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int x509_load_certificate_list(const u8 *cert_list, const long unsigned int list_size, const struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_loader.c (0)
Location: crypto/asymmetric_keys/x509_loader.c:7
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:load_module_cert
  - certs/blacklist.c:load_revocation_certificate_list
```
**Symbols:**

```
ffffffff81e8aca0-ffffffff81e8ad03: x509_load_certificate_list.cold (STB_LOCAL)
ffffffff8166b700-ffffffff8166b7aa: x509_load_certificate_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x509_load_certificate_list(const u8 *cert_list, const long unsigned int list_size, const struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_loader.c (ffffffff817262a0)
Location: crypto/asymmetric_keys/x509_loader.c:7
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:load_module_cert
  - certs/blacklist.c:load_revocation_certificate_list
```
**Symbols:**

```
ffffffff817262a0-ffffffff817263a4: x509_load_certificate_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x509_load_certificate_list(const u8 *cert_list, const long unsigned int list_size, const struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_loader.c (ffffffff81762630)
Location: crypto/asymmetric_keys/x509_loader.c:7
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:load_module_cert
  - certs/blacklist.c:load_revocation_certificate_list
```
**Symbols:**

```
ffffffff81762630-ffffffff81762734: x509_load_certificate_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x509_load_certificate_list(const u8 *cert_list, const long unsigned int list_size, const struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_loader.c (ffffffff817a40f0)
Location: crypto/asymmetric_keys/x509_loader.c:7
Inline: False
Direct callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:load_module_cert
  - certs/blacklist.c:load_revocation_certificate_list
```
**Symbols:**

```
ffffffff817a40f0-ffffffff817a41f4: x509_load_certificate_list (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
