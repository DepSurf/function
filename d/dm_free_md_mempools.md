# Function: <code>dm_free_md_mempools</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a49f0)
Location: drivers/md/dm.c:3542
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_free_md_mempools
```
**Symbols:**

```
ffffffff816a49f0-ffffffff816a4a2d: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81704ba0)
Location: drivers/md/dm.c:2543
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81704ba0-ffffffff81704bdd: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81736a50)
Location: drivers/md/dm.c:2603
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81736a50-ffffffff81736a8d: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff8174ff2a)
Location: drivers/md/dm.c:2804
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff8174e2e0-ffffffff8174e30e: dm_free_md_mempools.part.33 (STB_LOCAL)
ffffffff8174ffa0-ffffffff8174ffb7: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff817c2107)
Location: drivers/md/dm.c:2783
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff817c0310-ffffffff817c033e: dm_free_md_mempools.part.32 (STB_LOCAL)
ffffffff817c2180-ffffffff817c2197: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8180a8c0)
Location: drivers/md/dm.c:2977
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff8180a950-ffffffff8180a97f: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818368ea)
Location: drivers/md/dm.c:2999
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81836950-ffffffff8183697f: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8187949d)
Location: drivers/md/dm.c:3030
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81879500-ffffffff81879532: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818ab2dd)
Location: drivers/md/dm.c:3035
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff818ab340-ffffffff818ab372: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197b4aa)
Location: drivers/md/dm.c:3098
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff8197b510-ffffffff8197b544: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197fc40)
Location: drivers/md/dm.c:2944
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff8197fd20-ffffffff8197fd54: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81963dc8)
Location: drivers/md/dm.c:2963
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81963ea0-ffffffff81963ed4: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0bd78)
Location: drivers/md/dm.c:2852
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81a0be50-ffffffff81a0be84: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b742fb)
Location: drivers/md/dm.c:3033
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81b74370-ffffffff81b743ae: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0d109)
Location: drivers/md/dm.c:3090
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81d111e0-ffffffff81d1121e: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d75ec9)
Location: drivers/md/dm.c:3133
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81d7a670-ffffffff81d7a6ae: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2d0f9)
Location: drivers/md/dm.c:3141
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff81e31810-ffffffff81e3184e: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b015dc)
Location: drivers/md/dm.c:3035
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffff800010b01660-ffff800010b016a0: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0be0d1c)
Location: drivers/md/dm.c:3035
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
c0be0d7c-c0be0db0: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bf0980)
Location: drivers/md/dm.c:3035
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
c000000000bf0a30-c000000000bf0a8c: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f1576)
Location: drivers/md/dm.c:3035
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffe0006f15ce-ffffffe0006f1610: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8185115d)
Location: drivers/md/dm.c:3035
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff818511c0-ffffffff818511f2: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8181876d)
Location: drivers/md/dm.c:3035
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff818187d0-ffffffff81818802: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a078d)
Location: drivers/md/dm.c:3035
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff818a07f0-ffffffff818a0822: dm_free_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dm_free_md_mempools(struct dm_md_mempools *pools);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bc9cd)
Location: drivers/md/dm.c:3035
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
Direct callers:
  - drivers/md/dm-table.c:dm_table_free_md_mempools
  - drivers/md/dm-table.c:dm_table_destroy
```
**Symbols:**

```
ffffffff818bca30-ffffffff818bca62: dm_free_md_mempools (STB_GLOBAL)
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
