# Function: <code>integrity_kernel_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, char *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81396440)
Location: security/integrity/iint.c:182
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_read_file
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff81396440-ffffffff81396499: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, char *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff813d21c0)
Location: security/integrity/iint.c:184
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_read_file
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff813d21c0-ffffffff813d2219: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, char *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff813e98e0)
Location: security/integrity/iint.c:184
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_read_file
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff813e98e0-ffffffff813e9939: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff813f5ce0)
Location: security/integrity/iint.c:184
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_read_file
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff813f5ce0-ffffffff813f5d3b: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8141ddd0)
Location: security/integrity/iint.c:184
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff8141ddd0-ffffffff8141de35: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81450080)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff81450080-ffffffff814500e5: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8146d060)
Location: security/integrity/iint.c:192
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
**Symbols:**

```
ffffffff8146d060-ffffffff8146d0c5: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8149a750)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff8149a750-ffffffff8149a7b5: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff814b4950)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff814b4950-ffffffff814b49b5: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81513ee0)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff81513ee0-ffffffff81513f02: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81531040)
Location: security/integrity/iint.c:196
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff81531040-ffffffff81531062: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81539470)
Location: security/integrity/iint.c:196
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff81539470-ffffffff81539492: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81597cb0)
Location: security/integrity/iint.c:196
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff81597cb0-ffffffff81597cd2: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8163c490)
Location: security/integrity/iint.c:196
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff8163c490-ffffffff8163c4be: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff816f3cd0)
Location: security/integrity/iint.c:196
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff816f3cd0-ffffffff816f3cfe: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8172de00)
Location: security/integrity/iint.c:192
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff8172de00-ffffffff8172de2e: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8176e760)
Location: security/integrity/iint.c:218
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff8176e760-ffffffff8176e78e: integrity_kernel_read (STB_GLOBAL)
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
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffff8000105ac9a0)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffff8000105ac9a0-ffff8000105aca7c: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (c075c328)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
c075c328-c075c3a4: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (c00000000072aea0)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
c00000000072aea0-c00000000072af58: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffe0003f5136)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffe0003f5136-ffffffe0003f5196: integrity_kernel_read (STB_GLOBAL)
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
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff814acf30)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff814acf30-ffffffff814acf95: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8149d950)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff8149d950-ffffffff8149d9b5: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff814a8fd0)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff814a8fd0-ffffffff814a9035: integrity_kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int integrity_kernel_read(struct file *file, loff_t offset, void *addr, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff814c19e0)
Location: security/integrity/iint.c:188
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff814c19e0-ffffffff814c1a45: integrity_kernel_read (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *addr</code> ➡️ <code>void *addr</code>
</li>
</ul>
</details>
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
