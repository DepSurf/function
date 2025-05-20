# Function: <code>twl_get_regmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81587720)
Location: drivers/mfd/twl-core.c:425
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_i2c_write
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff81587720-ffffffff8158779e: twl_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff815dc780)
Location: drivers/mfd/twl-core.c:425
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff815dc780-ffffffff815dc7fe: twl_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81609450)
Location: drivers/mfd/twl-core.c:424
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff81609450-ffffffff816094ce: twl_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff8161d430)
Location: drivers/mfd/twl-core.c:424
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff8161d430-ffffffff8161d4ae: twl_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81685c70)
Location: drivers/mfd/twl-core.c:424
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff81685c70-ffffffff81685cee: twl_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:424
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff816c1d80-ffffffff816c1ddc: twl_get_regmap (STB_LOCAL)
ffffffff816c23ff-ffffffff816c2435: twl_get_regmap.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff816e3ff8)
Location: drivers/mfd/twl-core.c:424
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff816e31c0-ffffffff816e321c: twl_get_regmap (STB_LOCAL)
ffffffff816e3ff8-ffffffff816e402e: twl_get_regmap.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff8171d5fd)
Location: drivers/mfd/twl-core.c:411
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff8171c860-ffffffff8171c8bc: twl_get_regmap (STB_LOCAL)
ffffffff8171d5fd-ffffffff8171d633: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff817418d0)
Location: drivers/mfd/twl-core.c:411
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff81740b30-ffffffff81740b8c: twl_get_regmap (STB_LOCAL)
ffffffff817418d0-ffffffff81741906: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:411
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff817fe300-ffffffff817fe35d: twl_get_regmap (STB_LOCAL)
ffffffff817ff3de-ffffffff817ff415: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:411
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff8180f730-ffffffff8180f78d: twl_get_regmap (STB_LOCAL)
ffffffff81c12fe9-ffffffff81c13020: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:411
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff817f3f60-ffffffff817f3fbd: twl_get_regmap (STB_LOCAL)
ffffffff81c05140-ffffffff81c05177: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:411
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff8187d270-ffffffff8187d2ea: twl_get_regmap (STB_LOCAL)
ffffffff81d08477-ffffffff81d084c0: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:411
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff819c56c0-ffffffff819c5746: twl_get_regmap (STB_LOCAL)
ffffffff81ed0912-ffffffff81ed0956: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:411
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff81b3c5a0-ffffffff81b3c648: twl_get_regmap (STB_LOCAL)
ffffffff8209a146-ffffffff8209a15b: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:414
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff81b8f9c0-ffffffff81b8fa68: twl_get_regmap (STB_LOCAL)
ffffffff8211b1ea-ffffffff8211b1ff: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:416
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff81be38e0-ffffffff81be3988: twl_get_regmap (STB_LOCAL)
ffffffff821f9071-ffffffff821f9086: twl_get_regmap.cold (STB_LOCAL)
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
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffff80001093c2d0)
Location: drivers/mfd/twl-core.c:411
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffff80001093c2d0-ffff80001093c378: twl_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (c0a25304)
Location: drivers/mfd/twl-core.c:411
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
c0a25304-c0a253a4: twl_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (c0000000009e3cf0)
Location: drivers/mfd/twl-core.c:411
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
c0000000009e3cf0-c0000000009e3dc4: twl_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffe0005b0798)
Location: drivers/mfd/twl-core.c:411
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffe0005b0798-ffffffe0005b082a: twl_get_regmap (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81734d90)
Location: drivers/mfd/twl-core.c:411
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff81733ff0-ffffffff8173404c: twl_get_regmap (STB_LOCAL)
ffffffff81734d90-ffffffff81734dc6: twl_get_regmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct regmap *twl_get_regmap(u8 mod_no);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff817501d0)
Location: drivers/mfd/twl-core.c:411
Inline: True
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
  - drivers/mfd/twl-core.c:twl_i2c_read
  - drivers/mfd/twl-core.c:twl_i2c_write
```
**Symbols:**

```
ffffffff8174f430-ffffffff8174f48c: twl_get_regmap (STB_LOCAL)
ffffffff817501d0-ffffffff81750206: twl_get_regmap.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
