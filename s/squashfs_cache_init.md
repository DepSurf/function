# Function: <code>squashfs_cache_init</code>

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
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81321740)
Location: fs/squashfs/cache.c:236
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81321740-ffffffff8132198b: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813375d0)
Location: fs/squashfs/cache.c:236
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813375d0-ffffffff8133781b: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8134c300)
Location: fs/squashfs/cache.c:236
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8134c300-ffffffff8134c554: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81370980)
Location: fs/squashfs/cache.c:236
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81370980-ffffffff81370bd4: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:236
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8139f6f3-ffffffff8139f728: squashfs_cache_init.cold.5 (STB_LOCAL)
ffffffff8139f1e0-ffffffff8139f3ec: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:236
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813b8483-ffffffff813b84b8: squashfs_cache_init.cold.4 (STB_LOCAL)
ffffffff813b7f70-ffffffff813b817c: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813e2c63-ffffffff813e2c98: squashfs_cache_init.cold (STB_LOCAL)
ffffffff813e2740-ffffffff813e294f: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813fcc93-ffffffff813fccc8: squashfs_cache_init.cold (STB_LOCAL)
ffffffff813fc770-ffffffff813fc97f: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8144a603-ffffffff8144a638: squashfs_cache_init.cold (STB_LOCAL)
ffffffff8144a0e0-ffffffff8144a2e7: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81bed3ec-ffffffff81bed421: squashfs_cache_init.cold (STB_LOCAL)
ffffffff814667d0-ffffffff814669d7: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81bdf4d0-ffffffff81bdf505: squashfs_cache_init.cold (STB_LOCAL)
ffffffff8146bda0-ffffffff8146bfa4: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81ccef1d-ffffffff81ccef52: squashfs_cache_init.cold (STB_LOCAL)
ffffffff814c2600-ffffffff814c2804: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81e81f70-ffffffff81e81fa2: squashfs_cache_init.cold (STB_LOCAL)
ffffffff8154d110-ffffffff8154d320: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff815ed050)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff815ed050-ffffffff815ed281: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81624f90)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81624f90-ffffffff816251b6: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8165e020)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8165e020-ffffffff8165e2cc: squashfs_cache_init (STB_GLOBAL)
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
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffff8000104da5d0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffff8000104da5d0-ffff8000104da82c: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c069bd18)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
c069bd18-c069bf24: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c0000000006151f0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
c0000000006151f0-c0000000006154f8: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffe00034f5b2)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffe00034f5b2-ffffffe00034f7ca: squashfs_cache_init (STB_GLOBAL)
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
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813f5273-ffffffff813f52a8: squashfs_cache_init.cold (STB_LOCAL)
ffffffff813f4d50-ffffffff813f4f5f: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813e5cf3-ffffffff813e5d28: squashfs_cache_init.cold (STB_LOCAL)
ffffffff813e57d0-ffffffff813e59df: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813f25f3-ffffffff813f2628: squashfs_cache_init.cold (STB_LOCAL)
ffffffff813f20d0-ffffffff813f22df: squashfs_cache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache *squashfs_cache_init(char *name, int entries, int block_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:223
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff814081e3-ffffffff81408218: squashfs_cache_init.cold (STB_LOCAL)
ffffffff81407cc0-ffffffff81407ecf: squashfs_cache_init (STB_GLOBAL)
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
