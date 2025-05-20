# Function: <code>regmap_debugfs_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff8156a260)
Location: drivers/base/regmap/regmap-debugfs.c:549
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff8156a260-ffffffff8156a541: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff815bee00)
Location: drivers/base/regmap/regmap-debugfs.c:516
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff815bee00-ffffffff815bf0e4: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff815ee210)
Location: drivers/base/regmap/regmap-debugfs.c:526
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff815ee210-ffffffff815ee4f4: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff81602410)
Location: drivers/base/regmap/regmap-debugfs.c:526
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff81602410-ffffffff816026ff: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff8166a7c0)
Location: drivers/base/regmap/regmap-debugfs.c:526
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff8166a7c0-ffffffff8166aab2: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff816a6110)
Location: drivers/base/regmap/regmap-debugfs.c:531
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff816a6110-ffffffff816a64b7: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff816c6c50)
Location: drivers/base/regmap/regmap-debugfs.c:521
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff816c6c50-ffffffff816c6ff7: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff81701e4b)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff81702430-ffffffff8170245f: regmap_debugfs_init.cold (STB_LOCAL)
ffffffff81701e20-ffffffff81702197: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff817261d0)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff817261d0-ffffffff81726534: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff817e1f40)
Location: drivers/base/regmap/regmap-debugfs.c:547
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff817e1f40-ffffffff817e225c: regmap_debugfs_init.part.0 (STB_LOCAL)
ffffffff817e2910-ffffffff817e2949: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void regmap_debugfs_init(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff817f7300)
Location: drivers/base/regmap/regmap-debugfs.c:546
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff817f7300-ffffffff817f767b: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void regmap_debugfs_init(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff817dba90)
Location: drivers/base/regmap/regmap-debugfs.c:546
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff817dba90-ffffffff817dbe0e: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: drivers/base/regmap/regmap-debugfs.c:546
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff81d05315-ffffffff81d0532a: regmap_debugfs_init.cold (STB_LOCAL)
ffffffff818673d0-ffffffff81867763: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: drivers/base/regmap/regmap-debugfs.c:546
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff81ecdd08-ffffffff81ecdd1c: regmap_debugfs_init.cold (STB_LOCAL)
ffffffff819afa70-ffffffff819afe59: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: drivers/base/regmap/regmap-debugfs.c:546
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff820997cf-ffffffff820997e3: regmap_debugfs_init.cold (STB_LOCAL)
ffffffff81b23750-ffffffff81b23b39: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: drivers/base/regmap/regmap-debugfs.c:546
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff8211a85c-ffffffff8211a870: regmap_debugfs_init.cold (STB_LOCAL)
ffffffff81b73870-ffffffff81b73c59: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: drivers/base/regmap/regmap-debugfs.c:546
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff821f86e1-ffffffff821f86f5: regmap_debugfs_init.cold (STB_LOCAL)
ffffffff81bc7690-ffffffff81bc7aa8: regmap_debugfs_init (STB_GLOBAL)
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
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffff80001091b238)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffff80001091b238-ffff80001091b56c: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (c0a00c94)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
c0a00c94-c0a00fb4: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (c0000000009bf1a0)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
c0000000009bf1a0-c0000000009bf6a8: regmap_debugfs_init.part.0 (STB_LOCAL)
c0000000009bfa20-c0000000009bfa88: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffe00059ae82)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffe00059ae82-ffffffe00059b18c: regmap_debugfs_init (STB_GLOBAL)
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
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff816ec500)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff816ec500-ffffffff816ec864: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff816c6b40)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff816c6b40-ffffffff816c6ea4: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff81719690)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff81719690-ffffffff817199f4: regmap_debugfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void regmap_debugfs_init(struct regmap *map, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff817349f0)
Location: drivers/base/regmap/regmap-debugfs.c:535
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
```
**Symbols:**

```
ffffffff817349f0-ffffffff81734d54: regmap_debugfs_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const char *name</code>
</li>
</ul>
</details>
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
