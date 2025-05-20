# Function: <code>fscrypt_symlink_getattr</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_symlink_getattr(const struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a9de0)
Location: fs/crypto/hooks.c:408
Inline: False
Direct callers:
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff813a9de0-ffffffff813a9e8c: fscrypt_symlink_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_symlink_getattr(const struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813f9620)
Location: fs/crypto/hooks.c:408
Inline: False
Direct callers:
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff813f9620-ffffffff813f96cc: fscrypt_symlink_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_symlink_getattr(const struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8146c550)
Location: fs/crypto/hooks.c:408
Inline: False
Direct callers:
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff8146c550-ffffffff8146c607: fscrypt_symlink_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_symlink_getattr(const struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff814fd900)
Location: fs/crypto/hooks.c:404
Inline: False
Direct callers:
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff814fd900-ffffffff814fd9b7: fscrypt_symlink_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_symlink_getattr(const struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81534e60)
Location: fs/crypto/hooks.c:434
Inline: False
Direct callers:
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff81534e60-ffffffff81534f17: fscrypt_symlink_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_symlink_getattr(const struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81569e20)
Location: fs/crypto/hooks.c:434
Inline: False
Direct callers:
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff81569e20-ffffffff81569ed7: fscrypt_symlink_getattr (STB_GLOBAL)
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
