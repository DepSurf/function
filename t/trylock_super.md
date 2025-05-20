# Function: <code>trylock_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120fe10)
Location: fs/super.c:387
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff8120fe10-ffffffff8120fe5e: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812368d0)
Location: fs/super.c:391
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff812368d0-ffffffff8123691e: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81249580)
Location: fs/super.c:390
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff81249580-ffffffff812495ce: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81254ea0)
Location: fs/super.c:389
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff81254ea0-ffffffff81254eee: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81277030)
Location: fs/super.c:393
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff81277030-ffffffff8127707e: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129da10)
Location: fs/super.c:407
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff8129da10-ffffffff8129da5e: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b29d0)
Location: fs/super.c:411
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff812b29d0-ffffffff812b2a1e: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cf630)
Location: fs/super.c:412
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff812cf630-ffffffff812cf680: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e10e0)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff812e10e0-ffffffff812e1130: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81316d1b)
Location: fs/super.c:416
Inline: True
Inline callers:
  - fs/super.c:super_cache_scan
Direct callers:
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff813185f0-ffffffff81318640: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8132222b)
Location: fs/super.c:416
Inline: True
Inline callers:
  - fs/super.c:super_cache_scan
Direct callers:
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff81323a10-ffffffff81323a60: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813282eb)
Location: fs/super.c:416
Inline: True
Inline callers:
  - fs/super.c:super_cache_scan
Direct callers:
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff81329ad0-ffffffff81329b20: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813758bb)
Location: fs/super.c:416
Inline: True
Inline callers:
  - fs/super.c:super_cache_scan
Direct callers:
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff81377100-ffffffff81377150: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f5328)
Location: fs/super.c:413
Inline: True
Inline callers:
  - fs/super.c:super_cache_scan
Direct callers:
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff813f6370-ffffffff813f63c2: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147e588)
Location: fs/super.c:413
Inline: True
Inline callers:
  - fs/super.c:super_cache_scan
Direct callers:
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff8147f430-ffffffff8147f482: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b2e58)
Location: fs/super.c:411
Inline: True
Inline callers:
  - fs/super.c:super_cache_scan
Direct callers:
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff814b4080-ffffffff814b40d2: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388288)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffff800010388288-ffff8000103882f4: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0570a84)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
c0570a84-c0570aec: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047eec0)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
c00000000047eec0-c00000000047ef6c: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025a95e)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffe00025a95e-ffffffe00025a9c2: trylock_super (STB_GLOBAL)
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
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d96c0)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff812d96c0-ffffffff812d9710: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ca340)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff812ca340-ffffffff812ca390: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d74d0)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff812d74d0-ffffffff812d7520: trylock_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool trylock_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8320)
Location: fs/super.c:416
Inline: False
Direct callers:
  - fs/super.c:super_cache_scan
  - fs/fs-writeback.c:__writeback_inodes_wb
```
**Symbols:**

```
ffffffff812e8320-ffffffff812e8370: trylock_super (STB_GLOBAL)
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
