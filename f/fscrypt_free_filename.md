# Function: <code>fscrypt_free_filename</code>

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
void fscrypt_free_filename(struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81289140)
Location: fs/crypto/fname.c:417
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81289140-ffffffff81289170: fscrypt_free_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fscrypt_free_filename(struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8129ded0)
Location: fs/crypto/fname.c:407
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff8129ded0-ffffffff8129df00: fscrypt_free_filename (STB_GLOBAL)
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
In fs/ext4/namei.c (ffffffff8131aa9f)
Location: include/linux/fscrypt_supp.h:51
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff8133f1df)
Location: include/linux/fscrypt_supp.h:53
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff8136d120)
Location: include/linux/fscrypt_supp.h:92
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813855a0)
Location: include/linux/fscrypt_supp.h:92
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813af577)
Location: include/linux/fscrypt.h:149
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813c84cf)
Location: include/linux/fscrypt.h:160
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81414374)
Location: include/linux/fscrypt.h:187
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142797c)
Location: include/linux/fscrypt.h:213
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142e5f0)
Location: include/linux/fscrypt.h:213
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81482529)
Location: include/linux/fscrypt.h:314
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8153cc15)
Location: include/linux/fscrypt.h:333
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_fname_free_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff815db3c5)
Location: include/linux/fscrypt.h:333
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_fname_free_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff81612e75)
Location: include/linux/fscrypt.h:341
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_fname_free_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8164bc19)
Location: include/linux/fscrypt.h:356
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
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
In fs/ext4/namei.c (ffff80001049fe80)
Location: include/linux/fscrypt.h:160
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (c0661aa8)
Location: include/linux/fscrypt.h:160
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (c0000000005cbeb4)
Location: include/linux/fscrypt.h:160
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffe000322370)
Location: include/linux/fscrypt.h:160
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813c0aaf)
Location: include/linux/fscrypt.h:160
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813b153f)
Location: include/linux/fscrypt.h:160
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813bdf59)
Location: include/linux/fscrypt.h:160
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813d303f)
Location: include/linux/fscrypt.h:160
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
</ul>
