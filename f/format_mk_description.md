# Function: <code>format_mk_description</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void format_mk_description(char *description, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134c170)
Location: fs/crypto/keyring.c:170
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff8134c170-ffffffff8134c1a2: format_mk_description (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813920c6)
Location: fs/crypto/keyring.c:174
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a3442)
Location: fs/crypto/keyring.c:174
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813aa682)
Location: fs/crypto/keyring.c:174
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813f9f12)
Location: fs/crypto/keyring.c:174
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146d0da)
Location: fs/crypto/keyring.c:174
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void format_mk_description(char *description, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040ccd0)
Location: fs/crypto/keyring.c:170
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffff80001040ccd0-ffff80001040cd28: format_mk_description (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void format_mk_description(char *description, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05d9cfc)
Location: fs/crypto/keyring.c:170
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
c05d9cfc-c05d9d40: format_mk_description (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void format_mk_description(char *description, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051a050)
Location: fs/crypto/keyring.c:170
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
c00000000051a050-c00000000051a0b0: format_mk_description (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void format_mk_description(char *description, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b6540)
Location: fs/crypto/keyring.c:170
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffe0002b6540-ffffffe0002b658e: format_mk_description (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void format_mk_description(char *description, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81344750)
Location: fs/crypto/keyring.c:170
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff81344750-ffffffff81344782: format_mk_description (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void format_mk_description(char *description, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81335430)
Location: fs/crypto/keyring.c:170
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff81335430-ffffffff81335462: format_mk_description (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void format_mk_description(char *description, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81342220)
Location: fs/crypto/keyring.c:170
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff81342220-ffffffff81342252: format_mk_description (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void format_mk_description(char *description, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81355520)
Location: fs/crypto/keyring.c:170
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
**Symbols:**

```
ffffffff81355520-ffffffff81355552: format_mk_description (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
