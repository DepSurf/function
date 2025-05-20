# Function: <code>regcache_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81567e70)
Location: drivers/base/regmap/regcache.c:313
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff81567e70-ffffffff815680a8: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815bca20)
Location: drivers/base/regmap/regcache.c:341
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff815bca20-ffffffff815bcc4c: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815ebe30)
Location: drivers/base/regmap/regcache.c:341
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff815ebe30-ffffffff815ec05c: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81600730)
Location: drivers/base/regmap/regcache.c:343
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff81600730-ffffffff81600952: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81668a80)
Location: drivers/base/regmap/regcache.c:343
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff81668a80-ffffffff81668cb7: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816a4400)
Location: drivers/base/regmap/regcache.c:343
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff816a4400-ffffffff816a463b: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4f40)
Location: drivers/base/regmap/regcache.c:343
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff816c4f40-ffffffff816c517b: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff8170064f-ffffffff81700676: regcache_sync.cold (STB_LOCAL)
ffffffff816ffed0-ffffffff817000de: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff817249a9-ffffffff817249d0: regcache_sync.cold (STB_LOCAL)
ffffffff81724250-ffffffff8172445e: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff817e0c32-ffffffff817e0c59: regcache_sync.cold (STB_LOCAL)
ffffffff817dfe40-ffffffff817e004e: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff81c0f508-ffffffff81c0f52e: regcache_sync.cold (STB_LOCAL)
ffffffff817f4d40-ffffffff817f4f49: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff81c01652-ffffffff81c01678: regcache_sync.cold (STB_LOCAL)
ffffffff817d9650-ffffffff817d9859: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff81d04e3d-ffffffff81d04e8c: regcache_sync.cold (STB_LOCAL)
ffffffff81864d50-ffffffff81864f70: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff81ecd87f-ffffffff81ecd8d0: regcache_sync.cold (STB_LOCAL)
ffffffff819ad1d0-ffffffff819ad41a: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:345
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff8209952d-ffffffff82099557: regcache_sync.cold (STB_LOCAL)
ffffffff81b20a80-ffffffff81b20ce1: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:348
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff8211a5ae-ffffffff8211a5d8: regcache_sync.cold (STB_LOCAL)
ffffffff81b6fcf0-ffffffff81b6ff5b: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:353
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff821f8434-ffffffff821f845d: regcache_sync.cold (STB_LOCAL)
ffffffff81bc3960-ffffffff81bc3c93: regcache_sync (STB_GLOBAL)
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
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffff800010918ee8)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffff800010918ee8-ffff800010919168: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c09feb14)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_resume
```
**Symbols:**

```
c09feb14-c09fed9c: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c0000000009bc880)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
c0000000009bc880-c0000000009bcbb0: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffe000599210)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffe000599210-ffffffe000599416: regcache_sync (STB_GLOBAL)
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
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
```
**Symbols:**

```
ffffffff816eacd9-ffffffff816ead00: regcache_sync.cold (STB_LOCAL)
ffffffff816ea580-ffffffff816ea78e: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
```
**Symbols:**

```
ffffffff816c5319-ffffffff816c5340: regcache_sync.cold (STB_LOCAL)
ffffffff816c4bc0-ffffffff816c4dce: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff81717e69-ffffffff81717e90: regcache_sync.cold (STB_LOCAL)
ffffffff81717710-ffffffff8171791e: regcache_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regcache_sync(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:339
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_power
```
**Symbols:**

```
ffffffff817331c9-ffffffff817331f0: regcache_sync.cold (STB_LOCAL)
ffffffff81732a10-ffffffff81732c50: regcache_sync (STB_GLOBAL)
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
