# Function: <code>add_new_master_key</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134c78d)
Location: fs/crypto/keyring.c:321
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_new_master_key(struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec, struct key *keyring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81391fe0)
Location: fs/crypto/keyring.c:325
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff81391fe0-ffffffff81392219: add_new_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_new_master_key(struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec, struct key *keyring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a3380)
Location: fs/crypto/keyring.c:334
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff813a3380-ffffffff813a358f: add_new_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_new_master_key(struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec, struct key *keyring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813aa5c0)
Location: fs/crypto/keyring.c:334
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff813aa5c0-ffffffff813aa7cf: add_new_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_new_master_key(struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec, struct key *keyring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813f9e50)
Location: fs/crypto/keyring.c:334
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff813f9e50-ffffffff813fa05f: add_new_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_new_master_key(struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec, struct key *keyring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146d000)
Location: fs/crypto/keyring.c:334
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
```
**Symbols:**

```
ffffffff8146d000-ffffffff8146d328: add_new_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814fe7c0)
Location: fs/crypto/keyring.c:414
Inline: True
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff814fe7c0-ffffffff814fe9cc: add_new_master_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81535c90)
Location: fs/crypto/keyring.c:417
Inline: True
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff81535c90-ffffffff81535e90: add_new_master_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156ac60)
Location: fs/crypto/keyring.c:424
Inline: True
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff8156ac60-ffffffff8156ae98: add_new_master_key.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040d5cc)
Location: fs/crypto/keyring.c:321
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05da284)
Location: fs/crypto/keyring.c:321
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051a81c)
Location: fs/crypto/keyring.c:321
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b695c)
Location: fs/crypto/keyring.c:321
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81344d6d)
Location: fs/crypto/keyring.c:321
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81335a4d)
Location: fs/crypto/keyring.c:321
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134283d)
Location: fs/crypto/keyring.c:321
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81355b3d)
Location: fs/crypto/keyring.c:321
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
