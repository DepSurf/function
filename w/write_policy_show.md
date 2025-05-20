# Function: <code>write_policy_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81552190)
Location: drivers/base/cacheinfo.c:303
Inline: False
```
**Symbols:**

```
ffffffff81552190-ffffffff815521f6: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815a4130)
Location: drivers/base/cacheinfo.c:303
Inline: False
```
**Symbols:**

```
ffffffff815a4130-ffffffff815a4196: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815d27f0)
Location: drivers/base/cacheinfo.c:434
Inline: False
```
**Symbols:**

```
ffffffff815d27f0-ffffffff815d2859: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815e7380)
Location: drivers/base/cacheinfo.c:434
Inline: False
```
**Symbols:**

```
ffffffff815e7380-ffffffff815e73e9: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff8164e750)
Location: drivers/base/cacheinfo.c:447
Inline: False
```
**Symbols:**

```
ffffffff8164e750-ffffffff8164e7b9: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81689d90)
Location: drivers/base/cacheinfo.c:437
Inline: False
```
**Symbols:**

```
ffffffff81689d90-ffffffff81689df9: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816a9290)
Location: drivers/base/cacheinfo.c:431
Inline: False
```
**Symbols:**

```
ffffffff816a9290-ffffffff816a92f9: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816e2860)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
```
In drivers/base/node.c (ffffffff816f6ef0)
Location: drivers/base/node.c:235
Inline: False
```
**Symbols:**

```
ffffffff816e2860-ffffffff816e28d0: write_policy_show (STB_LOCAL)
ffffffff816f6ef0-ffffffff816f6f16: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81706a10)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
```
In drivers/base/node.c (ffffffff8171b300)
Location: drivers/base/node.c:235
Inline: False
```
**Symbols:**

```
ffffffff81706a10-ffffffff81706a80: write_policy_show (STB_LOCAL)
ffffffff8171b300-ffffffff8171b326: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817c1700)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
```
In drivers/base/node.c (ffffffff817d73c0)
Location: drivers/base/node.c:235
Inline: False
```
**Symbols:**

```
ffffffff817c1700-ffffffff817c1770: write_policy_show (STB_LOCAL)
ffffffff817d73c0-ffffffff817d73e6: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817d69c0)
Location: drivers/base/cacheinfo.c:443
Inline: False
```
```
In drivers/base/node.c (ffffffff817ebd40)
Location: drivers/base/node.c:241
Inline: False
```
**Symbols:**

```
ffffffff817d69c0-ffffffff817d6a07: write_policy_show (STB_LOCAL)
ffffffff817ebd40-ffffffff817ebd66: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817ba480)
Location: drivers/base/cacheinfo.c:443
Inline: False
```
```
In drivers/base/node.c (ffffffff817d0560)
Location: drivers/base/node.c:241
Inline: False
```
**Symbols:**

```
ffffffff817ba480-ffffffff817ba4c7: write_policy_show (STB_LOCAL)
ffffffff817d0560-ffffffff817d0586: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81844210)
Location: drivers/base/cacheinfo.c:444
Inline: False
```
```
In drivers/base/node.c (ffffffff8185ad00)
Location: drivers/base/node.c:245
Inline: False
```
**Symbols:**

```
ffffffff81844210-ffffffff81844257: write_policy_show (STB_LOCAL)
ffffffff8185ad00-ffffffff8185ad26: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff819884f0)
Location: drivers/base/cacheinfo.c:444
Inline: False
```
```
In drivers/base/node.c (ffffffff819a1c50)
Location: drivers/base/node.c:245
Inline: False
```
**Symbols:**

```
ffffffff819884f0-ffffffff8198855b: write_policy_show (STB_LOCAL)
ffffffff819a1c50-ffffffff819a1c7f: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81af6d40)
Location: drivers/base/cacheinfo.c:496
Inline: False
```
```
In drivers/base/node.c (ffffffff81b13b30)
Location: drivers/base/node.c:246
Inline: False
```
**Symbols:**

```
ffffffff81af6d40-ffffffff81af6dab: write_policy_show (STB_LOCAL)
ffffffff81b13b30-ffffffff81b13b5f: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b44ff0)
Location: drivers/base/cacheinfo.c:698
Inline: False
```
```
In drivers/base/node.c (ffffffff81b62860)
Location: drivers/base/node.c:246
Inline: False
```
**Symbols:**

```
ffffffff81b44ff0-ffffffff81b4505b: write_policy_show (STB_LOCAL)
ffffffff81b62860-ffffffff81b6288f: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b9d070)
Location: drivers/base/cacheinfo.c:705
Inline: False
```
```
In drivers/base/node.c (ffffffff81bb6370)
Location: drivers/base/node.c:245
Inline: False
```
**Symbols:**

```
ffffffff81b9d070-ffffffff81b9d0db: write_policy_show (STB_LOCAL)
ffffffff81bb6370-ffffffff81bb639f: write_policy_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffff8000108f3dd0)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
```
In drivers/base/node.c (ffff80001090ec20)
Location: drivers/base/node.c:235
Inline: False
```
**Symbols:**

```
ffff8000108f3dd0-ffff8000108f3e5c: write_policy_show (STB_LOCAL)
ffff80001090ec20-ffff80001090ec60: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (c09e060c)
Location: drivers/base/cacheinfo.c:436
Inline: True
```
**Symbols:**

```
c09e060c-c09e06a0: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (c00000000098dc90)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
**Symbols:**

```
c00000000098dc90-c00000000098dd1c: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffe0005853ae)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
**Symbols:**

```
ffffffe0005853ae-ffffffe000585476: write_policy_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816cc160)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
```
In drivers/base/node.c (ffffffff816e1630)
Location: drivers/base/node.c:235
Inline: False
```
**Symbols:**

```
ffffffff816cc160-ffffffff816cc1d0: write_policy_show (STB_LOCAL)
ffffffff816e1630-ffffffff816e1656: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816a7490)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
```
In drivers/base/node.c (ffffffff816bbc70)
Location: drivers/base/node.c:235
Inline: False
```
**Symbols:**

```
ffffffff816a7490-ffffffff816a7500: write_policy_show (STB_LOCAL)
ffffffff816bbc70-ffffffff816bbc96: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816fa6d0)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
**Symbols:**

```
ffffffff816fa6d0-ffffffff816fa740: write_policy_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t write_policy_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81714f70)
Location: drivers/base/cacheinfo.c:436
Inline: False
```
```
In drivers/base/node.c (ffffffff81729920)
Location: drivers/base/node.c:235
Inline: False
```
**Symbols:**

```
ffffffff81714f70-ffffffff81714fe0: write_policy_show (STB_LOCAL)
ffffffff81729920-ffffffff81729946: write_policy_show (STB_LOCAL)
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
