# Function: <code>detect_cache_attributes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int detect_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815525a0)
Location: drivers/base/cacheinfo.c:185
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
```
**Symbols:**

```
ffffffff815525a0-ffffffff8155272a: detect_cache_attributes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int detect_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815a4540)
Location: drivers/base/cacheinfo.c:185
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
```
**Symbols:**

```
ffffffff815a4540-ffffffff815a46d0: detect_cache_attributes (STB_LOCAL)
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
In drivers/base/cacheinfo.c (ffffffff815d2d4c)
Location: drivers/base/cacheinfo.c:314
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
In drivers/base/cacheinfo.c (ffffffff815e78bc)
Location: drivers/base/cacheinfo.c:314
Inline: True
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
In drivers/base/cacheinfo.c (ffffffff8164ec6c)
Location: drivers/base/cacheinfo.c:327
Inline: True
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
In drivers/base/cacheinfo.c (ffffffff8168a3f5)
Location: drivers/base/cacheinfo.c:313
Inline: True
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
In drivers/base/cacheinfo.c (ffffffff816a98f5)
Location: drivers/base/cacheinfo.c:307
Inline: True
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
In drivers/base/cacheinfo.c (ffffffff816e2ef5)
Location: drivers/base/cacheinfo.c:312
Inline: True
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
In drivers/base/cacheinfo.c (ffffffff817070a5)
Location: drivers/base/cacheinfo.c:312
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int detect_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:312
Inline: False
```
**Symbols:**

```
ffffffff817c1f50-ffffffff817c200e: detect_cache_attributes (STB_LOCAL)
ffffffff817c21c1-ffffffff817c21d5: detect_cache_attributes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int detect_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:312
Inline: False
```
**Symbols:**

```
ffffffff817d7170-ffffffff817d722e: detect_cache_attributes (STB_LOCAL)
ffffffff81c0e603-ffffffff81c0e617: detect_cache_attributes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817badf0)
Location: drivers/base/cacheinfo.c:312
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81844f72)
Location: drivers/base/cacheinfo.c:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff819891a4)
Location: drivers/base/cacheinfo.c:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int detect_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81af7ed0)
Location: drivers/base/cacheinfo.c:352
Inline: False
```
**Symbols:**

```
ffffffff81af7ed0-ffffffff81af80de: detect_cache_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int detect_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b4649b)
Location: drivers/base/cacheinfo.c:564
Inline: True
```
**Symbols:**

```
ffffffff8211975f-ffffffff8211977a: detect_cache_attributes.cold (STB_LOCAL)
ffffffff81b463b0-ffffffff81b46608: detect_cache_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int detect_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b9e80a)
Location: drivers/base/cacheinfo.c:571
Inline: True
```
**Symbols:**

```
ffffffff821f7721-ffffffff821f773c: detect_cache_attributes.cold (STB_LOCAL)
ffffffff81b9e6c0-ffffffff81b9e946: detect_cache_attributes (STB_GLOBAL)
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
In drivers/base/cacheinfo.c (ffff8000108f4574)
Location: drivers/base/cacheinfo.c:312
Inline: True
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
In drivers/base/cacheinfo.c (c09e0aa4)
Location: drivers/base/cacheinfo.c:312
Inline: True
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
In drivers/base/cacheinfo.c (c00000000098e540)
Location: drivers/base/cacheinfo.c:312
Inline: True
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
In drivers/base/cacheinfo.c (ffffffe000585b1c)
Location: drivers/base/cacheinfo.c:312
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
In drivers/base/cacheinfo.c (ffffffff816cc7f5)
Location: drivers/base/cacheinfo.c:312
Inline: True
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
In drivers/base/cacheinfo.c (ffffffff816a7b25)
Location: drivers/base/cacheinfo.c:312
Inline: True
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
In drivers/base/cacheinfo.c (ffffffff816fad65)
Location: drivers/base/cacheinfo.c:312
Inline: True
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
In drivers/base/cacheinfo.c (ffffffff81715605)
Location: drivers/base/cacheinfo.c:312
Inline: True
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
