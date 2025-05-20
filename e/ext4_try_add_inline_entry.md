# Function: <code>ext4_try_add_inline_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812e15e0)
Location: fs/ext4/inline.c:1247
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff812e15e0-ffffffff812e17a9: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81311530)
Location: fs/ext4/inline.c:1247
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff81311530-ffffffff813116f2: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81327440)
Location: fs/ext4/inline.c:1264
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff81327440-ffffffff81327636: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fb290)
Location: fs/ext4/inline.c:1266
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff812fb290-ffffffff812fb49d: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131fa70)
Location: fs/ext4/inline.c:1257
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff8131fa70-ffffffff8131fc7d: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134db70)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff8134db70-ffffffff8134dd86: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81365d10)
Location: fs/ext4/inline.c:1263
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff81365d10-ffffffff81365f26: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138f030)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff8138f030-ffffffff8138f26c: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a7a90)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff813a7a90-ffffffff813a7ccc: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f3ab0)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff813f3ab0-ffffffff813f3d29: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81406240)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff81406240-ffffffff814064b9: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140c720)
Location: fs/ext4/inline.c:1266
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff8140c720-ffffffff8140c995: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145f510)
Location: fs/ext4/inline.c:1283
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff8145f510-ffffffff8145f7e7: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814ddbe0)
Location: fs/ext4/inline.c:1279
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff814ddbe0-ffffffff814ddefa: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81576c30)
Location: fs/ext4/inline.c:1278
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff81576c30-ffffffff81576f4a: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815ae140)
Location: fs/ext4/inline.c:1261
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff815ae140-ffffffff815ae45d: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e6f00)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff815e6f00-ffffffff815e721d: ext4_try_add_inline_entry (STB_GLOBAL)
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
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047b3c0)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffff80001047b3c0-ffff80001047b60c: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063cc6c)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
c063cc6c-c063ceac: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059e770)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
c00000000059e770-c00000000059ea14: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe0003058d0)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffe0003058d0-ffffffe000305a7e: ext4_try_add_inline_entry (STB_GLOBAL)
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
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a0070)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff813a0070-ffffffff813a02ac: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81390b00)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff81390b00-ffffffff81390d3c: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139d8d0)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff8139d8d0-ffffffff8139db0c: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_try_add_inline_entry(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b1e40)
Location: fs/ext4/inline.c:1260
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff813b1e40-ffffffff813b207c: ext4_try_add_inline_entry (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *dir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
</ul>
</details>
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
