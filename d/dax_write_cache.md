# Function: <code>dax_write_cache</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163d2e0)
Location: drivers/dax/super.c:272
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8163d2e0-ffffffff8163d302: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a6060)
Location: drivers/dax/super.c:298
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff816a6060-ffffffff816a6082: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1bb0)
Location: drivers/dax/super.c:324
Inline: True
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff816e1bb0-ffffffff816e1bd2: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81704fd0)
Location: drivers/dax/super.c:323
Inline: True
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81704fd0-ffffffff81704ff2: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173ede0)
Location: drivers/dax/super.c:363
Inline: True
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8173ede0-ffffffff8173ee02: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81762fc0)
Location: drivers/dax/super.c:363
Inline: True
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81762fc0-ffffffff81762fe2: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822e90)
Location: drivers/dax/super.c:384
Inline: False
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81822e90-ffffffff81822eb2: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831bd0)
Location: drivers/dax/super.c:392
Inline: False
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81831bd0-ffffffff81831bf2: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814e00)
Location: drivers/dax/super.c:392
Inline: False
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81814e00-ffffffff81814e22: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f570)
Location: drivers/dax/super.c:384
Inline: False
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8189f570-ffffffff8189f592: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e9240)
Location: drivers/dax/super.c:223
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff819e9240-ffffffff819e9272: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65a20)
Location: drivers/dax/super.c:268
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81b65a20-ffffffff81b65a52: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb8fd0)
Location: drivers/dax/super.c:271
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81bb8fd0-ffffffff81bb9002: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d630)
Location: drivers/dax/super.c:271
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81c0d630-ffffffff81c0d662: dax_write_cache (STB_GLOBAL)
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
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963750)
Location: drivers/dax/super.c:363
Inline: False
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffff800010963750-ffff8000109637dc: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39a78)
Location: drivers/dax/super.c:363
Inline: False
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
c0a39a78-c0a39aac: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a198b8)
Location: drivers/dax/super.c:363
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/dax/super.c:write_cache_store
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
c000000000a193f0-c000000000a19434: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d08b2)
Location: drivers/dax/super.c:363
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffe0005cffd8-ffffffe0005d0022: dax_write_cache (STB_GLOBAL)
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
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817176b0)
Location: drivers/dax/super.c:363
Inline: True
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff817176b0-ffffffff817176d2: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efbe0)
Location: drivers/dax/super.c:363
Inline: True
Direct callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff816efbe0-ffffffff816efc02: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756480)
Location: drivers/dax/super.c:363
Inline: True
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81756480-ffffffff817564a2: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dax_write_cache(struct dax_device *dax_dev, bool wc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771b00)
Location: drivers/dax/super.c:363
Inline: True
Direct callers:
  - drivers/dax/super.c:write_cache_store
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81771b00-ffffffff81771b22: dax_write_cache (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
