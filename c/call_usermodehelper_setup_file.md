# Function: <code>call_usermodehelper_setup_file</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a9b10)
Location: kernel/umh.c:403
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffff810a9b10-ffffffff810a9b89: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b2a50)
Location: kernel/umh.c:407
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffff810b2a50-ffffffff810b2b15: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b85e0)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffff810b85e0-ffffffff810b86b1: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810beae0)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffff810beae0-ffffffff810bebb1: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c5d70)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffff810c5d70-ffffffff810c5e41: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffff80001011b4f8)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffff80001011b4f8-ffff80001011b5c8: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c036f9f8)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
c036f9f8-c036fac4: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c0000000001632c0)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
c0000000001632c0-c0000000001633f4: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffe0000d5aa2)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffe0000d5aa2-ffffffe0000d5b68: call_usermodehelper_setup_file (STB_GLOBAL)
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
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b8e50)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffff810b8e50-ffffffff810b8f21: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a7790)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffff810a7790-ffffffff810a7861: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b83b0)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffff810b83b0-ffffffff810b8481: call_usermodehelper_setup_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct subprocess_info *call_usermodehelper_setup_file(struct file *file, int (*init)(struct subprocess_info *, struct cred *), void (*cleanup)(struct subprocess_info *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c0700)
Location: kernel/umh.c:408
Inline: False
Direct callers:
  - kernel/umh.c:fork_usermode_blob
```
**Symbols:**

```
ffffffff810c0700-ffffffff810c07d1: call_usermodehelper_setup_file (STB_GLOBAL)
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
