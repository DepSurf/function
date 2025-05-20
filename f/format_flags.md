# Function: <code>format_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81735630)
Location: net/core/net-sysfs.c:318
Inline: False
```
**Symbols:**

```
ffffffff81735630-ffffffff81735655: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
char *format_flags(char *buf, char *end, long unsigned int flags, const struct trace_print_flags *names);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81439db8)
Location: lib/vsprintf.c:1408
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
```
In net/core/net-sysfs.c (ffffffff817a1780)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff817a1780-ffffffff817a17a5: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
char *format_flags(char *buf, char *end, long unsigned int flags, const struct trace_print_flags *names);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81456d98)
Location: lib/vsprintf.c:1408
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
```
In net/core/net-sysfs.c (ffffffff817d00a0)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff817d00a0-ffffffff817d00c5: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817ef4a0)
Location: net/core/net-sysfs.c:322
Inline: False
```
```
In lib/vsprintf.c (ffffffff818f8628)
Location: lib/vsprintf.c:1409
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff817ef4a0-ffffffff817ef4c5: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff8186aa40)
Location: net/core/net-sysfs.c:326
Inline: False
```
```
In lib/vsprintf.c (ffffffff8197f0e8)
Location: lib/vsprintf.c:1464
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff8186aa40-ffffffff8186aa65: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818bb2e0)
Location: net/core/net-sysfs.c:347
Inline: False
```
```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:1483
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff818bb2e0-ffffffff818bb305: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818e23d0)
Location: net/core/net-sysfs.c:348
Inline: False
```
```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:1667
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff818e23d0-ffffffff818e23f5: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819319c0)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (ffffffff81a82c7f)
Location: lib/vsprintf.c:1808
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff819319c0-ffffffff819319e6: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81964500)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (ffffffff81ab9e8f)
Location: lib/vsprintf.c:1817
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81964500-ffffffff81964526: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:1889
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
```
In net/core/net-sysfs.c (ffffffff81a38fb4)
Location: net/core/net-sysfs.c:355
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:1893
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
```
In net/core/net-sysfs.c (ffffffff81a3aba4)
Location: net/core/net-sysfs.c:356
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
char *format_flags(char *buf, char *end, long unsigned int flags, const struct trace_print_flags *names);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fe180)
Location: lib/vsprintf.c:1955
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
```
```
In net/core/net-sysfs.c (ffffffff81a22504)
Location: net/core/net-sysfs.c:356
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_show
```
**Symbols:**

```
ffffffff815fe180-ffffffff815fe21a: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
char *format_flags(char *buf, char *end, long unsigned int flags, const struct trace_print_flags *names);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166be50)
Location: lib/vsprintf.c:1972
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
```
```
In net/core/net-sysfs.c (ffffffff81ad64a4)
Location: net/core/net-sysfs.c:376
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_show
```
**Symbols:**

```
ffffffff8166be50-ffffffff8166beea: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
char *format_flags(char *buf, char *end, long unsigned int flags, const struct trace_print_flags *names);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81785ec0)
Location: lib/vsprintf.c:1960
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
```
```
In net/core/net-sysfs.c (ffffffff81c56914)
Location: net/core/net-sysfs.c:378
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_show
```
**Symbols:**

```
ffffffff81785ec0-ffffffff81785f8c: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81e0c8a4)
Location: net/core/net-sysfs.c:378
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_show
```
```
In lib/vsprintf.c (ffffffff82042f60)
Location: lib/vsprintf.c:1961
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff82042f60-ffffffff8204302c: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81e7f8f4)
Location: net/core/net-sysfs.c:378
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_show
```
```
In lib/vsprintf.c (ffffffff820c1500)
Location: lib/vsprintf.c:1961
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff820c1500-ffffffff820c15b3: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81f40874)
Location: net/core/net-sysfs.c:390
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_show
```
```
In lib/vsprintf.c (ffffffff8219be30)
Location: lib/vsprintf.c:1963
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff8219be30-ffffffff8219bee3: format_flags (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffff800010c08f58)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (ffff800010d94644)
Location: lib/vsprintf.c:1817
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffff800010c08f58-ffff800010c08f9c: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c0d21e90)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (c0e91d78)
Location: lib/vsprintf.c:1817
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
c0d21e90-c0d21ebc: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c000000000cf39c0)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (c000000000ed901c)
Location: lib/vsprintf.c:1817
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
c000000000cf39c0-c000000000cf3a08: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffe000786c2c)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (ffffffe0008be50c)
Location: lib/vsprintf.c:1817
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffe000786c2c-ffffffe000786c68: format_flags (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819044d0)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (ffffffff81a58cdf)
Location: lib/vsprintf.c:1817
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff819044d0-ffffffff819044f6: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818be300)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (ffffffff81a15dbf)
Location: lib/vsprintf.c:1817
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff818be300-ffffffff818be326: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81955500)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (ffffffff81ac50cf)
Location: lib/vsprintf.c:1817
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81955500-ffffffff81955526: format_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t format_flags(const struct net_device *dev, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81977580)
Location: net/core/net-sysfs.c:343
Inline: False
```
```
In lib/vsprintf.c (ffffffff81ad159f)
Location: lib/vsprintf.c:1817
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81977580-ffffffff819775a6: format_flags (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *end</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param added. </b>
<code>const struct trace_print_flags *names</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct net_device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, buf</code> ➡️ <code>buf, end, flags, names</code>
</li>
<li>
<b>Return type changed. </b>
<code>ssize_t</code> ➡️ <code>char *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct net_device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>char *end</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct trace_print_flags *names</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, end, flags, names</code> ➡️ <code>dev, buf</code>
</li>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct net_device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>char *end</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct trace_print_flags *names</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, end, flags, names</code> ➡️ <code>dev, buf</code>
</li>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
