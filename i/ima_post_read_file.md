# Function: <code>ima_post_read_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff813d3b30)
Location: security/integrity/ima/ima_main.c:392
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff813d3b30-ffffffff813d3bc2: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff813eb570)
Location: security/integrity/ima/ima_main.c:394
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff813eb570-ffffffff813eb602: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff813f78a0)
Location: security/integrity/ima/ima_main.c:394
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff813f78a0-ffffffff813f7931: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8141f9c0)
Location: security/integrity/ima/ima_main.c:397
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff8141f9c0-ffffffff8141fa58: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81451f20)
Location: security/integrity/ima/ima_main.c:467
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff81451f20-ffffffff81452030: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:467
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff8146f02f-ffffffff8146f045: ima_post_read_file.cold.2 (STB_LOCAL)
ffffffff8146eea0-ffffffff8146efa1: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:527
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff8149cadb-ffffffff8149caf1: ima_post_read_file.cold (STB_LOCAL)
ffffffff8149c8e0-ffffffff8149c9dd: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:547
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff814b6e19-ffffffff814b6e2f: ima_post_read_file.cold (STB_LOCAL)
ffffffff814b6a60-ffffffff814b6b5d: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:646
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff8151661c-ffffffff81516632: ima_post_read_file.cold (STB_LOCAL)
ffffffff81516250-ffffffff8151634d: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff815333b0)
Location: security/integrity/ima/ima_main.c:708
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff815333b0-ffffffff8153348e: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8153b8e0)
Location: security/integrity/ima/ima_main.c:721
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff8153b8e0-ffffffff8153b9d3: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8159a360)
Location: security/integrity/ima/ima_main.c:738
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff8159a360-ffffffff8159a46a: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8163f070)
Location: security/integrity/ima/ima_main.c:761
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff8163f070-ffffffff8163f198: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f6d70)
Location: security/integrity/ima/ima_main.c:771
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff816f6d70-ffffffff816f6e98: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81730ff0)
Location: security/integrity/ima/ima_main.c:790
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff81730ff0-ffffffff81731116: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81771a60)
Location: security/integrity/ima/ima_main.c:804
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff81771a60-ffffffff81771b7e: ima_post_read_file (STB_GLOBAL)
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
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffff8000105aed30)
Location: security/integrity/ima/ima_main.c:547
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffff8000105aed30-ffff8000105aee58: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c075e410)
Location: security/integrity/ima/ima_main.c:547
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
c075e410-c075e56c: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c00000000072de30)
Location: security/integrity/ima/ima_main.c:547
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
c00000000072de30-c00000000072dfe8: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffe0003f6d30)
Location: security/integrity/ima/ima_main.c:547
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffe0003f6d30-ffffffe0003f6e02: ima_post_read_file (STB_GLOBAL)
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
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:547
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff814af3f9-ffffffff814af40f: ima_post_read_file.cold (STB_LOCAL)
ffffffff814af040-ffffffff814af13d: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:547
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff8149fe19-ffffffff8149fe2f: ima_post_read_file.cold (STB_LOCAL)
ffffffff8149fa60-ffffffff8149fb5d: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:547
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff814ab489-ffffffff814ab49f: ima_post_read_file.cold (STB_LOCAL)
ffffffff814ab0e0-ffffffff814ab1dd: ima_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_post_read_file(struct file *file, void *buf, loff_t size, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:547
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_read_file
```
**Symbols:**

```
ffffffff814c3ed9-ffffffff814c3eef: ima_post_read_file.cold (STB_LOCAL)
ffffffff814c3b20-ffffffff814c3c1d: ima_post_read_file (STB_GLOBAL)
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
