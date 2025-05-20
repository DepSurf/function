# Function: <code>simple_transaction_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234bf0)
Location: fs/libfs.c:695
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff81234bf0-ffffffff81234ca9: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125d100)
Location: fs/libfs.c:723
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff8125d100-ffffffff8125d1cf: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81270630)
Location: fs/libfs.c:731
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff81270630-ffffffff812706ff: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127dd10)
Location: fs/libfs.c:732
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff8127dd10-ffffffff8127ddd6: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812a07f0)
Location: fs/libfs.c:732
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff812a07f0-ffffffff812a08b6: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c7520)
Location: fs/libfs.c:732
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff812c7520-ffffffff812c75fb: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dc650)
Location: fs/libfs.c:732
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff812dc650-ffffffff812dc72b: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fad10)
Location: fs/libfs.c:751
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff812fad10-ffffffff812fadee: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130cf40)
Location: fs/libfs.c:789
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff8130cf40-ffffffff8130d01e: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/libfs.c (ffffffff81346970)
Location: fs/libfs.c:825
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff81346970-ffffffff81346a3f: simple_transaction_get.part.0 (STB_LOCAL)
ffffffff81346a40-ffffffff81346a61: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/libfs.c (ffffffff81352e60)
Location: fs/libfs.c:827
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff81352e60-ffffffff81352f2f: simple_transaction_get.part.0 (STB_LOCAL)
ffffffff81352f30-ffffffff81352f51: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81359a30)
Location: fs/libfs.c:830
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff81359a30-ffffffff81359b0e: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a7ed0)
Location: fs/libfs.c:839
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff813a7ed0-ffffffff813a7fae: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142b390)
Location: fs/libfs.c:866
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff8142b390-ffffffff8142b491: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8530)
Location: fs/libfs.c:867
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff814b8530-ffffffff814b8631: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ed740)
Location: fs/libfs.c:862
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff814ed740-ffffffff814ed841: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff815214a0)
Location: fs/libfs.c:1132
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff815214a0-ffffffff815215a1: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c12e0)
Location: fs/libfs.c:789
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffff8000103c12e0-ffff8000103c1418: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059e080)
Location: fs/libfs.c:789
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
c059e080-c059e1bc: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004c01e0)
Location: fs/libfs.c:789
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
c0000000004c01e0-c0000000004c036c: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000281a98)
Location: fs/libfs.c:789
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffe000281a98-ffffffe000281bc4: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81305520)
Location: fs/libfs.c:789
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff81305520-ffffffff813055fe: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f6140)
Location: fs/libfs.c:789
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff812f6140-ffffffff812f621e: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81303310)
Location: fs/libfs.c:789
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff81303310-ffffffff813033ee: simple_transaction_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *simple_transaction_get(struct file *file, const char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313d90)
Location: fs/libfs.c:789
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:selinux_transaction_write
```
**Symbols:**

```
ffffffff81313d90-ffffffff81313e71: simple_transaction_get (STB_GLOBAL)
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
