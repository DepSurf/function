# Function: <code>ext4_setup_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ba8c0)
Location: fs/ext4/super.c:1931
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812ba8c0-ffffffff812baaa5: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e97f0)
Location: fs/ext4/super.c:2050
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812e97f0-ffffffff812e99d5: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ff560)
Location: fs/ext4/super.c:2075
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812ff560-ffffffff812ff745: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81334350)
Location: fs/ext4/super.c:2133
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81334350-ffffffff81334523: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81358860)
Location: fs/ext4/super.c:2136
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81358860-ffffffff81358a33: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2177
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81387200-ffffffff813873b0: ext4_setup_super (STB_LOCAL)
ffffffff8138bd13-ffffffff8138bd3e: ext4_setup_super.cold.144 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2239
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8139fd10-ffffffff8139fee1: ext4_setup_super (STB_LOCAL)
ffffffff813a4892-ffffffff813a48c0: ext4_setup_super.cold.148 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2283
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813ca060-ffffffff813ca231: ext4_setup_super (STB_LOCAL)
ffffffff813cea71-ffffffff813cea9f: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2286
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813e3360-ffffffff813e3531: ext4_setup_super (STB_LOCAL)
ffffffff813e8130-ffffffff813e815e: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2439
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff814302d0-ffffffff814304ef: ext4_setup_super (STB_LOCAL)
ffffffff81434bb2-ffffffff81434be0: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2644
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81449010-ffffffff8144922a: ext4_setup_super (STB_LOCAL)
ffffffff81bec9ac-ffffffff81bec9da: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2670
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8144e990-ffffffff8144ebac: ext4_setup_super (STB_LOCAL)
ffffffff81bdea5e-ffffffff81bdea8a: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2653
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff814a2460-ffffffff814a26ef: ext4_setup_super (STB_LOCAL)
ffffffff81ccdbdd-ffffffff81ccdc09: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:3034
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff81529780-ffffffff81529a2e: ext4_setup_super (STB_LOCAL)
ffffffff81e80b2b-ffffffff81e80b59: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c7f30)
Location: fs/ext4/super.c:3023
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff815c7f30-ffffffff815c822c: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ffd40)
Location: fs/ext4/super.c:3079
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff815ffd40-ffffffff8160003c: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81638a90)
Location: fs/ext4/super.c:3085
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff81638a90-ffffffff81638d8c: ext4_setup_super (STB_LOCAL)
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
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bc8f8)
Location: fs/ext4/super.c:2286
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffff8000104bc8f8-ffff8000104bcb00: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067ff78)
Location: fs/ext4/super.c:2286
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c067ff78-c06801b4: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f2720)
Location: fs/ext4/super.c:2286
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c0000000005f2720-c0000000005f2968: ext4_setup_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000338622)
Location: fs/ext4/super.c:2286
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe000338622-ffffffe000338802: ext4_setup_super (STB_LOCAL)
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
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2286
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813db940-ffffffff813dbb11: ext4_setup_super (STB_LOCAL)
ffffffff813e0710-ffffffff813e073e: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2286
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813cc3c0-ffffffff813cc591: ext4_setup_super (STB_LOCAL)
ffffffff813d1190-ffffffff813d11be: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2286
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813d8de0-ffffffff813d8fb1: ext4_setup_super (STB_LOCAL)
ffffffff813dda90-ffffffff813ddabe: ext4_setup_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ext4_setup_super(struct super_block *sb, struct ext4_super_block *es, int read_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2286
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813ee0d0-ffffffff813ee2a1: ext4_setup_super (STB_LOCAL)
ffffffff813f2ebc-ffffffff813f2eea: ext4_setup_super.cold (STB_LOCAL)
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
