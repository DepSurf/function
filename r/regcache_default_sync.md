# Function: <code>regcache_default_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81567d50)
Location: drivers/base/regmap/regcache.c:268
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync_region
```
**Symbols:**

```
ffffffff81567d50-ffffffff81567e70: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815bc8f0)
Location: drivers/base/regmap/regcache.c:296
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff815bc8f0-ffffffff815bca12: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815ebd00)
Location: drivers/base/regmap/regcache.c:296
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff815ebd00-ffffffff815ebe22: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81600620)
Location: drivers/base/regmap/regcache.c:298
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff81600620-ffffffff8160072e: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81668970)
Location: drivers/base/regmap/regcache.c:298
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff81668970-ffffffff81668a7e: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816a42f0)
Location: drivers/base/regmap/regcache.c:298
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff816a42f0-ffffffff816a43fa: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4e30)
Location: drivers/base/regmap/regcache.c:298
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff816c4e30-ffffffff816c4f3a: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff816ffdd0-ffffffff816ffec8: regcache_default_sync (STB_LOCAL)
ffffffff8170062f-ffffffff8170064f: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff81724150-ffffffff81724248: regcache_default_sync (STB_LOCAL)
ffffffff81724989-ffffffff817249a9: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff817dfcf0-ffffffff817dfe3b: regcache_default_sync (STB_LOCAL)
ffffffff817e0c12-ffffffff817e0c32: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff817f4bf0-ffffffff817f4d3b: regcache_default_sync (STB_LOCAL)
ffffffff81c0f4e8-ffffffff81c0f508: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff817d9500-ffffffff817d964b: regcache_default_sync (STB_LOCAL)
ffffffff81c01632-ffffffff81c01652: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff81864bf0-ffffffff81864d47: regcache_default_sync (STB_LOCAL)
ffffffff81d04e08-ffffffff81d04e3d: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff819ad0c0-ffffffff819ad1c1: regcache_default_sync (STB_LOCAL)
ffffffff81ecd85f-ffffffff81ecd87f: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:300
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff81b208e0-ffffffff81b20a66: regcache_default_sync (STB_LOCAL)
ffffffff82099512-ffffffff8209952d: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81b6fbc0)
Location: drivers/base/regmap/regcache.c:301
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff81b6fbc0-ffffffff81b6fcdf: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81bc3830)
Location: drivers/base/regmap/regcache.c:301
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff81bc3830-ffffffff81bc394f: regcache_default_sync (STB_LOCAL)
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
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffff800010918d70)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffff800010918d70-ffff800010918ee4: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c09fe9ac)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
c09fe9ac-c09feb14: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c0000000009bc660)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
c0000000009bc660-c0000000009bc874: regcache_default_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffe0005990fc)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffe0005990fc-ffffffe000599210: regcache_default_sync (STB_LOCAL)
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
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff816ea480-ffffffff816ea578: regcache_default_sync (STB_LOCAL)
ffffffff816eacb9-ffffffff816eacd9: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff816c4ac0-ffffffff816c4bb8: regcache_default_sync (STB_LOCAL)
ffffffff816c52f9-ffffffff816c5319: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff81717610-ffffffff81717708: regcache_default_sync (STB_LOCAL)
ffffffff81717e49-ffffffff81717e69: regcache_default_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regcache_default_sync(struct regmap *map, unsigned int min, unsigned int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:294
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
```
**Symbols:**

```
ffffffff81732910-ffffffff81732a08: regcache_default_sync (STB_LOCAL)
ffffffff817331a9-ffffffff817331c9: regcache_default_sync.cold (STB_LOCAL)
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
