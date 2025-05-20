# Function: <code>shmem_reserve_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a6400)
Location: mm/shmem.c:203
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_link
```
**Symbols:**

```
ffffffff811a6400-ffffffff811a6466: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bcd00)
Location: mm/shmem.c:200
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff811bcd00-ffffffff811bcd66: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cd3d0)
Location: mm/shmem.c:196
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff811cd3d0-ffffffff811cd43c: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d6070)
Location: mm/shmem.c:212
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff811d6070-ffffffff811d60ca: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811eb590)
Location: mm/shmem.c:245
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff811eb590-ffffffff811eb5ea: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120fb50)
Location: mm/shmem.c:245
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff8120fb50-ffffffff8120fbaa: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81224f20)
Location: mm/shmem.c:247
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff81224f20-ffffffff81224f7a: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812320f0)
Location: mm/shmem.c:252
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff812320f0-ffffffff8123214a: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81240320)
Location: mm/shmem.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff81240320-ffffffff8124037a: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81271211)
Location: mm/shmem.c:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int shmem_reserve_inode(struct super_block *sb, ino_t *inop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:275
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff812781b0-ffffffff812782d2: shmem_reserve_inode (STB_LOCAL)
ffffffff81be6ec9-ffffffff81be6ef7: shmem_reserve_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int shmem_reserve_inode(struct super_block *sb, ino_t *inop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:275
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff8127d130-ffffffff8127d251: shmem_reserve_inode (STB_LOCAL)
ffffffff81bd8c35-ffffffff81bd8c63: shmem_reserve_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shmem_reserve_inode(struct super_block *sb, ino_t *inop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:271
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff812bb270-ffffffff812bb3d4: shmem_reserve_inode (STB_LOCAL)
ffffffff81cba9ba-ffffffff81cbaa04: shmem_reserve_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shmem_reserve_inode(struct super_block *sb, ino_t *inop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff813166a7)
Location: mm/shmem.c:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_link
Direct callers:
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff81315b00-ffffffff81315c77: shmem_reserve_inode (STB_LOCAL)
ffffffff81e6c251-ffffffff81e6c29b: shmem_reserve_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shmem_reserve_inode(struct super_block *sb, ino_t *inop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff8138a8fa)
Location: mm/shmem.c:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_link
Direct callers:
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff81389b30-ffffffff81389cd6: shmem_reserve_inode (STB_LOCAL)
ffffffff82062cdd-ffffffff82062cf8: shmem_reserve_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shmem_reserve_inode(struct super_block *sb, ino_t *inop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff813bd22a)
Location: mm/shmem.c:267
Inline: True
Inline callers:
  - mm/shmem.c:shmem_link
Direct callers:
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff813bbcf0-ffffffff813bbe96: shmem_reserve_inode (STB_LOCAL)
ffffffff820e2504-ffffffff820e251f: shmem_reserve_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shmem_reserve_inode(struct super_block *sb, ino_t *inop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff813e90b8)
Location: mm/shmem.c:330
Inline: True
Inline callers:
  - mm/shmem.c:shmem_link
Direct callers:
  - mm/shmem.c:__shmem_get_inode
```
**Symbols:**

```
ffffffff813e67a0-ffffffff813e694b: shmem_reserve_inode (STB_LOCAL)
ffffffff821beed2-ffffffff821beeed: shmem_reserve_inode.cold (STB_LOCAL)
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
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d13a8)
Location: mm/shmem.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffff8000102d13a8-ffff8000102d1460: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04f86d8)
Location: mm/shmem.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
c04f86d8-c04f8758: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038ead0)
Location: mm/shmem.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
c00000000038ead0-c00000000038ebd4: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001eebc4)
Location: mm/shmem.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffe0001eebc4-ffffffe0001eec90: shmem_reserve_inode (STB_LOCAL)
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
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81238970)
Location: mm/shmem.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff81238970-ffffffff812389ca: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122b9b0)
Location: mm/shmem.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff8122b9b0-ffffffff8122ba0a: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81236710)
Location: mm/shmem.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff81236710-ffffffff8123676a: shmem_reserve_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_reserve_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81242eb0)
Location: mm/shmem.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_get_inode
```
**Symbols:**

```
ffffffff81242eb0-ffffffff81242f06: shmem_reserve_inode (STB_LOCAL)
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
