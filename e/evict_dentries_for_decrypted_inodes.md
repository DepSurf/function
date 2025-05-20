# Function: <code>evict_dentries_for_decrypted_inodes</code>

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
In fs/crypto/keyring.c (ffffffff8134cd42)
Location: fs/crypto/keyring.c:631
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void evict_dentries_for_decrypted_inodes(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81392300)
Location: fs/crypto/keyring.c:775
Inline: False
```
**Symbols:**

```
ffffffff81392300-ffffffff81392423: evict_dentries_for_decrypted_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void evict_dentries_for_decrypted_inodes(struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a3680)
Location: fs/crypto/keyring.c:780
Inline: False
```
**Symbols:**

```
ffffffff813a3680-ffffffff813a37a3: evict_dentries_for_decrypted_inodes (STB_LOCAL)
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
In fs/crypto/keyring.c (ffffffff813aa82c)
Location: fs/crypto/keyring.c:780
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
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
In fs/crypto/keyring.c (ffffffff813fa0bc)
Location: fs/crypto/keyring.c:780
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
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
In fs/crypto/keyring.c (ffffffff8146cc86)
Location: fs/crypto/keyring.c:820
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
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
In fs/crypto/keyring.c (ffffffff814fdf86)
Location: fs/crypto/keyring.c:877
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
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
In fs/crypto/keyring.c (ffffffff81535576)
Location: fs/crypto/keyring.c:872
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
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
In fs/crypto/keyring.c (ffffffff8156a546)
Location: fs/crypto/keyring.c:887
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
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
In fs/crypto/keyring.c (ffff80001040db4c)
Location: fs/crypto/keyring.c:631
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
In fs/crypto/keyring.c (c05da964)
Location: fs/crypto/keyring.c:631
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
In fs/crypto/keyring.c (c00000000051aeec)
Location: fs/crypto/keyring.c:631
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
In fs/crypto/keyring.c (ffffffe0002b6e68)
Location: fs/crypto/keyring.c:631
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
In fs/crypto/keyring.c (ffffffff81345322)
Location: fs/crypto/keyring.c:631
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
In fs/crypto/keyring.c (ffffffff81336002)
Location: fs/crypto/keyring.c:631
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
In fs/crypto/keyring.c (ffffffff81342df2)
Location: fs/crypto/keyring.c:631
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
In fs/crypto/keyring.c (ffffffff813560f4)
Location: fs/crypto/keyring.c:631
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
