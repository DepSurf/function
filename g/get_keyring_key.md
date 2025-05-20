# Function: <code>get_keyring_key</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813929a9)
Location: fs/crypto/keyring.c:569
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
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
In fs/crypto/keyring.c (ffffffff813a3d19)
Location: fs/crypto/keyring.c:574
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
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
In fs/crypto/keyring.c (ffffffff813aaf59)
Location: fs/crypto/keyring.c:574
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
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
In fs/crypto/keyring.c (ffffffff813fa7e9)
Location: fs/crypto/keyring.c:574
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
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
In fs/crypto/keyring.c (ffffffff8146da50)
Location: fs/crypto/keyring.c:574
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_keyring_key(u32 key_id, u32 type, struct fscrypt_master_key_secret *secret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814fe200)
Location: fs/crypto/keyring.c:630
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff814fe200-ffffffff814fe290: get_keyring_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_keyring_key(u32 key_id, u32 type, struct fscrypt_master_key_secret *secret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:633
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff815357e0-ffffffff815358ca: get_keyring_key (STB_LOCAL)
ffffffff820ea3e0-ffffffff820ea3fd: get_keyring_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int get_keyring_key(u32 key_id, u32 type, struct fscrypt_master_key_secret *secret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:648
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff8156a7b0-ffffffff8156a89a: get_keyring_key (STB_LOCAL)
ffffffff821c6eaa-ffffffff821c6ec7: get_keyring_key.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
