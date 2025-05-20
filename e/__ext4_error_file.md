# Function: <code>__ext4_error_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b8650)
Location: fs/ext4/super.c:458
Inline: False
Direct callers:
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff812b8650-ffffffff812b87fd: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e74e0)
Location: fs/ext4/super.c:487
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff812e74e0-ffffffff812e768d: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fd150)
Location: fs/ext4/super.c:489
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff812fd150-ffffffff812fd2fd: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81331db0)
Location: fs/ext4/super.c:500
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff81331db0-ffffffff81331f74: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81356290)
Location: fs/ext4/super.c:500
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff81356290-ffffffff8135646f: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:505
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff8138b9d3-ffffffff8138baaf: __ext4_error_file.cold.137 (STB_LOCAL)
ffffffff81384620-ffffffff8138479f: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:547
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff813a4533-ffffffff813a460f: __ext4_error_file.cold.141 (STB_LOCAL)
ffffffff8139d100-ffffffff8139d27f: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:558
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff813ce73a-ffffffff813ce7f7: __ext4_error_file.cold (STB_LOCAL)
ffffffff813c7330-ffffffff813c74a8: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:553
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff813e7df9-ffffffff813e7eb6: __ext4_error_file.cold (STB_LOCAL)
ffffffff813e06f0-ffffffff813e0868: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:590
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff814348c0-ffffffff8143497d: __ext4_error_file.cold (STB_LOCAL)
ffffffff8142d450-ffffffff8142d5d1: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:788
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff81bec755-ffffffff81bec809: __ext4_error_file.cold (STB_LOCAL)
ffffffff81446220-ffffffff81446346: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:797
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff81bde807-ffffffff81bde8bb: __ext4_error_file.cold (STB_LOCAL)
ffffffff8144b9d0-ffffffff8144baf6: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:796
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff81ccd947-ffffffff81ccd9fb: __ext4_error_file.cold (STB_LOCAL)
ffffffff8149f9d0-ffffffff8149faf3: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:819
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff81e8081c-ffffffff81e808d9: __ext4_error_file.cold (STB_LOCAL)
ffffffff81526140-ffffffff8152632b: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c3930)
Location: fs/ext4/super.c:812
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff815c3930-ffffffff815c3bd6: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fb080)
Location: fs/ext4/super.c:812
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff815fb080-ffffffff815fb329: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81633c60)
Location: fs/ext4/super.c:881
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff81633c60-ffffffff81633f09: __ext4_error_file (STB_GLOBAL)
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
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b9990)
Location: fs/ext4/super.c:553
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffff8000104b9990-ffff8000104b9bb0: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067cfd0)
Location: fs/ext4/super.c:553
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
c067cfd0-c067d21c: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005eedf0)
Location: fs/ext4/super.c:553
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
c0000000005eedf0-c0000000005ef09c: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000336046)
Location: fs/ext4/super.c:553
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffe000336046-ffffffe0003361e2: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:553
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff813e03d9-ffffffff813e0496: __ext4_error_file.cold (STB_LOCAL)
ffffffff813d8cd0-ffffffff813d8e48: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:553
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff813d0e59-ffffffff813d0f16: __ext4_error_file.cold (STB_LOCAL)
ffffffff813c9750-ffffffff813c98c8: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:553
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff813dd759-ffffffff813dd816: __ext4_error_file.cold (STB_LOCAL)
ffffffff813d6160-ffffffff813d62d8: __ext4_error_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ext4_error_file(struct file *file, const char *function, unsigned int line, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:553
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
**Symbols:**

```
ffffffff813f2b85-ffffffff813f2c42: __ext4_error_file.cold (STB_LOCAL)
ffffffff813eb400-ffffffff813eb58f: __ext4_error_file (STB_GLOBAL)
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
