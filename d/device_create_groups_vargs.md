# Function: <code>device_create_groups_vargs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81548b80)
Location: drivers/base/core.c:1680
Inline: False
Direct callers:
  - drivers/base/core.c:device_create
  - drivers/base/core.c:device_create_with_groups
```
**Symbols:**

```
ffffffff81548b80-ffffffff81548c6b: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159a7b0)
Location: drivers/base/core.c:1680
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff8159a7b0-ffffffff8159a89b: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c8d10)
Location: drivers/base/core.c:2271
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff815c8d10-ffffffff815c8dfb: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dda30)
Location: drivers/base/core.c:2269
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff815dda30-ffffffff815ddb1c: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81644a30)
Location: drivers/base/core.c:2404
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff81644a30-ffffffff81644b1c: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167fe50)
Location: drivers/base/core.c:2451
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff8167fe50-ffffffff8167ff40: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169eb90)
Location: drivers/base/core.c:2526
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff8169eb90-ffffffff8169ec7e: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d7140)
Location: drivers/base/core.c:2780
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff816d7140-ffffffff816d722e: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fb240)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff816fb240-ffffffff816fb32e: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b4480)
Location: drivers/base/core.c:3318
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff817b4480-ffffffff817b456e: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817caaa0)
Location: drivers/base/core.c:3730
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff817caaa0-ffffffff817cab8e: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ae410)
Location: drivers/base/core.c:3957
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff817ae410-ffffffff817ae4fe: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81837630)
Location: drivers/base/core.c:4022
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff81837630-ffffffff8183771e: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819796f0)
Location: drivers/base/core.c:4056
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff819796f0-ffffffff819797f3: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae61e0)
Location: drivers/base/core.c:4275
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff81ae61e0-ffffffff81ae62e3: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(const struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b34580)
Location: drivers/base/core.c:4284
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff81b34580-ffffffff81b34683: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(const struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8bf80)
Location: drivers/base/core.c:4297
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff81b8bf80-ffffffff81b8c0b2: device_create_groups_vargs (STB_LOCAL)
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
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e5858)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffff8000108e5858-ffff8000108e5984: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d3fe0)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
c09d3fe0-c09d40b0: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097b330)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
c00000000097b330-c00000000097b49c: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057a554)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffe00057a554-ffffffe00057a624: device_create_groups_vargs (STB_LOCAL)
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
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c0a30)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff816c0a30-ffffffff816c0b1e: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169bce0)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff8169bce0-ffffffff8169bdce: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816eef00)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff816eef00-ffffffff816eefee: device_create_groups_vargs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *device_create_groups_vargs(struct class *class, struct device *parent, dev_t devt, void *drvdata, const struct attribute_group **groups, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709560)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - drivers/base/core.c:device_create_with_groups
  - drivers/base/core.c:device_create
```
**Symbols:**

```
ffffffff81709560-ffffffff8170964e: device_create_groups_vargs (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class *class</code> ➡️ <code>const struct class *class</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
