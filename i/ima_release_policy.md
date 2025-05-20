# Function: <code>ima_release_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff81396f20)
Location: security/integrity/ima/ima_fs.c:325
Inline: True
```
**Symbols:**

```
ffffffff81396f20-ffffffff81396fd5: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff813d2850)
Location: security/integrity/ima/ima_fs.c:399
Inline: False
```
**Symbols:**

```
ffffffff813d2850-ffffffff813d2911: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff813ea160)
Location: security/integrity/ima/ima_fs.c:413
Inline: False
```
**Symbols:**

```
ffffffff813ea160-ffffffff813ea243: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff813f6550)
Location: security/integrity/ima/ima_fs.c:408
Inline: False
```
**Symbols:**

```
ffffffff813f6550-ffffffff813f662c: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff8141e660)
Location: security/integrity/ima/ima_fs.c:408
Inline: False
```
**Symbols:**

```
ffffffff8141e660-ffffffff8141e73c: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:412
Inline: False
```
**Symbols:**

```
ffffffff814508f0-ffffffff81450938: ima_release_policy (STB_LOCAL)
ffffffff81450e0a-ffffffff81450eb8: ima_release_policy.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:413
Inline: False
```
**Symbols:**

```
ffffffff8146d8d0-ffffffff8146d918: ima_release_policy (STB_LOCAL)
ffffffff8146ddea-ffffffff8146de98: ima_release_policy.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
ffffffff8149afc0-ffffffff8149b008: ima_release_policy (STB_LOCAL)
ffffffff8149b4b3-ffffffff8149b561: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
ffffffff814b5200-ffffffff814b5248: ima_release_policy (STB_LOCAL)
ffffffff814b56f3-ffffffff814b57a1: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:406
Inline: False
```
**Symbols:**

```
ffffffff815145e0-ffffffff81514628: ima_release_policy (STB_LOCAL)
ffffffff81514d03-ffffffff81514db1: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:410
Inline: False
```
**Symbols:**

```
ffffffff815316c0-ffffffff81531708: ima_release_policy (STB_LOCAL)
ffffffff81bf1a3e-ffffffff81bf1aec: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:410
Inline: False
```
**Symbols:**

```
ffffffff81539b50-ffffffff81539b98: ima_release_policy (STB_LOCAL)
ffffffff81be3a5c-ffffffff81be3b0a: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:410
Inline: False
```
**Symbols:**

```
ffffffff815984c0-ffffffff81598508: ima_release_policy (STB_LOCAL)
ffffffff81cd6c20-ffffffff81cd6cce: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:410
Inline: False
```
**Symbols:**

```
ffffffff8163cd70-ffffffff8163cdc8: ima_release_policy (STB_LOCAL)
ffffffff81e89e6d-ffffffff81e89f01: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff816f46a0)
Location: security/integrity/ima/ima_fs.c:410
Inline: False
```
**Symbols:**

```
ffffffff816f46a0-ffffffff816f47a8: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff8172e7c0)
Location: security/integrity/ima/ima_fs.c:410
Inline: False
```
**Symbols:**

```
ffffffff8172e7c0-ffffffff8172e8c8: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff8176f120)
Location: security/integrity/ima/ima_fs.c:410
Inline: False
```
**Symbols:**

```
ffffffff8176f120-ffffffff8176f228: ima_release_policy (STB_LOCAL)
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
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffff8000105ad938)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
ffff8000105ad938-ffff8000105ada68: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (c075cc7c)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
c075cc7c-c075cd8c: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (c00000000072bd30)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
c00000000072bd30-c00000000072beb0: ima_release_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffe0003f59ea)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
ffffffe0003f59ea-ffffffe0003f5aec: ima_release_policy (STB_LOCAL)
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
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
ffffffff814ad7e0-ffffffff814ad828: ima_release_policy (STB_LOCAL)
ffffffff814adcd3-ffffffff814add81: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
ffffffff8149e200-ffffffff8149e248: ima_release_policy (STB_LOCAL)
ffffffff8149e6f3-ffffffff8149e7a1: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
ffffffff814a9880-ffffffff814a98c8: ima_release_policy (STB_LOCAL)
ffffffff814a9d73-ffffffff814a9e21: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_release_policy(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:409
Inline: False
```
**Symbols:**

```
ffffffff814c2210-ffffffff814c2258: ima_release_policy (STB_LOCAL)
ffffffff814c27c3-ffffffff814c2871: ima_release_policy.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
