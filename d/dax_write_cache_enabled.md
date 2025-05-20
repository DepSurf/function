# Function: <code>dax_write_cache_enabled</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163ca00)
Location: drivers/dax/super.c:281
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff8163ca00-ffffffff8163ca18: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5690)
Location: drivers/dax/super.c:307
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff816a5690-ffffffff816a56a8: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e19f5)
Location: drivers/dax/super.c:333
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff816e18e0-ffffffff816e18f8: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81704e15)
Location: drivers/dax/super.c:332
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff81704d00-ffffffff81704d18: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173ec75)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff8173eb10-ffffffff8173eb28: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81762e55)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff81762cf0-ffffffff81762d08: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822c15)
Location: drivers/dax/super.c:393
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff81822af0-ffffffff81822b08: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831925)
Location: drivers/dax/super.c:401
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff81831800-ffffffff81831818: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814b55)
Location: drivers/dax/super.c:401
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff81814a30-ffffffff81814a48: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f315)
Location: drivers/dax/super.c:393
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff8189f1f0-ffffffff8189f208: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8fb5)
Location: drivers/dax/super.c:232
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff819e8d90-ffffffff819e8dae: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b655d5)
Location: drivers/dax/super.c:277
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff81b653e0-ffffffff81b653fe: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb8bf5)
Location: drivers/dax/super.c:280
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff81bb89e0-ffffffff81bb89fe: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d255)
Location: drivers/dax/super.c:280
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff81c0d040-ffffffff81c0d05e: dax_write_cache_enabled (STB_GLOBAL)
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
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010962bdc)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffff8000109629f8-ffff800010962a24: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a3a590)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
c0a398ec-c0a3990c: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a18c60)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
c000000000a18ab0-c000000000a18ac4: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d092a)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffe0005d0022-ffffffe0005d004a: dax_write_cache_enabled (STB_GLOBAL)
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
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717545)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff817173e0-ffffffff817173f8: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efa75)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff816ef910-ffffffff816ef928: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756315)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff817561b0-ffffffff817561c8: dax_write_cache_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool dax_write_cache_enabled(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771785)
Location: drivers/dax/super.c:372
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_flush
  - drivers/dax/super.c:write_cache_show
Direct callers:
  - drivers/md/dm-table.c:device_dax_write_cache_enabled
```
**Symbols:**

```
ffffffff81771620-ffffffff81771638: dax_write_cache_enabled (STB_GLOBAL)
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
