# Function: <code>ext4_setup_system_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff812d62a0)
Location: fs/ext4/block_validity.c:139
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812d62a0-ffffffff812d6492: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81305f40)
Location: fs/ext4/block_validity.c:139
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81305f40-ffffffff8130612e: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff8131bf00)
Location: fs/ext4/block_validity.c:139
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8131bf00-ffffffff8131c0ee: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff812e4ac0)
Location: fs/ext4/block_validity.c:139
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812e4ac0-ffffffff812e4cb4: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813094f0)
Location: fs/ext4/block_validity.c:140
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813094f0-ffffffff813096e4: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:140
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813376fe-ffffffff81337774: ext4_setup_system_zone.cold.4 (STB_LOCAL)
ffffffff81337430-ffffffff813375c1: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:140
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8134e97e-ffffffff8134e9f4: ext4_setup_system_zone.cold.4 (STB_LOCAL)
ffffffff8134e6b0-ffffffff8134e841: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:183
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813774d8-ffffffff8137754f: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff813770c0-ffffffff81377407: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:253
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8138f833-ffffffff8138f8aa: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff8138f340-ffffffff8138f6e3: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:247
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813dad69-ffffffff813dade4: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff813da850-ffffffff813dabc3: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:211
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81bec23a-ffffffff81bec2ba: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff813ec520-ffffffff813ec893: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:211
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81bde2c1-ffffffff81bde341: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff813f2a60-ffffffff813f2dd3: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:211
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81cc8cee-ffffffff81cc8da4: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff81444a40-ffffffff81444dcf: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:211
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff81e7ba25-ffffffff81e7bada: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff814c09e0-ffffffff814c0daf: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:211
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff8206c18e-ffffffff8206c1c4: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff81558ac0-ffffffff81558f12: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:211
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff820ec019-ffffffff820ec04b: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff81590910-ffffffff81590d6f: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:211
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff821c9294-ffffffff821c92a8: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff815c9650-ffffffff815c9aaa: ext4_setup_system_zone (STB_GLOBAL)
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
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffff800010461bd8)
Location: fs/ext4/block_validity.c:253
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffff800010461bd8-ffff800010461fd0: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c06220cc)
Location: fs/ext4/block_validity.c:253
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c06220cc-c06225a0: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c00000000057e380)
Location: fs/ext4/block_validity.c:253
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c00000000057e380-c00000000057e920: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffe0002f0b2a)
Location: fs/ext4/block_validity.c:253
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe0002f0b2a-ffffffe0002f0e96: ext4_setup_system_zone (STB_GLOBAL)
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
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:253
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81387e13-ffffffff81387e8a: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff81387920-ffffffff81387cc3: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:253
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813788a3-ffffffff8137891a: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff813783b0-ffffffff81378753: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:253
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813858e3-ffffffff8138595a: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff813853f0-ffffffff81385793: ext4_setup_system_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ext4_setup_system_zone(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (0)
Location: fs/ext4/block_validity.c:253
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81399468-ffffffff813994df: ext4_setup_system_zone.cold (STB_LOCAL)
ffffffff81398f70-ffffffff8139930e: ext4_setup_system_zone (STB_GLOBAL)
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
