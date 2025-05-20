# Function: <code>ext4_fname_setup_ci_filename</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ac7e0)
Location: fs/ext4/namei.c:1310
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff813ac7e0-ffffffff813ac864: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c5710)
Location: fs/ext4/namei.c:1310
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff813c5710-ffffffff813c57ab: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81411b80)
Location: fs/ext4/namei.c:1314
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff81411b80-ffffffff81411c1b: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81425030)
Location: fs/ext4/namei.c:1303
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff81425030-ffffffff814250bd: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct ext4_filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142bcb0)
Location: fs/ext4/namei.c:1372
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff8142bcb0-ffffffff8142bdce: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct ext4_filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147fb50)
Location: fs/ext4/namei.c:1373
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff8147fb50-ffffffff8147fc6e: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct ext4_filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81502be0)
Location: fs/ext4/namei.c:1419
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff81502be0-ffffffff81502cf9: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct ext4_filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159d6f0)
Location: fs/ext4/namei.c:1424
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff8159d6f0-ffffffff8159d809: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct ext4_filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d3f40)
Location: fs/ext4/namei.c:1441
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff815d3f40-ffffffff815d406f: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct ext4_filename *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160c5b0)
Location: fs/ext4/namei.c:1445
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff8160c5b0-ffffffff8160c711: ext4_fname_setup_ci_filename (STB_GLOBAL)
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
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049d248)
Location: fs/ext4/namei.c:1310
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffff80001049d248-ffff80001049d2f4: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065f064)
Location: fs/ext4/namei.c:1310
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
c065f064-c065f108: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c8600)
Location: fs/ext4/namei.c:1310
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
c0000000005c8600-c0000000005c872c: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000320070)
Location: fs/ext4/namei.c:1310
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffe000320070-ffffffe000320112: ext4_fname_setup_ci_filename (STB_GLOBAL)
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
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bdcf0)
Location: fs/ext4/namei.c:1310
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff813bdcf0-ffffffff813bdd8b: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ae780)
Location: fs/ext4/namei.c:1310
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff813ae780-ffffffff813ae81b: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_setup_ci_filename(struct inode *dir, const struct qstr *iname, struct fscrypt_str *cf_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d0280)
Location: fs/ext4/namei.c:1310
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
  - fs/ext4/namei.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff813d0280-ffffffff813d031b: ext4_fname_setup_ci_filename (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ext4_filename *name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fscrypt_str *cf_name</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
