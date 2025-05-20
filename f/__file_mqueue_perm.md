# Function: <code>__file_mqueue_perm</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __file_mqueue_perm(const char *op, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81627b90)
Location: security/apparmor/file.c:553
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81627b90-ffffffff81627e14: __file_mqueue_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __file_mqueue_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff816dc1e0)
Location: security/apparmor/file.c:696
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff816dc1e0-ffffffff816dc464: __file_mqueue_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __file_mqueue_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81715710)
Location: security/apparmor/file.c:716
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81715710-ffffffff8171599e: __file_mqueue_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __file_mqueue_perm(const char *op, const struct cred *subj_cred, struct aa_label *label, struct aa_label *flabel, struct file *file, u32 request, u32 denied, bool in_atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81754200)
Location: security/apparmor/file.c:723
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81754200-ffffffff8175448e: __file_mqueue_perm (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
