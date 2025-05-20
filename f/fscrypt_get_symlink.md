# Function: <code>fscrypt_get_symlink</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff812fb480)
Location: fs/crypto/hooks.c:214
Inline: True
```
**Symbols:**

```
ffffffff812fb480-ffffffff812fb580: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81310890)
Location: fs/crypto/hooks.c:214
Inline: True
```
**Symbols:**

```
ffffffff81310890-ffffffff81310990: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
ffffffff81338066-ffffffff81338080: fscrypt_get_symlink.cold (STB_LOCAL)
ffffffff81337b00-ffffffff81337c4e: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8134bb80)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
ffffffff8134bb80-ffffffff8134bccf: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813914f0)
Location: fs/crypto/hooks.c:278
Inline: False
```
**Symbols:**

```
ffffffff813914f0-ffffffff81391634: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a2b00)
Location: fs/crypto/hooks.c:312
Inline: False
```
**Symbols:**

```
ffffffff813a2b00-ffffffff813a2c44: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a9c90)
Location: fs/crypto/hooks.c:312
Inline: False
```
**Symbols:**

```
ffffffff813a9c90-ffffffff813a9ddf: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813f94d0)
Location: fs/crypto/hooks.c:312
Inline: False
```
**Symbols:**

```
ffffffff813f94d0-ffffffff813f961f: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8146c3c0)
Location: fs/crypto/hooks.c:312
Inline: False
```
**Symbols:**

```
ffffffff8146c3c0-ffffffff8146c544: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff814fd760)
Location: fs/crypto/hooks.c:308
Inline: False
```
**Symbols:**

```
ffffffff814fd760-ffffffff814fd8e4: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81534cc0)
Location: fs/crypto/hooks.c:338
Inline: False
```
**Symbols:**

```
ffffffff81534cc0-ffffffff81534e44: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81569c80)
Location: fs/crypto/hooks.c:338
Inline: False
```
**Symbols:**

```
ffffffff81569c80-ffffffff81569e04: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffff80001040c738)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
ffff80001040c738-ffff80001040c8d0: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c05d98b4)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
c05d98b4-c05d9a4c: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c0000000005195b0)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
c0000000005195b0-c0000000005197d0: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffe0002b5e64)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
ffffffe0002b5e64-ffffffe0002b5f8a: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81344160)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
ffffffff81344160-ffffffff813442af: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81334e40)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
ffffffff81334e40-ffffffff81334f8f: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81341c30)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
ffffffff81341c30-ffffffff81341d7f: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *fscrypt_get_symlink(struct inode *inode, const void *caddr, unsigned int max_size, struct delayed_call *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81354f30)
Location: fs/crypto/hooks.c:233
Inline: False
```
**Symbols:**

```
ffffffff81354f30-ffffffff8135507f: fscrypt_get_symlink (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
