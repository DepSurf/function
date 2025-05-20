# Function: <code>ext4_ext_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c7870)
Location: fs/ext4/extents.c:3083
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812c7870-ffffffff812c787b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f7090)
Location: fs/ext4/extents.c:3105
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff812f7090-ffffffff812f709b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130d0a0)
Location: fs/ext4/extents.c:3105
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8130d0a0-ffffffff8130d0ab: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3106
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff812eb830-ffffffff812eb83b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3106
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813102e0-ffffffff813102eb: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3100
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8133e170-ffffffff8133e17b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3162
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813564a0-ffffffff813564ab: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137fe50)
Location: fs/ext4/extents.c:3182
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8137fe50-ffffffff8137fe5b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81398550)
Location: fs/ext4/extents.c:3228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81398550-ffffffff8139855b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3065
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813e45c0-ffffffff813e45cb: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3064
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813f5e70-ffffffff813f5e7b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3067
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813fc1a0-ffffffff813fc1ab: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3105
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8144e510-ffffffff8144e51b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3104
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff814cb130-ffffffff814cb13f: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3109
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff815637d0-ffffffff815637df: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3109
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8159b4c0-ffffffff8159b4cf: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3085
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff815d42e0-ffffffff815d42ef: ext4_ext_release (STB_GLOBAL)
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
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffff80001046b110-ffff80001046b128: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
c062c098-c062c0b0: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c00000000058a440)
Location: fs/ext4/extents.c:3228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
c00000000058a440-c00000000058a44c: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffe0002f883c-ffffffe0002f8856: ext4_ext_release (STB_GLOBAL)
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
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81390b30)
Location: fs/ext4/extents.c:3228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81390b30-ffffffff81390b3b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813815c0)
Location: fs/ext4/extents.c:3228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813815c0-ffffffff813815cb: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138e490)
Location: fs/ext4/extents.c:3228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8138e490-ffffffff8138e49b: ext4_ext_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_ext_release(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a2250)
Location: fs/ext4/extents.c:3228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff813a2250-ffffffff813a225b: ext4_ext_release (STB_GLOBAL)
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
