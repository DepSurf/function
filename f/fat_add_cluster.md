# Function: <code>fat_add_cluster</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fb6fb)
Location: fs/fat/inode.c:96
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813317f0)
Location: fs/fat/inode.c:96
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813317f0-ffffffff81331868: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81347590)
Location: fs/fat/inode.c:96
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81347590-ffffffff81347608: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8135bfc0)
Location: fs/fat/inode.c:96
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff8135bfc0-ffffffff8135c038: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81380cc0)
Location: fs/fat/inode.c:96
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81380cc0-ffffffff81380d38: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813af450)
Location: fs/fat/inode.c:97
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813af450-ffffffff813af4c8: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813c88f0)
Location: fs/fat/inode.c:97
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813c88f0-ffffffff813c8968: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813f3490)
Location: fs/fat/inode.c:98
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813f3490-ffffffff813f350d: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8140d370)
Location: fs/fat/inode.c:103
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff8140d370-ffffffff8140d3ed: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8145b0a0)
Location: fs/fat/inode.c:104
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff8145b0a0-ffffffff8145b11d: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff814773f0)
Location: fs/fat/inode.c:104
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff814773f0-ffffffff8147746d: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8147ce60)
Location: fs/fat/inode.c:104
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff8147ce60-ffffffff8147cedd: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff814d4580)
Location: fs/fat/inode.c:104
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff814d4580-ffffffff814d45fd: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff815614c0)
Location: fs/fat/inode.c:104
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff815614c0-ffffffff81561549: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81603b60)
Location: fs/fat/inode.c:104
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff81603b60-ffffffff81603be9: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8163ba80)
Location: fs/fat/inode.c:104
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff8163ba80-ffffffff8163bb09: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81674fe0)
Location: fs/fat/inode.c:104
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff81674fe0-ffffffff81675069: fat_add_cluster (STB_GLOBAL)
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
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104ee050)
Location: fs/fat/inode.c:103
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffff8000104ee050-ffff8000104ee0e8: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06abbc4)
Location: fs/fat/inode.c:103
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
c06abbc4-c06abc58: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c00000000062ceb0)
Location: fs/fat/inode.c:103
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
c00000000062ceb0-c00000000062cf68: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035e4c6)
Location: fs/fat/inode.c:103
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffe00035e4c6-ffffffe00035e530: fat_add_cluster (STB_GLOBAL)
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
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81405950)
Location: fs/fat/inode.c:103
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81405950-ffffffff814059cd: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813f63d0)
Location: fs/fat/inode.c:103
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813f63d0-ffffffff813f644d: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81402cd0)
Location: fs/fat/inode.c:103
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81402cd0-ffffffff81402d4d: fat_add_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fat_add_cluster(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81418930)
Location: fs/fat/inode.c:103
Inline: False
Direct callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81418930-ffffffff814189ad: fat_add_cluster (STB_GLOBAL)
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
