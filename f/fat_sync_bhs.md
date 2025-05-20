# Function: <code>fat_sync_bhs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff812fe620)
Location: fs/fat/misc.c:265
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_write
  - fs/fat/fatent.c:fat_alloc_clusters
```
**Symbols:**

```
ffffffff812fe620-ffffffff812fe6a9: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81332620)
Location: fs/fat/misc.c:265
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff81332620-ffffffff813326a6: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813483c0)
Location: fs/fat/misc.c:265
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff813483c0-ffffffff81348446: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8135cdd0)
Location: fs/fat/misc.c:265
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff8135cdd0-ffffffff8135ce62: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81381ad0)
Location: fs/fat/misc.c:265
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff81381ad0-ffffffff81381b62: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813b0650)
Location: fs/fat/misc.c:265
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff813b0650-ffffffff813b06d8: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813c9cb0)
Location: fs/fat/misc.c:343
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff813c9cb0-ffffffff813c9d38: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f4830)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff813f4830-ffffffff813f48b8: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8140e700)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff8140e700-ffffffff8140e788: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8145c4f0)
Location: fs/fat/misc.c:352
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff8145c4f0-ffffffff8145c578: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff814783f0)
Location: fs/fat/misc.c:352
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff814783f0-ffffffff81478478: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8147de60)
Location: fs/fat/misc.c:353
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff8147de60-ffffffff8147dee8: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff814d5600)
Location: fs/fat/misc.c:356
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff814d5600-ffffffff814d5688: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff815626e0)
Location: fs/fat/misc.c:364
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff815626e0-ffffffff8156276f: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff816050c0)
Location: fs/fat/misc.c:364
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff816050c0-ffffffff8160514d: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8163cfd0)
Location: fs/fat/misc.c:364
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff8163cfd0-ffffffff8163d05d: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81676540)
Location: fs/fat/misc.c:362
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff81676540-ffffffff816765cd: fat_sync_bhs (STB_GLOBAL)
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
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffff8000104ef320)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffff8000104ef320-ffff8000104ef3ec: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c06ace54)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
c06ace54-c06acee4: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c00000000062e5a0)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
c00000000062e5a0-c00000000062e6a4: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffe00035f340)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffe00035f340-ffffffe00035f3d2: fat_sync_bhs (STB_GLOBAL)
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
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81406ce0)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff81406ce0-ffffffff81406d68: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f7760)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff813f7760-ffffffff813f77e8: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81404060)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff81404060-ffffffff814040e8: fat_sync_bhs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fat_sync_bhs(struct buffer_head **bhs, int nr_bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81419cd0)
Location: fs/fat/misc.c:344
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_write
```
**Symbols:**

```
ffffffff81419cd0-ffffffff81419d4b: fat_sync_bhs (STB_GLOBAL)
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
