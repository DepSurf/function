# Function: <code>dev_printk_emit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81547440)
Location: drivers/base/core.c:2174
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff81547440-ffffffff815474a5: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815990b0)
Location: drivers/base/core.c:2174
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff815990b0-ffffffff81599115: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c69f0)
Location: drivers/base/core.c:2765
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff815c69f0-ffffffff815c6a55: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815db790)
Location: drivers/base/core.c:2767
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff815db790-ffffffff815db7f6: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816427c0)
Location: drivers/base/core.c:2903
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff816427c0-ffffffff81642826: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167dae0)
Location: drivers/base/core.c:2958
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff8167dae0-ffffffff8167db45: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d4e0)
Location: drivers/base/core.c:3033
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff8169d4e0-ffffffff8169d545: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d8c21)
Location: drivers/base/core.c:3287
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff816d8c21-ffffffff816d8c86: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fccba)
Location: drivers/base/core.c:3439
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff816fccba-ffffffff816fcd1f: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b6610)
Location: drivers/base/core.c:3907
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff817b6610-ffffffff817b6675: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81c0dd5e)
Location: drivers/base/core.c:4305
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81c0dd5e-ffffffff81c0ddc3: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81c000fc)
Location: drivers/base/core.c:4532
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81c000fc-ffffffff81c00161: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81d02652)
Location: drivers/base/core.c:4597
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81d02652-ffffffff81d026b7: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ecac1b)
Location: drivers/base/core.c:4631
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81ecac1b-ffffffff81ecaca8: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae1a90)
Location: drivers/base/core.c:4850
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81ae1a90-ffffffff81ae1b66: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2f8b0)
Location: drivers/base/core.c:4855
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81b2f8b0-ffffffff81b2f986: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b870b0)
Location: drivers/base/core.c:4868
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81b870b0-ffffffff81b87186: dev_printk_emit (STB_GLOBAL)
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
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e788c)
Location: drivers/base/core.c:3439
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffff8000108e788c-ffff8000108e792c: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d5d20)
Location: drivers/base/core.c:3439
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
c09d5d20-c09d5d84: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097db38)
Location: drivers/base/core.c:3439
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
c00000000097db38-c00000000097db80: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057be6e)
Location: drivers/base/core.c:3439
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffe00057be6e-ffffffe00057bebe: dev_printk_emit (STB_GLOBAL)
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
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c24aa)
Location: drivers/base/core.c:3439
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff816c24aa-ffffffff816c250f: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d75a)
Location: drivers/base/core.c:3439
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff8169d75a-ffffffff8169d7bf: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f097a)
Location: drivers/base/core.c:3439
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff816f097a-ffffffff816f09df: dev_printk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_printk_emit(int level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8170b1ba)
Location: drivers/base/core.c:3439
Inline: False
Direct callers:
  - lib/dynamic_debug.c:__dynamic_ibdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_dev_dbg
  - drivers/base/core.c:__dev_printk
```
**Symbols:**

```
ffffffff8170b1ba-ffffffff8170b21f: dev_printk_emit (STB_GLOBAL)
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
