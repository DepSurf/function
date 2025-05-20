# Function: <code>ext4_put_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b8da0)
Location: fs/ext4/super.c:797
Inline: False
```
**Symbols:**

```
ffffffff812b8da0-ffffffff812b90be: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e7c20)
Location: fs/ext4/super.c:826
Inline: False
```
**Symbols:**

```
ffffffff812e7c20-ffffffff812e7f64: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fd960)
Location: fs/ext4/super.c:829
Inline: False
```
**Symbols:**

```
ffffffff812fd960-ffffffff812fdd02: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813326d0)
Location: fs/ext4/super.c:869
Inline: False
```
**Symbols:**

```
ffffffff813326d0-ffffffff81332a97: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81356be0)
Location: fs/ext4/super.c:869
Inline: False
```
**Symbols:**

```
ffffffff81356be0-ffffffff81356fb3: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:909
Inline: False
```
**Symbols:**

```
ffffffff81384ed0-ffffffff8138524f: ext4_put_super (STB_LOCAL)
ffffffff8138babb-ffffffff8138bb03: ext4_put_super.cold.139 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:963
Inline: False
```
**Symbols:**

```
ffffffff8139d9c0-ffffffff8139dd35: ext4_put_super (STB_LOCAL)
ffffffff813a461b-ffffffff813a4663: ext4_put_super.cold.143 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:974
Inline: False
```
**Symbols:**

```
ffffffff813c7c10-ffffffff813c7fc3: ext4_put_super (STB_LOCAL)
ffffffff813ce803-ffffffff813ce848: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:969
Inline: False
```
**Symbols:**

```
ffffffff813e0fd0-ffffffff813e13ad: ext4_put_super (STB_LOCAL)
ffffffff813e7ec2-ffffffff813e7f07: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:997
Inline: False
```
**Symbols:**

```
ffffffff8142dbe0-ffffffff8142dfd7: ext4_put_super (STB_LOCAL)
ffffffff81434a3d-ffffffff81434a82: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:1153
Inline: False
```
**Symbols:**

```
ffffffff814468a0-ffffffff81446cbb: ext4_put_super (STB_LOCAL)
ffffffff81bec809-ffffffff81bec87c: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:1162
Inline: False
```
**Symbols:**

```
ffffffff8144c050-ffffffff8144c461: ext4_put_super (STB_LOCAL)
ffffffff81bde8bb-ffffffff81bde92e: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:1161
Inline: False
```
**Symbols:**

```
ffffffff814a00f0-ffffffff814a051b: ext4_put_super (STB_LOCAL)
ffffffff81ccda1a-ffffffff81ccda8d: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:1193
Inline: False
```
**Symbols:**

```
ffffffff81526d30-ffffffff81527156: ext4_put_super (STB_LOCAL)
ffffffff81e808f8-ffffffff81e8096b: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c4620)
Location: fs/ext4/super.c:1186
Inline: False
```
**Symbols:**

```
ffffffff815c4620-ffffffff815c4abe: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fbd10)
Location: fs/ext4/super.c:1270
Inline: False
```
**Symbols:**

```
ffffffff815fbd10-ffffffff815fc1b0: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff816348b0)
Location: fs/ext4/super.c:1291
Inline: False
```
**Symbols:**

```
ffffffff816348b0-ffffffff81634cf4: ext4_put_super (STB_LOCAL)
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
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ba370)
Location: fs/ext4/super.c:969
Inline: False
```
**Symbols:**

```
ffff8000104ba370-ffff8000104ba6e8: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067da2c)
Location: fs/ext4/super.c:969
Inline: False
```
**Symbols:**

```
c067da2c-c067ddc8: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005efae0)
Location: fs/ext4/super.c:969
Inline: False
```
**Symbols:**

```
c0000000005efae0-c0000000005effec: ext4_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe00033685c)
Location: fs/ext4/super.c:969
Inline: False
```
**Symbols:**

```
ffffffe00033685c-ffffffe000336c48: ext4_put_super (STB_LOCAL)
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
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:969
Inline: False
```
**Symbols:**

```
ffffffff813d95b0-ffffffff813d998d: ext4_put_super (STB_LOCAL)
ffffffff813e04a2-ffffffff813e04e7: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:969
Inline: False
```
**Symbols:**

```
ffffffff813ca030-ffffffff813ca40d: ext4_put_super (STB_LOCAL)
ffffffff813d0f22-ffffffff813d0f67: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:969
Inline: False
```
**Symbols:**

```
ffffffff813d6a40-ffffffff813d6e10: ext4_put_super (STB_LOCAL)
ffffffff813dd822-ffffffff813dd867: ext4_put_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ext4_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:969
Inline: False
```
**Symbols:**

```
ffffffff813ebce0-ffffffff813ec0c7: ext4_put_super (STB_LOCAL)
ffffffff813f2c4e-ffffffff813f2c93: ext4_put_super.cold (STB_LOCAL)
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
