# Function: <code>check_for_busy_inodes</code>

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
In fs/crypto/keyring.c (ffffffff8134cea2)
Location: fs/crypto/keyring.c:661
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_for_busy_inodes(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:805
Inline: False
```
**Symbols:**

```
ffffffff81392220-ffffffff813922fd: check_for_busy_inodes (STB_LOCAL)
ffffffff81393204-ffffffff81393215: check_for_busy_inodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_for_busy_inodes(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:810
Inline: False
```
**Symbols:**

```
ffffffff813a3590-ffffffff813a3678: check_for_busy_inodes (STB_LOCAL)
ffffffff81beae39-ffffffff81beaeca: check_for_busy_inodes.cold (STB_LOCAL)
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
In fs/crypto/keyring.c (ffffffff813aa8f9)
Location: fs/crypto/keyring.c:810
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
In fs/crypto/keyring.c (ffffffff813fa189)
Location: fs/crypto/keyring.c:810
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
In fs/crypto/keyring.c (ffffffff8146cd43)
Location: fs/crypto/keyring.c:850
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
In fs/crypto/keyring.c (ffffffff814fe043)
Location: fs/crypto/keyring.c:907
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
In fs/crypto/keyring.c (ffffffff81535633)
Location: fs/crypto/keyring.c:902
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
In fs/crypto/keyring.c (ffffffff8156a603)
Location: fs/crypto/keyring.c:917
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
In fs/crypto/keyring.c (ffff80001040dbf4)
Location: fs/crypto/keyring.c:661
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
In fs/crypto/keyring.c (c05daa88)
Location: fs/crypto/keyring.c:661
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
In fs/crypto/keyring.c (c00000000051b048)
Location: fs/crypto/keyring.c:661
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
In fs/crypto/keyring.c (ffffffe0002b6fd8)
Location: fs/crypto/keyring.c:661
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
In fs/crypto/keyring.c (ffffffff81345482)
Location: fs/crypto/keyring.c:661
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
In fs/crypto/keyring.c (ffffffff81336162)
Location: fs/crypto/keyring.c:661
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
In fs/crypto/keyring.c (ffffffff81342f52)
Location: fs/crypto/keyring.c:661
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
In fs/crypto/keyring.c (ffffffff8135625b)
Location: fs/crypto/keyring.c:661
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
