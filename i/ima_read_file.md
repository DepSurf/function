# Function: <code>ima_read_file</code>

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
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff813d3af0)
Location: security/integrity/ima/ima_main.c:358
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff813d3af0-ffffffff813d3b22: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff813eb530)
Location: security/integrity/ima/ima_main.c:360
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff813eb530-ffffffff813eb562: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff813f7860)
Location: security/integrity/ima/ima_main.c:360
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff813f7860-ffffffff813f7892: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8141f970)
Location: security/integrity/ima/ima_main.c:363
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff8141f970-ffffffff8141f9b3: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:430
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff81452030-ffffffff81452046: ima_read_file.cold.2 (STB_LOCAL)
ffffffff81451ed0-ffffffff81451f1a: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8146ee90)
Location: security/integrity/ima/ima_main.c:432
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff8146ee90-ffffffff8146ee9d: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8149c8d0)
Location: security/integrity/ima/ima_main.c:492
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff8149c8d0-ffffffff8149c8dd: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814b6a50)
Location: security/integrity/ima/ima_main.c:512
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff814b6a50-ffffffff814b6a5d: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81516240)
Location: security/integrity/ima/ima_main.c:611
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff81516240-ffffffff8151624d: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81533320)
Location: security/integrity/ima/ima_main.c:658
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff81533320-ffffffff815333af: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8153b830)
Location: security/integrity/ima/ima_main.c:671
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff8153b830-ffffffff8153b8d4: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8159a2b0)
Location: security/integrity/ima/ima_main.c:688
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff8159a2b0-ffffffff8159a354: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8163efa0)
Location: security/integrity/ima/ima_main.c:711
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff8163efa0-ffffffff8163f062: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f6c90)
Location: security/integrity/ima/ima_main.c:721
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff816f6c90-ffffffff816f6d52: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81730f10)
Location: security/integrity/ima/ima_main.c:740
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff81730f10-ffffffff81730fd2: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81771990)
Location: security/integrity/ima/ima_main.c:754
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff81771990-ffffffff81771a4a: ima_read_file (STB_GLOBAL)
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
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffff8000105aed10)
Location: security/integrity/ima/ima_main.c:512
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffff8000105aed10-ffff8000105aed2c: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c075e3f4)
Location: security/integrity/ima/ima_main.c:512
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
c075e3f4-c075e410: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c00000000072de20)
Location: security/integrity/ima/ima_main.c:512
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
c00000000072de20-c00000000072de30: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffe0003f6d14)
Location: security/integrity/ima/ima_main.c:512
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffe0003f6d14-ffffffe0003f6d30: ima_read_file (STB_GLOBAL)
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
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814af030)
Location: security/integrity/ima/ima_main.c:512
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff814af030-ffffffff814af03d: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8149fa50)
Location: security/integrity/ima/ima_main.c:512
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff8149fa50-ffffffff8149fa5d: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814ab0d0)
Location: security/integrity/ima/ima_main.c:512
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff814ab0d0-ffffffff814ab0dd: ima_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ima_read_file(struct file *file, enum kernel_read_file_id read_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814c3b10)
Location: security/integrity/ima/ima_main.c:512
Inline: False
Direct callers:
  - security/security.c:security_kernel_read_file
```
**Symbols:**

```
ffffffff814c3b10-ffffffff814c3b1d: ima_read_file (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool contents</code>
</li>
</ul>
</details>
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
