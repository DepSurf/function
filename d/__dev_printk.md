# Function: <code>__dev_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815476d0)
Location: drivers/base/core.c:2189
Inline: False
Direct callers:
  - drivers/base/core.c:dev_printk
  - drivers/base/core.c:dev_emerg
  - drivers/base/core.c:dev_alert
  - drivers/base/core.c:dev_crit
  - drivers/base/core.c:dev_err
  - drivers/base/core.c:dev_warn
  - drivers/base/core.c:dev_notice
  - drivers/base/core.c:_dev_info
```
**Symbols:**

```
ffffffff815476d0-ffffffff81547750: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81599430)
Location: drivers/base/core.c:2189
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:dev_notice
  - drivers/base/core.c:dev_warn
  - drivers/base/core.c:dev_err
  - drivers/base/core.c:dev_crit
  - drivers/base/core.c:dev_alert
  - drivers/base/core.c:dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff81599430-ffffffff815994b0: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c6d70)
Location: drivers/base/core.c:2780
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:dev_notice
  - drivers/base/core.c:dev_warn
  - drivers/base/core.c:dev_err
  - drivers/base/core.c:dev_crit
  - drivers/base/core.c:dev_alert
  - drivers/base/core.c:dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff815c6d70-ffffffff815c6df0: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dbb00)
Location: drivers/base/core.c:2782
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:dev_notice
  - drivers/base/core.c:dev_warn
  - drivers/base/core.c:dev_err
  - drivers/base/core.c:dev_crit
  - drivers/base/core.c:dev_alert
  - drivers/base/core.c:dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff815dbb00-ffffffff815dbb80: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642b30)
Location: drivers/base/core.c:2918
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:dev_notice
  - drivers/base/core.c:dev_warn
  - drivers/base/core.c:dev_err
  - drivers/base/core.c:dev_crit
  - drivers/base/core.c:dev_alert
  - drivers/base/core.c:dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff81642b30-ffffffff81642ba6: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:2973
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:dev_notice
  - drivers/base/core.c:dev_warn
  - drivers/base/core.c:dev_err
  - drivers/base/core.c:dev_crit
  - drivers/base/core.c:dev_alert
  - drivers/base/core.c:dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff8167dc90-ffffffff8167dcf7: __dev_printk (STB_LOCAL)
ffffffff8168081d-ffffffff81680831: __dev_printk.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3048
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff8169d690-ffffffff8169d6f7: __dev_printk (STB_LOCAL)
ffffffff816a02ad-ffffffff816a02c1: __dev_printk.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d8c99)
Location: drivers/base/core.c:3302
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff816d8c99-ffffffff816d8d08: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fcd1f)
Location: drivers/base/core.c:3454
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff816fcd1f-ffffffff816fcd8e: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b6675)
Location: drivers/base/core.c:3922
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff817b6675-ffffffff817b66e1: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81c0ddc3)
Location: drivers/base/core.c:4320
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff81c0ddc3-ffffffff81c0de2f: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81c00161)
Location: drivers/base/core.c:4547
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff81c00161-ffffffff81c001cd: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81d026d2)
Location: drivers/base/core.c:4612
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:_dev_printk
```
**Symbols:**

```
ffffffff81d026d2-ffffffff81d0273e: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ecacc3)
Location: drivers/base/core.c:4646
Inline: True
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:_dev_printk
```
**Symbols:**

```
ffffffff81ecacc3-ffffffff81ecad44: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae2b50)
Location: drivers/base/core.c:4865
Inline: True
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:_dev_printk
```
**Symbols:**

```
ffffffff81ae2b50-ffffffff81ae2bee: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b30a70)
Location: drivers/base/core.c:4870
Inline: True
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:_dev_printk
```
**Symbols:**

```
ffffffff81b30a70-ffffffff81b30b0e: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b88070)
Location: drivers/base/core.c:4883
Inline: True
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:_dev_printk
```
**Symbols:**

```
ffffffff81b88070-ffffffff81b8810e: __dev_printk (STB_LOCAL)
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
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e792c)
Location: drivers/base/core.c:3454
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffff8000108e792c-ffff8000108e79cc: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d5d84)
Location: drivers/base/core.c:3454
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
c09d5d84-c09d5e1c: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097db80)
Location: drivers/base/core.c:3454
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
c00000000097db80-c00000000097dc2c: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057bebe)
Location: drivers/base/core.c:3454
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffe00057bebe-ffffffe00057bf3c: __dev_printk (STB_LOCAL)
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
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c250f)
Location: drivers/base/core.c:3454
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff816c250f-ffffffff816c257e: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d7bf)
Location: drivers/base/core.c:3454
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff8169d7bf-ffffffff8169d82e: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f09df)
Location: drivers/base/core.c:3454
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff816f09df-ffffffff816f0a4e: __dev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dev_printk(const char *level, const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8170b21f)
Location: drivers/base/core.c:3454
Inline: False
Direct callers:
  - drivers/base/core.c:_dev_info
  - drivers/base/core.c:_dev_notice
  - drivers/base/core.c:_dev_warn
  - drivers/base/core.c:_dev_err
  - drivers/base/core.c:_dev_crit
  - drivers/base/core.c:_dev_alert
  - drivers/base/core.c:_dev_emerg
  - drivers/base/core.c:dev_printk
```
**Symbols:**

```
ffffffff8170b21f-ffffffff8170b28e: __dev_printk (STB_LOCAL)
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
