# Function: <code>squashfs_read_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff81323080)
Location: fs/squashfs/inode.c:113
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81323080-ffffffff8132391f: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff81338f10)
Location: fs/squashfs/inode.c:113
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81338f10-ffffffff813397af: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff8134dbe0)
Location: fs/squashfs/inode.c:113
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8134dbe0-ffffffff8134e482: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff81372290)
Location: fs/squashfs/inode.c:113
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81372290-ffffffff81372b37: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:113
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813a14ad-ffffffff813a14ee: squashfs_read_inode.cold.0 (STB_LOCAL)
ffffffff813a0b90-ffffffff813a141b: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:113
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813ba29d-ffffffff813ba2c4: squashfs_read_inode.cold.0 (STB_LOCAL)
ffffffff813b9910-ffffffff813ba20c: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813e4b54-ffffffff813e4b98: squashfs_read_inode.cold (STB_LOCAL)
ffffffff813e41c0-ffffffff813e4ab6: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813feba4-ffffffff813febe8: squashfs_read_inode.cold (STB_LOCAL)
ffffffff813fe210-ffffffff813feb06: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8144c4e4-ffffffff8144c528: squashfs_read_inode.cold (STB_LOCAL)
ffffffff8144bbb0-ffffffff8144c448: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81bed4bf-ffffffff81bed503: squashfs_read_inode.cold (STB_LOCAL)
ffffffff814682a0-ffffffff81468b37: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81bdf5a3-ffffffff81bdf5e5: squashfs_read_inode.cold (STB_LOCAL)
ffffffff8146d940-ffffffff8146e239: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81ccf082-ffffffff81ccf0c4: squashfs_read_inode.cold (STB_LOCAL)
ffffffff814c41d0-ffffffff814c4ac1: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81e820e3-ffffffff81e8213f: squashfs_read_inode.cold (STB_LOCAL)
ffffffff8154ef80-ffffffff8154f8a5: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff815ef9e0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff815ef9e0-ffffffff815f0335: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff816279b0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff816279b0-ffffffff81628373: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff81660b10)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81660b10-ffffffff816614f1: squashfs_read_inode (STB_GLOBAL)
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
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffff8000104dc350)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffff8000104dc350-ffff8000104dcbd8: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (c069dbf8)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
c069dbf8-c069e620: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (c000000000617740)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
c000000000617740-c0000000006181c0: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffe000350eae)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffe000350eae-ffffffe0003516d8: squashfs_read_inode (STB_GLOBAL)
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
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813f7184-ffffffff813f71c8: squashfs_read_inode.cold (STB_LOCAL)
ffffffff813f67f0-ffffffff813f70e6: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813e7c04-ffffffff813e7c48: squashfs_read_inode.cold (STB_LOCAL)
ffffffff813e7270-ffffffff813e7b66: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813f4504-ffffffff813f4548: squashfs_read_inode.cold (STB_LOCAL)
ffffffff813f3b70-ffffffff813f4466: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int squashfs_read_inode(struct inode *inode, long long int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/inode.c (0)
Location: fs/squashfs/inode.c:100
Inline: False
Direct callers:
  - fs/squashfs/inode.c:squashfs_iget
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8140a134-ffffffff8140a178: squashfs_read_inode.cold (STB_LOCAL)
ffffffff814097a0-ffffffff8140a096: squashfs_read_inode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
