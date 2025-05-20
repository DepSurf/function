# Function: <code>do_add_master_key</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81392510)
Location: fs/crypto/keyring.c:429
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff81392510-ffffffff813927c1: do_add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a3890)
Location: fs/crypto/keyring.c:434
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff813a3890-ffffffff813a3b40: do_add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813aaad0)
Location: fs/crypto/keyring.c:434
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff813aaad0-ffffffff813aad7c: do_add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813fa360)
Location: fs/crypto/keyring.c:434
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff813fa360-ffffffff813fa60c: do_add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146d530)
Location: fs/crypto/keyring.c:434
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff8146d530-ffffffff8146d836: do_add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814fed18)
Location: fs/crypto/keyring.c:492
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81536328)
Location: fs/crypto/keyring.c:495
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156b348)
Location: fs/crypto/keyring.c:510
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
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
