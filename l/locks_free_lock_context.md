# Function: <code>locks_free_lock_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void locks_free_lock_context(struct file_lock_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81262530)
Location: fs/locks.c:237
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81262530-ffffffff812625dc: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128e710)
Location: fs/locks.c:264
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8128e710-ffffffff8128e7c9: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a3630)
Location: fs/locks.c:274
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812a3630-ffffffff812a36e9: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b22f0)
Location: fs/locks.c:274
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812b22f0-ffffffff812b23a5: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d5e50)
Location: fs/locks.c:291
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812d5e50-ffffffff812d5f05: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:291
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff813016c8-ffffffff8130171e: locks_free_lock_context.cold.46 (STB_LOCAL)
ffffffff81300c40-ffffffff81300ca9: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:322
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff813171b3-ffffffff81317209: locks_free_lock_context.cold.45 (STB_LOCAL)
ffffffff813166a0-ffffffff81316709: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:323
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8133ea6d-ffffffff8133eac3: locks_free_lock_context.cold (STB_LOCAL)
ffffffff8133df10-ffffffff8133df89: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8135705d-ffffffff813570b3: locks_free_lock_context.cold (STB_LOCAL)
ffffffff81356500-ffffffff81356579: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8139e30b-ffffffff8139e361: locks_free_lock_context.cold (STB_LOCAL)
ffffffff8139d660-ffffffff8139d6d9: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81beb9f7-ffffffff81beba4d: locks_free_lock_context.cold (STB_LOCAL)
ffffffff813af020-ffffffff813af099: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81bdda59-ffffffff81bddaaf: locks_free_lock_context.cold (STB_LOCAL)
ffffffff813b6380-ffffffff813b63f9: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81cc7495-ffffffff81cc74eb: locks_free_lock_context.cold (STB_LOCAL)
ffffffff81406080-ffffffff814060f9: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:248
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81e79a25-ffffffff81e79a7b: locks_free_lock_context.cold (STB_LOCAL)
ffffffff8147aa30-ffffffff8147aabc: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150d440)
Location: fs/locks.c:248
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8150d440-ffffffff8150d5d4: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81544bf0)
Location: fs/locks.c:249
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81544bf0-ffffffff81544da1: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157a0e0)
Location: fs/locks.c:248
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8157a0e0-ffffffff8157a291: locks_free_lock_context (STB_GLOBAL)
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
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010418ef8)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffff800010418ef8-ffff800010418fd4: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e4f38)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
c05e4f38-c05e4ff8: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000528880)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
c000000000528880-c000000000528980: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bf70c)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffe0002bf70c-ffffffe0002bf7d4: locks_free_lock_context (STB_GLOBAL)
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
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8134f63d-ffffffff8134f693: locks_free_lock_context.cold (STB_LOCAL)
ffffffff8134eae0-ffffffff8134eb59: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8134031d-ffffffff81340373: locks_free_lock_context.cold (STB_LOCAL)
ffffffff8133f7c0-ffffffff8133f839: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8134d10d-ffffffff8134d163: locks_free_lock_context.cold (STB_LOCAL)
ffffffff8134c5b0-ffffffff8134c629: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void locks_free_lock_context(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:324
Inline: False
Direct callers:
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81360698-ffffffff813606ee: locks_free_lock_context.cold (STB_LOCAL)
ffffffff8135faa0-ffffffff8135fb19: locks_free_lock_context (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file_lock_context *ctx</code>
</li>
</ul>
</details>
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
