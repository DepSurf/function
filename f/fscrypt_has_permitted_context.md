# Function: <code>fscrypt_has_permitted_context</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81289f80)
Location: fs/crypto/policy.c:160
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81289f80-ffffffff8128a06b: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8129eca0)
Location: fs/crypto/policy.c:172
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff8129eca0-ffffffff8129eda9: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812ad5c0)
Location: fs/crypto/policy.c:156
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff812ad5c0-ffffffff812ad708: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812d18e0)
Location: fs/crypto/policy.c:157
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffff812d18e0-ffffffff812d1a2c: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812fc3c0)
Location: fs/crypto/policy.c:157
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffff812fc3c0-ffffffff812fc504: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81311c30)
Location: fs/crypto/policy.c:157
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffff81311c30-ffffffff81311d76: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813391a0)
Location: fs/crypto/policy.c:158
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffff813391a0-ffffffff813392e6: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8134f090)
Location: fs/crypto/policy.c:408
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffff8134f090-ffffffff8134f162: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81395480)
Location: fs/crypto/policy.c:557
Inline: True
```
**Symbols:**

```
ffffffff81395480-ffffffff8139554e: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813a6950)
Location: fs/crypto/policy.c:590
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
**Symbols:**

```
ffffffff813a6950-ffffffff813a6a39: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813ad9e0)
Location: fs/crypto/policy.c:590
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
**Symbols:**

```
ffffffff813ad9e0-ffffffff813adac9: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813fd360)
Location: fs/crypto/policy.c:590
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
```
**Symbols:**

```
ffffffff813fd360-ffffffff813fd449: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81470b20)
Location: fs/crypto/policy.c:611
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff81470b20-ffffffff81470c2d: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff815025f0)
Location: fs/crypto/policy.c:631
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff815025f0-ffffffff815026fd: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81539c90)
Location: fs/crypto/policy.c:630
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff81539c90-ffffffff81539d9d: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8156ee90)
Location: fs/crypto/policy.c:657
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_rename
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff8156ee90-ffffffff8156ef9d: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffff800010410a48)
Location: fs/crypto/policy.c:408
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffff800010410a48-ffff800010410b2c: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c05dd0dc)
Location: fs/crypto/policy.c:408
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
c05dd0dc-c05dd1cc: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c00000000051e380)
Location: fs/crypto/policy.c:408
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
c00000000051e380-c00000000051e4f0: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffe0002b8f84)
Location: fs/crypto/policy.c:408
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffe0002b8f84-ffffffe0002b9044: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81347670)
Location: fs/crypto/policy.c:408
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffff81347670-ffffffff81347742: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81338350)
Location: fs/crypto/policy.c:408
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffff81338350-ffffffff81338422: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81345140)
Location: fs/crypto/policy.c:408
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffff81345140-ffffffff81345212: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_has_permitted_context(struct inode *parent, struct inode *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81358420)
Location: fs/crypto/policy.c:408
Inline: True
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
**Symbols:**

```
ffffffff81358420-ffffffff813584f2: fscrypt_has_permitted_context (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
