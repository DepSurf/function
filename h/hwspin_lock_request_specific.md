# Function: <code>hwspin_lock_request_specific</code>

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
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811aa0)
Location: drivers/hwspinlock/hwspinlock_core.c:590
Inline: False
```
**Symbols:**

```
ffffffff81811aa0-ffffffff81811b6d: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:617
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff8185bc11-ffffffff8185bc49: hwspin_lock_request_specific.cold.9 (STB_LOCAL)
ffffffff8185b640-ffffffff8185b6e3: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:728
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff8187b331-ffffffff8187b369: hwspin_lock_request_specific.cold.13 (STB_LOCAL)
ffffffff8187abc0-ffffffff8187ac63: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff818c0ae9-ffffffff818c0b35: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff818c04d0-ffffffff818c0575: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff818f3538-ffffffff818f3571: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff818f2fd0-ffffffff818f3075: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:752
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff819c8e1f-ffffffff819c8e58: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff819c8790-ffffffff819c882f: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:752
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff81c2dc13-ffffffff81c2dc4c: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff819c84e0-ffffffff819c857f: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:752
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff81c1fdc2-ffffffff81c1fdfb: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff819ad430-ffffffff819ad4cf: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:752
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff81d31724-ffffffff81d3175d: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff81a5b980-ffffffff81a5ba1f: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:752
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff81efdbe7-ffffffff81efdc1c: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff81bcbb70-ffffffff81bcbc16: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d75550)
Location: drivers/hwspinlock/hwspinlock_core.c:752
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff81d75550-ffffffff81d75622: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de3490)
Location: drivers/hwspinlock/hwspinlock_core.c:752
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff81de3490-ffffffff81de3562: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e99580)
Location: drivers/hwspinlock/hwspinlock_core.c:757
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff81e99580-ffffffff81e99652: hwspin_lock_request_specific (STB_GLOBAL)
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
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7eb78)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffff800010b7eb78-ffff800010b7ec70: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c62800)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
c0c62800-c0c628f4: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a740)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
c000000000c5a740-c000000000c5a888: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072cb8a)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffe00072cb8a-ffffffe00072cc78: hwspin_lock_request_specific (STB_GLOBAL)
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
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff81894868-ffffffff818948a1: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff81894300-ffffffff818943a5: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff8184cd42-ffffffff8184cd7b: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff8184ca20-ffffffff8184cac5: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff818e8368-ffffffff818e83a1: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff818e7e00-ffffffff818e7ea5: hwspin_lock_request_specific (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request_specific(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:750
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
```
**Symbols:**

```
ffffffff81904fd0-ffffffff81905009: hwspin_lock_request_specific.cold (STB_LOCAL)
ffffffff81904b20-ffffffff81904bc5: hwspin_lock_request_specific (STB_GLOBAL)
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
