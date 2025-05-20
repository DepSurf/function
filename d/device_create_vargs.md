# Function: <code>device_create_vargs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81548c70)
Location: drivers/base/core.c:1745
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
Direct callers:
  - mm/backing-dev.c:bdi_register
```
**Symbols:**

```
ffffffff81548c70-ffffffff81548c8e: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159a8e6)
Location: drivers/base/core.c:1745
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
Direct callers:
  - mm/backing-dev.c:bdi_register
```
**Symbols:**

```
ffffffff8159a8a0-ffffffff8159a8be: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c8e46)
Location: drivers/base/core.c:2336
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
Direct callers:
  - mm/backing-dev.c:bdi_register
```
**Symbols:**

```
ffffffff815c8e00-ffffffff815c8e1e: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815ddb57)
Location: drivers/base/core.c:2334
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff815ddb20-ffffffff815ddb38: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81644b57)
Location: drivers/base/core.c:2469
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff81644b20-ffffffff81644b38: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167ff9b)
Location: drivers/base/core.c:2516
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff8167ff40-ffffffff8167ff58: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169ecdb)
Location: drivers/base/core.c:2591
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff8169ec80-ffffffff8169ec98: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d728b)
Location: drivers/base/core.c:2845
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff816d7230-ffffffff816d7248: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fb38b)
Location: drivers/base/core.c:2882
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff816fb330-ffffffff816fb348: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e5a94)
Location: drivers/base/core.c:2882
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
Direct callers:
  - mm/backing-dev.c:bdi_register_va
```
**Symbols:**

```
ffff8000108e5988-ffff8000108e5a00: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d4130)
Location: drivers/base/core.c:2882
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
Direct callers:
  - mm/backing-dev.c:bdi_register_va
```
**Symbols:**

```
c09d40b0-c09d40e8: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097b4ec)
Location: drivers/base/core.c:2882
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
c00000000097b4a0-c00000000097b4c4: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057a6ac)
Location: drivers/base/core.c:2882
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffe00057a624-ffffffe00057a678: device_create_vargs (STB_GLOBAL)
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
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c0b7b)
Location: drivers/base/core.c:2882
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff816c0b20-ffffffff816c0b38: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169be2b)
Location: drivers/base/core.c:2882
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff8169bdd0-ffffffff8169bde8: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef04b)
Location: drivers/base/core.c:2882
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff816eeff0-ffffffff816ef008: device_create_vargs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct device *device_create_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817096ab)
Location: drivers/base/core.c:2882
Inline: True
Inline callers:
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff81709650-ffffffff81709668: device_create_vargs (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
