# Function: <code>do_remove_key</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_remove_key(struct file *filp, void *_uarg, bool all_users);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:757
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff8134cc10-ffffffff8134d136: do_remove_key (STB_LOCAL)
ffffffff8134d450-ffffffff8134d461: do_remove_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81392c70)
Location: fs/crypto/keyring.c:901
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff81392c70-ffffffff81392f97: do_remove_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a3fe0)
Location: fs/crypto/keyring.c:911
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff813a3fe0-ffffffff813a42f5: do_remove_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813ab220)
Location: fs/crypto/keyring.c:911
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff813ab220-ffffffff813ab4e2: do_remove_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813faab0)
Location: fs/crypto/keyring.c:911
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff813faab0-ffffffff813fad72: do_remove_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146de20)
Location: fs/crypto/keyring.c:951
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff8146de20-ffffffff8146e0d1: do_remove_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814ff420)
Location: fs/crypto/keyring.c:1008
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff814ff420-ffffffff814ff6b5: do_remove_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81536930)
Location: fs/crypto/keyring.c:1003
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff81536930-ffffffff81536bc9: do_remove_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:1017
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff8156b9c0-ffffffff8156bc71: do_remove_key.isra.0 (STB_LOCAL)
ffffffff821c6f19-ffffffff821c6f2e: do_remove_key.isra.0.cold (STB_LOCAL)
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
int do_remove_key(struct file *filp, void *_uarg, bool all_users);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040da30)
Location: fs/crypto/keyring.c:757
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffff80001040da30-ffff80001040e0a4: do_remove_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_remove_key(struct file *filp, void *_uarg, bool all_users);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05da810)
Location: fs/crypto/keyring.c:757
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
c05da810-c05dad54: do_remove_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_remove_key(struct file *filp, void *_uarg, bool all_users);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051ad90)
Location: fs/crypto/keyring.c:757
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
c00000000051ad90-c00000000051b54c: do_remove_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_remove_key(struct file *filp, void *_uarg, bool all_users);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b6d86)
Location: fs/crypto/keyring.c:757
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffe0002b6d86-ffffffe0002b72a4: do_remove_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int do_remove_key(struct file *filp, void *_uarg, bool all_users);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:757
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff813451f0-ffffffff81345716: do_remove_key (STB_LOCAL)
ffffffff81345a30-ffffffff81345a41: do_remove_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_remove_key(struct file *filp, void *_uarg, bool all_users);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:757
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff81335ed0-ffffffff813363f6: do_remove_key (STB_LOCAL)
ffffffff81336710-ffffffff81336721: do_remove_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_remove_key(struct file *filp, void *_uarg, bool all_users);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:757
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff81342cc0-ffffffff813431e6: do_remove_key (STB_LOCAL)
ffffffff81343500-ffffffff81343511: do_remove_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_remove_key(struct file *filp, void *_uarg, bool all_users);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:757
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key_all_users
  - fs/crypto/keyring.c:fscrypt_ioctl_remove_key
```
**Symbols:**

```
ffffffff81355fc0-ffffffff813564c7: do_remove_key (STB_LOCAL)
ffffffff813567e0-ffffffff813567f1: do_remove_key.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
