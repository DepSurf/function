# Function: <code>fat_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fbb70)
Location: fs/fat/inode.c:569
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff812fbb70-ffffffff812fbc49: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8132f730)
Location: fs/fat/inode.c:652
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff8132f730-ffffffff8132f806: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81345490)
Location: fs/fat/inode.c:652
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff81345490-ffffffff81345566: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81359ee0)
Location: fs/fat/inode.c:652
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff81359ee0-ffffffff81359fd1: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8137ebf0)
Location: fs/fat/inode.c:652
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff8137ebf0-ffffffff8137ece1: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:663
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff813ad220-ffffffff813ad2de: fat_set_state (STB_LOCAL)
ffffffff813afd03-ffffffff813afd36: fat_set_state.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:659
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff813c65d0-ffffffff813c668e: fat_set_state (STB_LOCAL)
ffffffff813c9173-ffffffff813c91a6: fat_set_state.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:660
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff813f10e0-ffffffff813f119f: fat_set_state (STB_LOCAL)
ffffffff813f3ce7-ffffffff813f3d1d: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff8140afc0-ffffffff8140b07f: fat_set_state (STB_LOCAL)
ffffffff8140dbc7-ffffffff8140dbfd: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff81458b70-ffffffff81458c30: fat_set_state (STB_LOCAL)
ffffffff8145b987-ffffffff8145b9bd: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff81474ec0-ffffffff81474f80: fat_set_state (STB_LOCAL)
ffffffff81bed8ce-ffffffff81bed904: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff8147a930-ffffffff8147a9f0: fat_set_state (STB_LOCAL)
ffffffff81bdf9d2-ffffffff81bdfa08: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:666
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff814d1f50-ffffffff814d2010: fat_set_state (STB_LOCAL)
ffffffff81ccfebb-ffffffff81ccfef1: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:668
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff8155eed0-ffffffff8155efab: fat_set_state (STB_LOCAL)
ffffffff81e83117-ffffffff81e8314d: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81601110)
Location: fs/fat/inode.c:663
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff81601110-ffffffff81601233: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81639000)
Location: fs/fat/inode.c:663
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff81639000-ffffffff81639123: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff816724f0)
Location: fs/fat/inode.c:668
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_remount
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff816724f0-ffffffff81672613: fat_set_state (STB_LOCAL)
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
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104eb9d0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffff8000104eb9d0-ffff8000104ebae0: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06a9c7c)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
c06a9c7c-c06a9d80: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c00000000062a3d0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
c00000000062a3d0-c00000000062a578: fat_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035c270)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffe00035c270-ffffffe00035c376: fat_set_state (STB_LOCAL)
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
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff814035a0-ffffffff8140365f: fat_set_state (STB_LOCAL)
ffffffff814061a7-ffffffff814061dd: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff813f4020-ffffffff813f40df: fat_set_state (STB_LOCAL)
ffffffff813f6c27-ffffffff813f6c5d: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff81400920-ffffffff814009df: fat_set_state (STB_LOCAL)
ffffffff81403527-ffffffff8140355d: fat_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fat_set_state(struct super_block *sb, unsigned int set, unsigned int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:665
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_put_super
```
**Symbols:**

```
ffffffff81416990-ffffffff81416a4f: fat_set_state (STB_LOCAL)
ffffffff814191ba-ffffffff814191f0: fat_set_state.cold (STB_LOCAL)
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
