# Function: <code>dev_alloc_name_ns</code>

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
In net/core/dev.c (ffffffff81718585)
Location: net/core/dev.c:1101
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81780dd5)
Location: net/core/dev.c:1105
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ae325)
Location: net/core/dev.c:1104
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ccc75)
Location: net/core/dev.c:1136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846360)
Location: net/core/dev.c:1112
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff81846360-ffffffff8184653e: dev_alloc_name_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1112
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff8188fa30-ffffffff8188fbff: dev_alloc_name_ns (STB_LOCAL)
ffffffff81898f52-ffffffff81898f6a: dev_alloc_name_ns.cold.153 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1114
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff818b01a0-ffffffff818b036f: dev_alloc_name_ns (STB_LOCAL)
ffffffff818bb3be-ffffffff818bb3d6: dev_alloc_name_ns.cold.159 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1110
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff818fced0-ffffffff818fd0b3: dev_alloc_name_ns (STB_LOCAL)
ffffffff819072a7-ffffffff819072bf: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff8192f4e0-ffffffff8192f6c3: dev_alloc_name_ns (STB_LOCAL)
ffffffff81939907-ffffffff8193991f: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1221
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff81a02eb0-ffffffff81a02f45: dev_alloc_name_ns (STB_LOCAL)
ffffffff81a0ee7c-ffffffff81a0ee94: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1223
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff81a04a90-ffffffff81a04b25: dev_alloc_name_ns (STB_LOCAL)
ffffffff81c311c2-ffffffff81c311da: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1271
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff819e9cb0-ffffffff819e9d45: dev_alloc_name_ns (STB_LOCAL)
ffffffff81c2345d-ffffffff81c23475: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1146
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff81a9a980-ffffffff81a9aa15: dev_alloc_name_ns (STB_LOCAL)
ffffffff81d35fdf-ffffffff81d35ff7: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1093
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff81c140f0-ffffffff81c1419d: dev_alloc_name_ns (STB_LOCAL)
ffffffff81f02879-ffffffff81f02891: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc47b0)
Location: net/core/dev.c:1093
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff81dc47b0-ffffffff81dc485c: dev_alloc_name_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e34810)
Location: net/core/dev.c:1118
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff81e34810-ffffffff81e348bc: dev_alloc_name_ns (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bccb40)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffff800010bccb40-ffff800010bccd88: dev_alloc_name_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce847c)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
c0ce847c-c0ce8684: dev_alloc_name_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca9990)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
c000000000ca9990-c000000000ca9d40: dev_alloc_name_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000757236)
Location: net/core/dev.c:1028
Inline: True
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffe000757236-ffffffe0007573c2: dev_alloc_name_ns (STB_LOCAL)
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
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff818cf4e0-ffffffff818cf6c3: dev_alloc_name_ns (STB_LOCAL)
ffffffff818d98d7-ffffffff818d98ef: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff81889600-ffffffff818897e3: dev_alloc_name_ns (STB_LOCAL)
ffffffff81893717-ffffffff8189372f: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff819204e0-ffffffff819206c3: dev_alloc_name_ns (STB_LOCAL)
ffffffff8192a907-ffffffff8192a91f: dev_alloc_name_ns.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dev_alloc_name_ns(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1028
Inline: False
Direct callers:
  - net/core/dev.c:dev_alloc_name
```
**Symbols:**

```
ffffffff81942240-ffffffff81942423: dev_alloc_name_ns (STB_LOCAL)
ffffffff8194c051-ffffffff8194c069: dev_alloc_name_ns.cold (STB_LOCAL)
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
