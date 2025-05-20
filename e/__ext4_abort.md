# Function: <code>__ext4_abort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b88f0)
Location: fs/ext4/super.c:571
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff812b88f0-ffffffff812b8a46: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e7780)
Location: fs/ext4/super.c:600
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff812e7780-ffffffff812e78d6: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fd3f0)
Location: fs/ext4/super.c:602
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
**Symbols:**

```
ffffffff812fd3f0-ffffffff812fd541: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81332070)
Location: fs/ext4/super.c:619
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81332070-ffffffff813321e6: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81356560)
Location: fs/ext4/super.c:618
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81356560-ffffffff813566d6: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:624
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8138baaf-ffffffff8138babb: __ext4_abort.cold.138 (STB_LOCAL)
ffffffff81384890-ffffffff813849eb: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:666
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813a460f-ffffffff813a461b: __ext4_abort.cold.142 (STB_LOCAL)
ffffffff8139d370-ffffffff8139d4cb: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:677
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813ce7f7-ffffffff813ce803: __ext4_abort.cold (STB_LOCAL)
ffffffff813c75a0-ffffffff813c770a: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813e7eb6-ffffffff813e7ec2: __ext4_abort.cold (STB_LOCAL)
ffffffff813e0960-ffffffff813e0aca: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, int error, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:707
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8143497d-ffffffff81434a3d: __ext4_abort.cold (STB_LOCAL)
ffffffff8142d6f0-ffffffff8142d78e: __ext4_abort (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b9cb0)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffff8000104b9cb0-ffff8000104b9e30: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067d330)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
c067d330-c067d4b0: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ef200)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
c0000000005ef200-c0000000005ef3d4: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe00033629c)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffe00033629c-ffffffe0003363d4: __ext4_abort (STB_GLOBAL)
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
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813e0496-ffffffff813e04a2: __ext4_abort.cold (STB_LOCAL)
ffffffff813d8f40-ffffffff813d90aa: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813d0f16-ffffffff813d0f22: __ext4_abort.cold (STB_LOCAL)
ffffffff813c99c0-ffffffff813c9b2a: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813dd816-ffffffff813dd822: __ext4_abort.cold (STB_LOCAL)
ffffffff813d63d0-ffffffff813d653a: __ext4_abort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ext4_abort(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813f2c42-ffffffff813f2c4e: __ext4_abort.cold (STB_LOCAL)
ffffffff813eb680-ffffffff813eb7ea: __ext4_abort (STB_GLOBAL)
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
<code>int error</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, function, line, fmt, (anon)</code> ➡️ <code>sb, function, line, error, fmt, (anon)</code>
</li>
</ul>
</details>
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
