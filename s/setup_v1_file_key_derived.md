# Function: <code>setup_v1_file_key_derived</code>

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
In fs/crypto/keysetup_v1.c (ffffffff8134e617)
Location: fs/crypto/keysetup_v1.c:286
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int setup_v1_file_key_derived(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813942d0)
Location: fs/crypto/keysetup_v1.c:267
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813942d0-ffffffff81394345: setup_v1_file_key_derived (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int setup_v1_file_key_derived(struct fscrypt_info *ci, const u8 *raw_master_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813a5790)
Location: fs/crypto/keysetup_v1.c:265
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
```
**Symbols:**

```
ffffffff813a5790-ffffffff813a5805: setup_v1_file_key_derived (STB_LOCAL)
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
In fs/crypto/keysetup_v1.c (ffffffff813acb9d)
Location: fs/crypto/keysetup_v1.c:265
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffff813fc50d)
Location: fs/crypto/keysetup_v1.c:265
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffff8146f9c6)
Location: fs/crypto/keysetup_v1.c:265
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffff815011b6)
Location: fs/crypto/keysetup_v1.c:267
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffff81538846)
Location: fs/crypto/keysetup_v1.c:267
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffff8156d9c6)
Location: fs/crypto/keysetup_v1.c:268
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffff80001040f9e0)
Location: fs/crypto/keysetup_v1.c:286
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (c05dc29c)
Location: fs/crypto/keysetup_v1.c:286
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (c00000000051d420)
Location: fs/crypto/keysetup_v1.c:286
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffe0002b848a)
Location: fs/crypto/keysetup_v1.c:286
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffff81346bf7)
Location: fs/crypto/keysetup_v1.c:286
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffff813378d7)
Location: fs/crypto/keysetup_v1.c:286
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffff813446c7)
Location: fs/crypto/keysetup_v1.c:286
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
In fs/crypto/keysetup_v1.c (ffffffff813579a7)
Location: fs/crypto/keysetup_v1.c:286
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
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
