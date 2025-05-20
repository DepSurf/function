# Function: <code>fat_ent_access_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff812f9790)
Location: fs/fat/fatent.c:286
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff812f9790-ffffffff812f9813: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8132d3c0)
Location: fs/fat/fatent.c:286
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff8132d3c0-ffffffff8132d443: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81343100)
Location: fs/fat/fatent.c:286
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81343100-ffffffff81343183: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81357b60)
Location: fs/fat/fatent.c:286
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81357b60-ffffffff81357be3: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8137c810)
Location: fs/fat/fatent.c:286
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff8137c810-ffffffff8137c893: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813ab2a0)
Location: fs/fat/fatent.c:286
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff813ab2a0-ffffffff813ab323: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff813c5419-ffffffff813c5435: fat_ent_access_init.cold.21 (STB_LOCAL)
ffffffff813c4100-ffffffff813c418f: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff813eff2a-ffffffff813eff46: fat_ent_access_init.cold (STB_LOCAL)
ffffffff813ee9e0-ffffffff813eea6f: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81409e15-ffffffff81409e31: fat_ent_access_init.cold (STB_LOCAL)
ffffffff81408a50-ffffffff81408adf: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81457aa3-ffffffff81457abf: fat_ent_access_init.cold (STB_LOCAL)
ffffffff814566a0-ffffffff8145672f: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81bed851-ffffffff81bed86d: fat_ent_access_init.cold (STB_LOCAL)
ffffffff81472a60-ffffffff81472aef: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81bdf951-ffffffff81bdf96d: fat_ent_access_init.cold (STB_LOCAL)
ffffffff81478480-ffffffff8147850f: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:288
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81ccfbfc-ffffffff81ccfc18: fat_ent_access_init.cold (STB_LOCAL)
ffffffff814cf860-ffffffff814cf8ef: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:289
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81e82e3d-ffffffff81e82e59: fat_ent_access_init.cold (STB_LOCAL)
ffffffff8155c2f0-ffffffff8155c3a9: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff815fe220)
Location: fs/fat/fatent.c:289
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff815fe220-ffffffff815fe2f7: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff816361f0)
Location: fs/fat/fatent.c:289
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff816361f0-ffffffff816362c7: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8166f6e0)
Location: fs/fat/fatent.c:289
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff8166f6e0-ffffffff8166f7b7: fat_ent_access_init (STB_GLOBAL)
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
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffff8000104e9170)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffff8000104e9170-ffff8000104e9244: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c06a6e4c)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
c06a6e4c-c06a6ef0: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c000000000626a90)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
c000000000626a90-c000000000626b98: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffe00035a2fc)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffe00035a2fc-ffffffe00035a3bc: fat_ent_access_init (STB_GLOBAL)
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
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff814023f5-ffffffff81402411: fat_ent_access_init.cold (STB_LOCAL)
ffffffff81401030-ffffffff814010bf: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff813f2e75-ffffffff813f2e91: fat_ent_access_init.cold (STB_LOCAL)
ffffffff813f1ab0-ffffffff813f1b3f: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff813ff775-ffffffff813ff791: fat_ent_access_init.cold (STB_LOCAL)
ffffffff813fe3b0-ffffffff813fe43f: fat_ent_access_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fat_ent_access_init(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:287
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff814153a0-ffffffff814153bc: fat_ent_access_init.cold (STB_LOCAL)
ffffffff81413fd0-ffffffff8141405f: fat_ent_access_init (STB_GLOBAL)
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
