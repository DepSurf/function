# Function: <code>generic_shutdown_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120e8e0)
Location: fs/super.c:413
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/super.c:kill_block_super
```
**Symbols:**

```
ffffffff8120e8e0-ffffffff8120e9d1: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235310)
Location: fs/super.c:417
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81235310-ffffffff81235404: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81247eb0)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81247eb0-ffffffff81247fa4: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812536c0)
Location: fs/super.c:415
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff812536c0-ffffffff812537d7: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81275740)
Location: fs/super.c:419
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81275740-ffffffff8127585a: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:433
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff8129e407-ffffffff8129e41f: generic_shutdown_super.cold.23 (STB_LOCAL)
ffffffff8129ca40-ffffffff8129cb46: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:437
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812b33da-ffffffff812b33f2: generic_shutdown_super.cold.24 (STB_LOCAL)
ffffffff812b1c00-ffffffff812b1d06: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:438
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812d0050-ffffffff812d0068: generic_shutdown_super.cold (STB_LOCAL)
ffffffff812ce990-ffffffff812cea96: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812e1c01-ffffffff812e1c19: generic_shutdown_super.cold (STB_LOCAL)
ffffffff812e0410-ffffffff812e0516: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81318e71-ffffffff81318e89: generic_shutdown_super.cold (STB_LOCAL)
ffffffff813170d0-ffffffff813171d6: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81bea53d-ffffffff81bea555: generic_shutdown_super.cold (STB_LOCAL)
ffffffff813225e0-ffffffff813226e6: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81bdc579-ffffffff81bdc591: generic_shutdown_super.cold (STB_LOCAL)
ffffffff81328550-ffffffff8132865e: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81cc3871-ffffffff81cc3889: generic_shutdown_super.cold (STB_LOCAL)
ffffffff81375b20-ffffffff81375c2e: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:439
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81e75fa8-ffffffff81e75fc0: generic_shutdown_super.cold (STB_LOCAL)
ffffffff813f3eb0-ffffffff813f3fdc: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147ce70)
Location: fs/super.c:468
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff8147ce70-ffffffff8147d01e: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b1c40)
Location: fs/super.c:466
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff814b1c40-ffffffff814b1dee: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e3420)
Location: fs/super.c:614
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff814e3420-ffffffff814e359a: generic_shutdown_super (STB_GLOBAL)
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
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388058)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffff800010388058-ffff8000103881a0: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056eb7c)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
  - drivers/mtd/mtdsuper.c:kill_mtd_super
```
**Symbols:**

```
c056eb7c-c056ec9c: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047bfc0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
c00000000047bfc0-c00000000047c168: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000259b1c)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffe000259b1c-ffffffe000259c52: generic_shutdown_super (STB_GLOBAL)
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
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812da1e1-ffffffff812da1f9: generic_shutdown_super.cold (STB_LOCAL)
ffffffff812d89f0-ffffffff812d8af6: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812cae61-ffffffff812cae79: generic_shutdown_super.cold (STB_LOCAL)
ffffffff812c9670-ffffffff812c9776: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812d7ff1-ffffffff812d8009: generic_shutdown_super.cold (STB_LOCAL)
ffffffff812d6800-ffffffff812d6906: generic_shutdown_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void generic_shutdown_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:442
Inline: False
Direct callers:
  - fs/super.c:kill_block_super
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812e8d7b-ffffffff812e8d93: generic_shutdown_super.cold (STB_LOCAL)
ffffffff812e66d0-ffffffff812e67d4: generic_shutdown_super (STB_GLOBAL)
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
