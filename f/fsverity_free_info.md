# Function: <code>fsverity_free_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff81350954)
Location: fs/verity/open.c:230
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81350910-ffffffff8135093a: fsverity_free_info.part.0 (STB_LOCAL)
ffffffff81350eb0-ffffffff81350ec6: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81397333)
Location: fs/verity/open.c:231
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81397900-ffffffff81397932: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813a8da3)
Location: fs/verity/open.c:240
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff813a9370-ffffffff813a93a2: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813afe13)
Location: fs/verity/open.c:213
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff813b0250-ffffffff813b0282: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813ffa03)
Location: fs/verity/open.c:213
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff813ffe40-ffffffff813ffe72: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff814737c3)
Location: fs/verity/open.c:212
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81473c30-ffffffff81473c71: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff815056f3)
Location: fs/verity/open.c:212
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81505cf0-ffffffff81505d31: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff8153c8e3)
Location: fs/verity/open.c:271
Inline: True
Inline callers:
  - fs/verity/open.c:__fsverity_cleanup_inode
  - fs/verity/open.c:__fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8153d010-ffffffff8153d05d: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81571d43)
Location: fs/verity/open.c:271
Inline: True
Inline callers:
  - fs/verity/open.c:__fsverity_cleanup_inode
  - fs/verity/open.c:__fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81572470-ffffffff815724bd: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffff8000104128f4)
Location: fs/verity/open.c:230
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffff800010412898-ffff8000104128d4: fsverity_free_info.part.0 (STB_LOCAL)
ffff800010413090-ffff8000104130c0: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (c05dec6c)
Location: fs/verity/open.c:230
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
c05dec18-c05dec50: fsverity_free_info.part.0 (STB_LOCAL)
c05df400-c05df424: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (c000000000520460)
Location: fs/verity/open.c:230
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
c0000000005203e0-c000000000520438: fsverity_free_info.part.0 (STB_LOCAL)
c000000000520e50-c000000000520e6c: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffe0002ba56e)
Location: fs/verity/open.c:230
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffe0002ba518-ffffffe0002ba554: fsverity_free_info.part.0 (STB_LOCAL)
ffffffe0002bac34-ffffffe0002bac60: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff81348f34)
Location: fs/verity/open.c:230
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81348ef0-ffffffff81348f1a: fsverity_free_info.part.0 (STB_LOCAL)
ffffffff81349490-ffffffff813494a6: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff81339c14)
Location: fs/verity/open.c:230
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81339bd0-ffffffff81339bfa: fsverity_free_info.part.0 (STB_LOCAL)
ffffffff8133a170-ffffffff8133a186: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff81346a04)
Location: fs/verity/open.c:230
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff813469c0-ffffffff813469ea: fsverity_free_info.part.0 (STB_LOCAL)
ffffffff81346f60-ffffffff81346f76: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsverity_free_info(struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff81359ce4)
Location: fs/verity/open.c:230
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81359ca0-ffffffff81359cca: fsverity_free_info.part.0 (STB_LOCAL)
ffffffff8135a240-ffffffff8135a256: fsverity_free_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
