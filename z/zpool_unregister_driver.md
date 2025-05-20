# Function: <code>zpool_unregister_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812041d0)
Location: mm/zpool.c:57
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff812041d0-ffffffff8120424a: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81229170)
Location: mm/zpool.c:57
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff81229170-ffffffff812291ea: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff8123b710)
Location: mm/zpool.c:57
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff8123b710-ffffffff8123b78a: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81247370)
Location: mm/zpool.c:57
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff81247370-ffffffff812473d9: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81267510)
Location: mm/zpool.c:57
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff81267510-ffffffff81267579: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff8128be40)
Location: mm/zpool.c:58
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff8128be40-ffffffff8128bea9: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812a0da0)
Location: mm/zpool.c:58
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff812a0da0-ffffffff812a0e09: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff812bc4df-ffffffff812bc4f2: zpool_unregister_driver.cold (STB_LOCAL)
ffffffff812bc020-ffffffff812bc08a: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812cdf00)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff812cdf00-ffffffff812cdf6a: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81304210)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff81304210-ffffffff8130427d: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff8130ffd0)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff8130ffd0-ffffffff8131003d: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff813160a0)
Location: mm/zpool.c:60
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff813160a0-ffffffff8131610d: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff813621c0)
Location: mm/zpool.c:60
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff813621c0-ffffffff8136222d: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff813dec90)
Location: mm/zpool.c:55
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff813dec90-ffffffff813ded00: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81465970)
Location: mm/zpool.c:52
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff81465970-ffffffff814659e0: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff8149b3f0)
Location: mm/zpool.c:52
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff8149b3f0-ffffffff8149b460: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff814caad0)
Location: mm/zpool.c:52
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff814caad0-ffffffff814cab40: zpool_unregister_driver (STB_GLOBAL)
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
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffff800010372470)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffff800010372470-ffff800010372540: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (c055f058)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
c055f058-c055f0f8: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (c000000000463cd0)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
c000000000463cd0-c000000000463de8: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffe00024b622)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffe00024b622-ffffffe00024b6c4: zpool_unregister_driver (STB_GLOBAL)
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
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812c64e0)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff812c64e0-ffffffff812c654a: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812b7520)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff812b7520-ffffffff812b758a: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812c42f0)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff812c42f0-ffffffff812c435a: zpool_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int zpool_unregister_driver(struct zpool_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812d4d90)
Location: mm/zpool.c:59
Inline: False
Direct callers:
  - mm/zbud.c:exit_zbud
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffff812d4d90-ffffffff812d4dfc: zpool_unregister_driver (STB_GLOBAL)
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
