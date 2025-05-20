# Function: <code>hwspin_lock_free</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811650)
Location: drivers/hwspinlock/hwspinlock_core.c:638
Inline: False
```
**Symbols:**

```
ffffffff81811650-ffffffff8181176f: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:665
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff8185bc49-ffffffff8185bc67: hwspin_lock_free.cold.10 (STB_LOCAL)
ffffffff8185b6f0-ffffffff8185b7ec: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:776
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff8187b369-ffffffff8187b387: hwspin_lock_free.cold.14 (STB_LOCAL)
ffffffff8187acf0-ffffffff8187adec: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff818c09a5-ffffffff818c09fc: hwspin_lock_free.cold (STB_LOCAL)
ffffffff818c0180-ffffffff818c025a: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff818f3453-ffffffff818f3497: hwspin_lock_free.cold (STB_LOCAL)
ffffffff818f2ca0-ffffffff818f2d7a: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:800
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff819c8e58-ffffffff819c8e9c: hwspin_lock_free.cold (STB_LOCAL)
ffffffff819c88b0-ffffffff819c8981: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:800
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff81c2dc4c-ffffffff81c2dc90: hwspin_lock_free.cold (STB_LOCAL)
ffffffff819c8600-ffffffff819c86d1: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:800
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff81c1fdfb-ffffffff81c1fe3f: hwspin_lock_free.cold (STB_LOCAL)
ffffffff819ad550-ffffffff819ad621: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:800
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff81d3175d-ffffffff81d317a1: hwspin_lock_free.cold (STB_LOCAL)
ffffffff81a5bab0-ffffffff81a5bb81: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:800
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff81efdc1c-ffffffff81efdc60: hwspin_lock_free.cold (STB_LOCAL)
ffffffff81bcbcb0-ffffffff81bcbd8b: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d756e0)
Location: drivers/hwspinlock/hwspinlock_core.c:800
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff81d756e0-ffffffff81d757f8: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de3620)
Location: drivers/hwspinlock/hwspinlock_core.c:800
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff81de3620-ffffffff81de3738: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e99710)
Location: drivers/hwspinlock/hwspinlock_core.c:805
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff81e99710-ffffffff81e99828: hwspin_lock_free (STB_GLOBAL)
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
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e658)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffff800010b7e658-ffff800010b7e78c: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c6232c)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
c0c6232c-c0c6244c: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a970)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
c000000000c5a970-c000000000c5ab08: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072ccfe)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffe00072ccfe-ffffffe00072ce18: hwspin_lock_free (STB_GLOBAL)
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
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff81894783-ffffffff818947c7: hwspin_lock_free.cold (STB_LOCAL)
ffffffff81893fd0-ffffffff818940aa: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff8184cc5d-ffffffff8184cca1: hwspin_lock_free.cold (STB_LOCAL)
ffffffff8184c6f0-ffffffff8184c7ca: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff818e8283-ffffffff818e82c7: hwspin_lock_free.cold (STB_LOCAL)
ffffffff818e7ad0-ffffffff818e7baa: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_free(struct hwspinlock *hwlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_release
```
**Symbols:**

```
ffffffff81904eeb-ffffffff81904f2f: hwspin_lock_free.cold (STB_LOCAL)
ffffffff819047f0-ffffffff819048ca: hwspin_lock_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
