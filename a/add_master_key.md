# Function: <code>add_master_key</code>

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
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134c5a0)
Location: fs/crypto/keyring.c:425
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff8134c5a0-ffffffff8134c9e2: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813927d0)
Location: fs/crypto/keyring.c:470
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff813927d0-ffffffff8139284b: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a3b40)
Location: fs/crypto/keyring.c:475
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff813a3b40-ffffffff813a3bbb: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813aad80)
Location: fs/crypto/keyring.c:475
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff813aad80-ffffffff813aadfb: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813fa610)
Location: fs/crypto/keyring.c:475
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff813fa610-ffffffff813fa68b: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146d840)
Location: fs/crypto/keyring.c:475
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff8146d840-ffffffff8146d8cc: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814fecf0)
Location: fs/crypto/keyring.c:531
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff814fecf0-ffffffff814fef17: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81536300)
Location: fs/crypto/keyring.c:534
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff81536300-ffffffff81536538: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:549
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff8156b320-ffffffff8156b5a2: add_master_key (STB_LOCAL)
ffffffff821c6ef0-ffffffff821c6f04: add_master_key.cold (STB_LOCAL)
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
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040d440)
Location: fs/crypto/keyring.c:425
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffff80001040d440-ffff80001040d7f0: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05da0dc)
Location: fs/crypto/keyring.c:425
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
c05da0dc-c05da4dc: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051a590)
Location: fs/crypto/keyring.c:425
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
c00000000051a590-c00000000051aaac: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b67cc)
Location: fs/crypto/keyring.c:425
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffe0002b67cc-ffffffe0002b6bd8: add_master_key (STB_LOCAL)
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
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81344b80)
Location: fs/crypto/keyring.c:425
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff81344b80-ffffffff81344fc2: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81335860)
Location: fs/crypto/keyring.c:425
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff81335860-ffffffff81335ca2: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81342650)
Location: fs/crypto/keyring.c:425
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff81342650-ffffffff81342a92: add_master_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_master_key(struct super_block *sb, struct fscrypt_master_key_secret *secret, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81355950)
Location: fs/crypto/keyring.c:425
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff81355950-ffffffff81355d92: add_master_key (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fscrypt_key_specifier *key_spec</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fscrypt_key_specifier *mk_spec</code>
</li>
</ul>
</details>
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
