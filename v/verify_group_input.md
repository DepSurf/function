# Function: <code>verify_group_input</code>

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
In fs/ext4/resize.c (ffffffff812c1087)
Location: fs/ext4/resize.c:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_group_add
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
In fs/ext4/resize.c (ffffffff812f0a8c)
Location: fs/ext4/resize.c:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_group_add
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
In fs/ext4/resize.c (ffffffff81306a5c)
Location: fs/ext4/resize.c:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_group_add
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
In fs/ext4/resize.c (ffffffff81321551)
Location: fs/ext4/resize.c:86
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_group_add
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
In fs/ext4/resize.c (ffffffff81345c91)
Location: fs/ext4/resize.c:87
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_group_add
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
In fs/ext4/resize.c (ffffffff81373af1)
Location: fs/ext4/resize.c:88
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_group_add
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
In fs/ext4/resize.c (ffffffff8138bf31)
Location: fs/ext4/resize.c:88
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b3c70)
Location: fs/ext4/resize.c:88
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813b3c70-ffffffff813b40bf: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813ccfb0)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813ccfb0-ffffffff813cd3ff: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8141ab20)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff8141ab20-ffffffff8141afb2: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142e840)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff8142e840-ffffffff8142ece0: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81435740)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff81435740-ffffffff81435bde: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81489200)
Location: fs/ext4/resize.c:120
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff81489200-ffffffff8148969e: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8150c170)
Location: fs/ext4/resize.c:131
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff8150c170-ffffffff8150c61a: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815a6e70)
Location: fs/ext4/resize.c:134
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff815a6e70-ffffffff815a730f: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815dd710)
Location: fs/ext4/resize.c:134
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff815dd710-ffffffff815ddbaf: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:120
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff81616150-ffffffff81616607: verify_group_input (STB_LOCAL)
ffffffff821cd3de-ffffffff821cd3fd: verify_group_input.cold (STB_LOCAL)
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
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a5380)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffff8000104a5380-ffff8000104a57f4: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c066701c)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
c066701c-c0667644: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d2540)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
c0000000005d2540-c0000000005d2a7c: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe0003262a8)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffe0003262a8-ffffffe000326658: verify_group_input (STB_LOCAL)
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
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c5590)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813c5590-ffffffff813c59df: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b6010)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813b6010-ffffffff813b645f: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c2a20)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813c2a20-ffffffff813c2e6f: verify_group_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int verify_group_input(struct super_block *sb, struct ext4_new_group_data *input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813d7bd0)
Location: fs/ext4/resize.c:115
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_group_add
```
**Symbols:**

```
ffffffff813d7bd0-ffffffff813d801f: verify_group_input (STB_LOCAL)
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
