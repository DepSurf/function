# Function: <code>ext4_decode_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7dd0)
Location: fs/ext4/super.c:495
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff812b7dd0-ffffffff812b7e8f: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e6ad0)
Location: fs/ext4/super.c:524
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff812e6ad0-ffffffff812e6b8f: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fc680)
Location: fs/ext4/super.c:526
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff812fc680-ffffffff812fc73f: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813312d0)
Location: fs/ext4/super.c:540
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff813312d0-ffffffff81331371: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81355790)
Location: fs/ext4/super.c:540
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff81355790-ffffffff81355831: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81383bc0)
Location: fs/ext4/super.c:546
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff81383bc0-ffffffff81383c5f: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139c6a0)
Location: fs/ext4/super.c:588
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff8139c6a0-ffffffff8139c73f: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c68f0)
Location: fs/ext4/super.c:599
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff813c68f0-ffffffff813c6997: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dfcb0)
Location: fs/ext4/super.c:594
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff813dfcb0-ffffffff813dfd57: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142c570)
Location: fs/ext4/super.c:629
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff8142c570-ffffffff8142c61f: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81445390)
Location: fs/ext4/super.c:826
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff81445390-ffffffff8144543f: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144acb0)
Location: fs/ext4/super.c:835
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff8144acb0-ffffffff8144ad5f: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149ebc0)
Location: fs/ext4/super.c:834
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff8149ebc0-ffffffff8149ec6f: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815252c0)
Location: fs/ext4/super.c:859
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff815252c0-ffffffff815253a8: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c2890)
Location: fs/ext4/super.c:852
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff815c2890-ffffffff815c2978: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fa010)
Location: fs/ext4/super.c:852
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff815fa010-ffffffff815fa0d9: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81632c10)
Location: fs/ext4/super.c:921
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff81632c10-ffffffff81632cd9: ext4_decode_error (STB_GLOBAL)
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
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b8c60)
Location: fs/ext4/super.c:594
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffff8000104b8c60-ffff8000104b8d6c: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067c2c8)
Location: fs/ext4/super.c:594
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
c067c2c8-c067c3c0: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005edd00)
Location: fs/ext4/super.c:594
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
c0000000005edd00-c0000000005ede14: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000335620)
Location: fs/ext4/super.c:594
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffe000335620-ffffffe0003356f0: ext4_decode_error (STB_GLOBAL)
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
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8290)
Location: fs/ext4/super.c:594
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff813d8290-ffffffff813d8337: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c8d10)
Location: fs/ext4/super.c:594
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff813c8d10-ffffffff813c8db7: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d5720)
Location: fs/ext4/super.c:594
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff813d5720-ffffffff813d57c7: ext4_decode_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_decode_error(struct super_block *sb, int errno, char *nbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ea9a0)
Location: fs/ext4/super.c:594
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_std_error
```
**Symbols:**

```
ffffffff813ea9a0-ffffffff813eaa47: ext4_decode_error (STB_GLOBAL)
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
