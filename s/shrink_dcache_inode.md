# Function: <code>shrink_dcache_inode</code>

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
In fs/crypto/keyring.c (ffffffff8134cd99)
Location: fs/crypto/keyring.c:617
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
In fs/crypto/keyring.c (ffffffff81392368)
Location: fs/crypto/keyring.c:761
Inline: True
Inline callers:
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
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
In fs/crypto/keyring.c (ffffffff813a36e8)
Location: fs/crypto/keyring.c:766
Inline: True
Inline callers:
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
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
In fs/crypto/keyring.c (ffffffff813aa877)
Location: fs/crypto/keyring.c:766
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
In fs/crypto/keyring.c (ffffffff813fa107)
Location: fs/crypto/keyring.c:766
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
In fs/crypto/keyring.c (ffffffff8146ccc4)
Location: fs/crypto/keyring.c:806
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
In fs/crypto/keyring.c (ffffffff814fdfc4)
Location: fs/crypto/keyring.c:863
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
In fs/crypto/keyring.c (ffffffff815355b4)
Location: fs/crypto/keyring.c:858
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
In fs/crypto/keyring.c (ffffffff8156a584)
Location: fs/crypto/keyring.c:873
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
In fs/crypto/keyring.c (ffff80001040de04)
Location: fs/crypto/keyring.c:617
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
In fs/crypto/keyring.c (c05daa20)
Location: fs/crypto/keyring.c:617
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
In fs/crypto/keyring.c (c00000000051afc4)
Location: fs/crypto/keyring.c:617
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
In fs/crypto/keyring.c (ffffffe0002b6f18)
Location: fs/crypto/keyring.c:617
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
In fs/crypto/keyring.c (ffffffff81345379)
Location: fs/crypto/keyring.c:617
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
In fs/crypto/keyring.c (ffffffff81336059)
Location: fs/crypto/keyring.c:617
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
In fs/crypto/keyring.c (ffffffff81342e49)
Location: fs/crypto/keyring.c:617
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
In fs/crypto/keyring.c (ffffffff81356149)
Location: fs/crypto/keyring.c:617
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
</details>
</li>
</ul>

## Differences
