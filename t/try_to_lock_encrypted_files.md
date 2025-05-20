# Function: <code>try_to_lock_encrypted_files</code>

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
In fs/crypto/keyring.c (ffffffff8134cd19)
Location: fs/crypto/keyring.c:696
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
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
In fs/crypto/keyring.c (ffffffff81392d7a)
Location: fs/crypto/keyring.c:840
Inline: True
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
In fs/crypto/keyring.c (ffffffff813a40f3)
Location: fs/crypto/keyring.c:850
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int try_to_lock_encrypted_files(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:850
Inline: False
```
**Symbols:**

```
ffffffff813aa7d0-ffffffff813aa9eb: try_to_lock_encrypted_files (STB_LOCAL)
ffffffff81bdce86-ffffffff81bdcf22: try_to_lock_encrypted_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int try_to_lock_encrypted_files(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:850
Inline: False
```
**Symbols:**

```
ffffffff813fa060-ffffffff813fa27b: try_to_lock_encrypted_files (STB_LOCAL)
ffffffff81cc6455-ffffffff81cc64f1: try_to_lock_encrypted_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int try_to_lock_encrypted_files(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:890
Inline: False
```
**Symbols:**

```
ffffffff8146cc20-ffffffff8146ce48: try_to_lock_encrypted_files (STB_LOCAL)
ffffffff81e788c4-ffffffff81e78960: try_to_lock_encrypted_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_to_lock_encrypted_files(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814fdf20)
Location: fs/crypto/keyring.c:947
Inline: False
```
**Symbols:**

```
ffffffff814fdf20-ffffffff814fe1e5: try_to_lock_encrypted_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_to_lock_encrypted_files(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81535510)
Location: fs/crypto/keyring.c:942
Inline: False
```
**Symbols:**

```
ffffffff81535510-ffffffff815357cb: try_to_lock_encrypted_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_to_lock_encrypted_files(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156a4e0)
Location: fs/crypto/keyring.c:957
Inline: False
```
**Symbols:**

```
ffffffff8156a4e0-ffffffff8156a79b: try_to_lock_encrypted_files (STB_LOCAL)
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
In fs/crypto/keyring.c (ffff80001040db28)
Location: fs/crypto/keyring.c:696
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
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
In fs/crypto/keyring.c (c05da938)
Location: fs/crypto/keyring.c:696
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
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
In fs/crypto/keyring.c (c00000000051aeb8)
Location: fs/crypto/keyring.c:696
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
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
In fs/crypto/keyring.c (ffffffe0002b6e50)
Location: fs/crypto/keyring.c:696
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
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
In fs/crypto/keyring.c (ffffffff813452f9)
Location: fs/crypto/keyring.c:696
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
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
In fs/crypto/keyring.c (ffffffff81335fd9)
Location: fs/crypto/keyring.c:696
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
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
In fs/crypto/keyring.c (ffffffff81342dc9)
Location: fs/crypto/keyring.c:696
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
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
In fs/crypto/keyring.c (ffffffff813560c6)
Location: fs/crypto/keyring.c:696
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
</details>
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
