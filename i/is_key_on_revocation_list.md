# Function: <code>is_key_on_revocation_list</code>

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
int is_key_on_revocation_list(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff8125c320)
Location: certs/blacklist.c:187
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff8125c320-ffffffff8125c342: is_key_on_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int is_key_on_revocation_list(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff812981d0)
Location: certs/blacklist.c:187
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff812981d0-ffffffff812981f2: is_key_on_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int is_key_on_revocation_list(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff812ee760)
Location: certs/blacklist.c:288
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff812ee760-ffffffff812ee78a: is_key_on_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int is_key_on_revocation_list(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff81358ca0)
Location: certs/blacklist.c:288
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81358ca0-ffffffff81358cca: is_key_on_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int is_key_on_revocation_list(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff8138a5c0)
Location: certs/blacklist.c:291
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff8138a5c0-ffffffff8138a5ea: is_key_on_revocation_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int is_key_on_revocation_list(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff813b40e0)
Location: certs/blacklist.c:291
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff813b40e0-ffffffff813b410a: is_key_on_revocation_list (STB_GLOBAL)
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
