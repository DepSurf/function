# Function: <code>__file_path_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8138888f)
Location: security/apparmor/file.c:502
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813c3400)
Location: security/apparmor/file.c:514
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813da912)
Location: security/apparmor/file.c:514
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813eb946)
Location: security/apparmor/file.c:519
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81413286)
Location: security/apparmor/file.c:513
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814455f6)
Location: security/apparmor/file.c:513
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814624ed)
Location: security/apparmor/file.c:514
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8148f7bc)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814a967c)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __file_path_perm(const char *op, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81506a00)
Location: security/apparmor/file.c:518
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81506a00-ffffffff81506d7d: __file_path_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __file_path_perm(const char *op, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81523af0)
Location: security/apparmor/file.c:507
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81523af0-ffffffff81523e6d: __file_path_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __file_path_perm(const char *op, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81529cd0)
Location: security/apparmor/file.c:509
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81529cd0-ffffffff8152a05c: __file_path_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __file_path_perm(const char *op, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81588070)
Location: security/apparmor/file.c:509
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81588070-ffffffff815883fc: __file_path_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __file_path_perm(const char *op, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81628740)
Location: security/apparmor/file.c:471
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81628740-ffffffff81628a0f: __file_path_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __file_path_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff816dcee0)
Location: security/apparmor/file.c:606
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff816dcee0-ffffffff816dd1ef: __file_path_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __file_path_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff817164e0)
Location: security/apparmor/file.c:626
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff817164e0-ffffffff817167f2: __file_path_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __file_path_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81754fb0)
Location: security/apparmor/file.c:633
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81754fb0-ffffffff817552c2: __file_path_perm (STB_LOCAL)
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
In security/apparmor/file.c (ffff8000105a0058)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
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
In security/apparmor/file.c (c0750cd8)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
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
In security/apparmor/file.c (c00000000071a210)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
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
In security/apparmor/file.c (ffffffe0003eb112)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
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
In security/apparmor/file.c (ffffffff814a1c5c)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
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
In security/apparmor/file.c (ffffffff8149267c)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
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
In security/apparmor/file.c (ffffffff8149dcfc)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
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
In security/apparmor/file.c (ffffffff814b62ca)
Location: security/apparmor/file.c:510
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, label, flabel, file, request, denied, in_atomic</code> ➡️ <code>op, subj_cred, label, flabel, file, request, denied, in_atomic</code>
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
