# Function: <code>regcache_hw_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81567a20)
Location: drivers/base/regmap/regcache.c:28
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815bc250)
Location: drivers/base/regmap/regcache.c:28
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff815bc250-ffffffff815bc4c6: regcache_hw_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815eb660)
Location: drivers/base/regmap/regcache.c:28
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff815eb660-ffffffff815eb8d6: regcache_hw_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815fff80)
Location: drivers/base/regmap/regcache.c:30
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff815fff80-ffffffff8160021f: regcache_hw_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816682d0)
Location: drivers/base/regmap/regcache.c:30
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff816682d0-ffffffff8166856f: regcache_hw_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816a3c40)
Location: drivers/base/regmap/regcache.c:30
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff816a3c40-ffffffff816a3ed6: regcache_hw_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4780)
Location: drivers/base/regmap/regcache.c:30
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff816c4780-ffffffff816c4a16: regcache_hw_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff816ff820-ffffffff816ffa02: regcache_hw_init (STB_LOCAL)
ffffffff81700540-ffffffff817005e3: regcache_hw_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff81723ba0-ffffffff81723d82: regcache_hw_init (STB_LOCAL)
ffffffff8172489a-ffffffff8172493d: regcache_hw_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff817e02e0-ffffffff817e04c7: regcache_hw_init (STB_LOCAL)
ffffffff817e0c59-ffffffff817e0cfc: regcache_hw_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff817f51d0-ffffffff817f53b7: regcache_hw_init (STB_LOCAL)
ffffffff81c0f52e-ffffffff81c0f5d1: regcache_hw_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: True
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff817d9b90-ffffffff817d9d77: regcache_hw_init.constprop.0 (STB_LOCAL)
ffffffff81c01678-ffffffff81c0171b: regcache_hw_init.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: True
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff818652c0-ffffffff818654b7: regcache_hw_init.constprop.0 (STB_LOCAL)
ffffffff81d04ebb-ffffffff81d04f93: regcache_hw_init.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: True
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff819ad7f0-ffffffff819ad9de: regcache_hw_init.constprop.0 (STB_LOCAL)
ffffffff81ecd8ff-ffffffff81ecd9dc: regcache_hw_init.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: True
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff81b21110-ffffffff81b213c3: regcache_hw_init.constprop.0 (STB_LOCAL)
ffffffff82099586-ffffffff820995b0: regcache_hw_init.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:24
Inline: True
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff81b70310-ffffffff81b705c3: regcache_hw_init.constprop.0 (STB_LOCAL)
ffffffff8211a608-ffffffff8211a632: regcache_hw_init.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:24
Inline: True
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff81bc4010-ffffffff81bc42c3: regcache_hw_init.constprop.0 (STB_LOCAL)
ffffffff821f848d-ffffffff821f84b7: regcache_hw_init.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c0000000009bbcd0)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
c0000000009bbcd0-c0000000009bc058: regcache_hw_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffe000598b96)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffe000598b96-ffffffe000598d7c: regcache_hw_init (STB_LOCAL)
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
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff816e9ed0-ffffffff816ea0b2: regcache_hw_init (STB_LOCAL)
ffffffff816eabca-ffffffff816eac6d: regcache_hw_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff816c4510-ffffffff816c46f2: regcache_hw_init (STB_LOCAL)
ffffffff816c520a-ffffffff816c52ad: regcache_hw_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff81717060-ffffffff81717242: regcache_hw_init (STB_LOCAL)
ffffffff81717d5a-ffffffff81717dfd: regcache_hw_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regcache_hw_init(struct regmap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:26
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_init
```
**Symbols:**

```
ffffffff81732360-ffffffff81732542: regcache_hw_init (STB_LOCAL)
ffffffff817330ba-ffffffff8173315d: regcache_hw_init.cold (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
