# Function: <code>ext4_xattr_free_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812dc6a0)
Location: fs/ext4/xattr.c:601
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff812dc6a0-ffffffff812dc700: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130bf30)
Location: fs/ext4/xattr.c:640
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff8130bf30-ffffffff8130bf90: ext4_xattr_free_space (STB_LOCAL)
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
In fs/ext4/xattr.c (ffffffff81324645)
Location: fs/ext4/xattr.c:644
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81339a10)
Location: fs/ext4/xattr.c:1282
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff81339a10-ffffffff81339a70: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8135dd60)
Location: fs/ext4/xattr.c:1303
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff8135dd60-ffffffff8135ddc0: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138c520)
Location: fs/ext4/xattr.c:1331
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff8138c520-ffffffff8138c580: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a5150)
Location: fs/ext4/xattr.c:1323
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813a5150-ffffffff813a51b0: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813cf390)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813cf390-ffffffff813cf3f0: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e8a60)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813e8a60-ffffffff813e8ac0: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81435790)
Location: fs/ext4/xattr.c:1306
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff81435790-ffffffff814357f0: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144e1f0)
Location: fs/ext4/xattr.c:1309
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff8144e1f0-ffffffff8144e250: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81453cf0)
Location: fs/ext4/xattr.c:1309
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff81453cf0-ffffffff81453d56: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a7d90)
Location: fs/ext4/xattr.c:1312
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff814a7d90-ffffffff814a7df6: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8152f670)
Location: fs/ext4/xattr.c:1321
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff8152f670-ffffffff8152f6eb: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815cd8a0)
Location: fs/ext4/xattr.c:1337
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff815cd8a0-ffffffff815cd91b: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81605380)
Location: fs/ext4/xattr.c:1365
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff81605380-ffffffff816053fb: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8163e040)
Location: fs/ext4/xattr.c:1365
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff8163e040-ffffffff8163e0bb: ext4_xattr_free_space (STB_LOCAL)
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
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c17d8)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffff8000104c17d8-ffff8000104c188c: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c06853e0)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
c06853e0-c0685474: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005f8480)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
c0000000005f8480-c0000000005f8518: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033cd36)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffe00033cd36-ffffffe00033cdb4: ext4_xattr_free_space (STB_LOCAL)
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
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e1040)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813e1040-ffffffff813e10a0: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d1ac0)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813d1ac0-ffffffff813d1b20: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813de3c0)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813de3c0-ffffffff813de420: ext4_xattr_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t ext4_xattr_free_space(struct ext4_xattr_entry *last, size_t *min_offs, void *base, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f37e0)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813f37e0-ffffffff813f3840: ext4_xattr_free_space (STB_LOCAL)
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
