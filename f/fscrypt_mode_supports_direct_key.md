# Function: <code>fscrypt_mode_supports_direct_key</code>

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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8134da34)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e5c5)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffff80001040ed0c)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f97c)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c05db834)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
```
In fs/crypto/keysetup_v1.c (c05dc244)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c00000000051c3a4)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
```
In fs/crypto/keysetup_v1.c (c00000000051d388)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffe0002b7b18)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b844c)
Location: fs/crypto/fscrypt_private.h:451
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81346014)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346ba5)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81336cf4)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81337885)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81343ae4)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81344675)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81356dc4)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81357955)
Location: fs/crypto/fscrypt_private.h:451
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
</details>
</li>
</ul>

## Differences
