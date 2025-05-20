# Function: <code>__dev_alloc_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81718320)
Location: net/core/dev.c:1021
Inline: False
```
**Symbols:**

```
ffffffff81718320-ffffffff817184ad: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81780b70)
Location: net/core/dev.c:1025
Inline: False
```
**Symbols:**

```
ffffffff81780b70-ffffffff81780cfd: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ae0c0)
Location: net/core/dev.c:1024
Inline: False
```
**Symbols:**

```
ffffffff817ae0c0-ffffffff817ae24d: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cc9e0)
Location: net/core/dev.c:1056
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff817cc9e0-ffffffff817ccb61: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846392)
Location: net/core/dev.c:1059
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188fa61)
Location: net/core/dev.c:1059
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b01d1)
Location: net/core/dev.c:1061
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fcf12)
Location: net/core/dev.c:1057
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192f522)
Location: net/core/dev.c:975
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02d10)
Location: net/core/dev.c:1168
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81a02d10-ffffffff81a02ea8: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04870)
Location: net/core/dev.c:1158
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81a04870-ffffffff81a04a86: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e9a90)
Location: net/core/dev.c:1206
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff819e9a90-ffffffff819e9ca6: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9a760)
Location: net/core/dev.c:1081
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81a9a760-ffffffff81a9a976: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c13ee0)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81c13ee0-ffffffff81c140e7: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc4590)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81dc4590-ffffffff81dc4797: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e345f0)
Location: net/core/dev.c:1053
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81e345f0-ffffffff81e347f7: __dev_alloc_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dev_alloc_name(struct net *net, const char *name, char *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeaa40)
Location: net/core/dev.c:1070
Inline: False
```
**Symbols:**

```
ffffffff81eeaa40-ffffffff81eeaca2: __dev_alloc_name (STB_LOCAL)
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
In net/core/dev.c (ffff800010bccb80)
Location: net/core/dev.c:975
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
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
In net/core/dev.c (c0ce84b8)
Location: net/core/dev.c:975
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca99e0)
Location: net/core/dev.c:975
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000757264)
Location: net/core/dev.c:975
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cf522)
Location: net/core/dev.c:975
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81889642)
Location: net/core/dev.c:975
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81920522)
Location: net/core/dev.c:975
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81942282)
Location: net/core/dev.c:975
Inline: True
Inline callers:
  - net/core/dev.c:dev_alloc_name_ns
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *res</code>
</li>
<li>
<b>Param removed. </b>
<code>char *buf</code>
</li>
</ul>
</details>
</li>
</ul>
