# Function: <code>fscrypt_is_nokey_name</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a2905)
Location: include/linux/fscrypt.h:138
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
```
In fs/ext4/namei.c (ffffffff814277d2)
Location: include/linux/fscrypt.h:138
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a9a95)
Location: include/linux/fscrypt.h:138
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
```
In fs/ext4/namei.c (ffffffff8142e446)
Location: include/linux/fscrypt.h:138
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813f92d5)
Location: include/linux/fscrypt.h:239
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
```
In fs/ext4/namei.c (ffffffff81482376)
Location: include/linux/fscrypt.h:239
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8146c145)
Location: include/linux/fscrypt.h:247
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
```
In fs/ext4/namei.c (ffffffff81505341)
Location: include/linux/fscrypt.h:247
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff814fd4a5)
Location: include/linux/fscrypt.h:244
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
```
In fs/ext4/namei.c (ffffffff8159fe51)
Location: include/linux/fscrypt.h:244
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81534a05)
Location: include/linux/fscrypt.h:244
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
```
In fs/ext4/namei.c (ffffffff815d67a1)
Location: include/linux/fscrypt.h:244
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff815699c5)
Location: include/linux/fscrypt.h:259
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
```
In fs/ext4/namei.c (ffffffff8160ee18)
Location: include/linux/fscrypt.h:259
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
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
