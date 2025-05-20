# Function: <code>aa_file_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813886b0)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:match_file
  - security/apparmor/file.c:aa_inherit_files
```
**Symbols:**

```
ffffffff813886b0-ffffffff81388adf: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813c3240)
Location: security/apparmor/file.c:595
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff813c3240-ffffffff813c3625: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813da750)
Location: security/apparmor/file.c:600
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff813da750-ffffffff813dabbd: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813eb880)
Location: security/apparmor/file.c:607
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff813eb880-ffffffff813ebc1a: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814131c0)
Location: security/apparmor/file.c:601
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff814131c0-ffffffff8141355a: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81445540)
Location: security/apparmor/file.c:601
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff81445540-ffffffff814458b4: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81462430)
Location: security/apparmor/file.c:602
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff81462430-ffffffff814627b9: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8148f700)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff8148f700-ffffffff8148fa7a: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814a95c0)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff814a95c0-ffffffff814a993a: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request, bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81507000)
Location: security/apparmor/file.c:609
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff81507000-ffffffff8150728d: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request, bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff815240f0)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff815240f0-ffffffff81524338: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request, bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8152a2e0)
Location: security/apparmor/file.c:600
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff8152a2e0-ffffffff8152a520: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request, bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81588680)
Location: security/apparmor/file.c:600
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff81588680-ffffffff815888c0: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request, bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81628c90)
Location: security/apparmor/file.c:616
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff81628c90-ffffffff81628f61: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_file_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, struct file *file, u32 request, bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff816dd510)
Location: security/apparmor/file.c:761
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff816dd510-ffffffff816dd7f6: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_file_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, struct file *file, u32 request, bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81716b20)
Location: security/apparmor/file.c:781
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff81716b20-ffffffff81716e07: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_file_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, struct file *file, u32 request, bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81755680)
Location: security/apparmor/file.c:801
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff81755680-ffffffff81755967: aa_file_perm (STB_GLOBAL)
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
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffff80001059ff80)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffff80001059ff80-ffff8000105a0330: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (c0750c00)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
c0750c00-c0750fc0: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (c00000000071a0d0)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
c00000000071a0d0-c00000000071a5b8: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffe0003eb062)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffe0003eb062-ffffffe0003eb304: aa_file_perm (STB_GLOBAL)
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
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814a1ba0)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff814a1ba0-ffffffff814a1f1a: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814925c0)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff814925c0-ffffffff8149293a: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8149dc40)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff8149dc40-ffffffff8149dfba: aa_file_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_file_perm(const char *op, struct aa_label *label, struct file *file, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814b6200)
Location: security/apparmor/file.c:598
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:match_file
```
**Symbols:**

```
ffffffff814b6200-ffffffff814b65a4: aa_file_perm (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool in_atomic</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, label, file, request, in_atomic</code> ➡️ <code>op, subj_cred, label, file, request, in_atomic</code>
</li>
</ul>
</details>
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
