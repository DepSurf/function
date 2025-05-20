# Function: <code>fscrypt_ioctl_set_policy</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8129e7d0)
Location: fs/crypto/policy.c:96
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8129e7d0-ffffffff8129ea71: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812ad2d0)
Location: fs/crypto/policy.c:57
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff812ad2d0-ffffffff812ad4d3: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812d15f0)
Location: fs/crypto/policy.c:58
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff812d15f0-ffffffff812d1808: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812fc0e0)
Location: fs/crypto/policy.c:58
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff812fc0e0-ffffffff812fc2e7: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81311950)
Location: fs/crypto/policy.c:58
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81311950-ffffffff81311b57: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81338eb0)
Location: fs/crypto/policy.c:58
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81338eb0-ffffffff813390cf: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:273
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8134f1fd-ffffffff8134f22b: fscrypt_ioctl_set_policy.cold (STB_LOCAL)
ffffffff8134ecb0-ffffffff8134eefe: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81395120)
Location: fs/crypto/policy.c:403
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81395120-ffffffff813952dc: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813a65f0)
Location: fs/crypto/policy.c:436
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff813a65f0-ffffffff813a67ac: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813ad680)
Location: fs/crypto/policy.c:436
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff813ad680-ffffffff813ad843: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813fd000)
Location: fs/crypto/policy.c:436
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff813fd000-ffffffff813fd1c3: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81470750)
Location: fs/crypto/policy.c:457
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff81470750-ffffffff8147094d: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff815021f0)
Location: fs/crypto/policy.c:477
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff815021f0-ffffffff815023ed: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81539890)
Location: fs/crypto/policy.c:476
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff81539890-ffffffff81539a90: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8156ea90)
Location: fs/crypto/policy.c:503
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff8156ea90-ffffffff8156ec90: fscrypt_ioctl_set_policy (STB_GLOBAL)
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
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffff8000104102b8)
Location: fs/crypto/policy.c:273
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffff8000104102b8-ffff800010410624: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c05dcb84)
Location: fs/crypto/policy.c:273
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c05dcb84-c05dce70: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c00000000051dde0)
Location: fs/crypto/policy.c:273
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c00000000051dde0-c00000000051e150: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffe0002b8ca4)
Location: fs/crypto/policy.c:273
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffe0002b8ca4-ffffffe0002b8e70: fscrypt_ioctl_set_policy (STB_GLOBAL)
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
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:273
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813477dd-ffffffff8134780b: fscrypt_ioctl_set_policy.cold (STB_LOCAL)
ffffffff81347290-ffffffff813474de: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:273
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813384bd-ffffffff813384eb: fscrypt_ioctl_set_policy.cold (STB_LOCAL)
ffffffff81337f70-ffffffff813381be: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:273
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813452ad-ffffffff813452db: fscrypt_ioctl_set_policy.cold (STB_LOCAL)
ffffffff81344d60-ffffffff81344fae: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fscrypt_ioctl_set_policy(struct file *filp, const void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:273
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8135858d-ffffffff813585bb: fscrypt_ioctl_set_policy.cold (STB_LOCAL)
ffffffff81358040-ffffffff8135828e: fscrypt_ioctl_set_policy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
