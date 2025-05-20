# Function: <code>set_encryption_policy</code>

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
In fs/crypto/policy.c (ffffffff8134ee20)
Location: fs/crypto/policy.c:231
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int set_encryption_policy(struct inode *inode, const union fscrypt_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:358
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81394ef0-ffffffff81394fc8: set_encryption_policy (STB_LOCAL)
ffffffff81395729-ffffffff81395785: set_encryption_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int set_encryption_policy(struct inode *inode, const union fscrypt_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:389
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff813a63a0-ffffffff813a6495: set_encryption_policy (STB_LOCAL)
ffffffff81beb23a-ffffffff81beb296: set_encryption_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int set_encryption_policy(struct inode *inode, const union fscrypt_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:389
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff813ad420-ffffffff813ad515: set_encryption_policy (STB_LOCAL)
ffffffff81bdd293-ffffffff81bdd2ef: set_encryption_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int set_encryption_policy(struct inode *inode, const union fscrypt_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:389
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff813fcd90-ffffffff813fce9f: set_encryption_policy (STB_LOCAL)
ffffffff81cc6991-ffffffff81cc6a15: set_encryption_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int set_encryption_policy(struct inode *inode, const union fscrypt_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:410
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81470460-ffffffff814705b6: set_encryption_policy (STB_LOCAL)
ffffffff81e78dbf-ffffffff81e78e45: set_encryption_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int set_encryption_policy(struct inode *inode, const union fscrypt_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:430
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81501e80-ffffffff8150202d: set_encryption_policy (STB_LOCAL)
ffffffff8206a719-ffffffff8206a743: set_encryption_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int set_encryption_policy(struct inode *inode, const union fscrypt_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:429
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff81539520-ffffffff815396cd: set_encryption_policy (STB_LOCAL)
ffffffff820ea527-ffffffff820ea551: set_encryption_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int set_encryption_policy(struct inode *inode, const union fscrypt_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/policy.c (0)
Location: fs/crypto/policy.c:456
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
**Symbols:**

```
ffffffff8156e710-ffffffff8156e8bd: set_encryption_policy (STB_LOCAL)
ffffffff821c70a5-ffffffff821c70cf: set_encryption_policy.cold (STB_LOCAL)
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
In fs/crypto/policy.c (ffff800010410524)
Location: fs/crypto/policy.c:231
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/policy.c (c05dcd68)
Location: fs/crypto/policy.c:231
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/policy.c (c00000000051e03c)
Location: fs/crypto/policy.c:231
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/policy.c (ffffffe0002b8ddc)
Location: fs/crypto/policy.c:231
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/policy.c (ffffffff81347400)
Location: fs/crypto/policy.c:231
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/policy.c (ffffffff813380e0)
Location: fs/crypto/policy.c:231
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/policy.c (ffffffff81344ed0)
Location: fs/crypto/policy.c:231
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
In fs/crypto/policy.c (ffffffff813581b0)
Location: fs/crypto/policy.c:231
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
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
