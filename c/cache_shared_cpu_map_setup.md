# Function: <code>cache_shared_cpu_map_setup</code>

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
In drivers/base/cacheinfo.c (ffffffff8155262c)
Location: drivers/base/cacheinfo.c:102
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
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
In drivers/base/cacheinfo.c (ffffffff815a45d0)
Location: drivers/base/cacheinfo.c:102
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
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
In drivers/base/cacheinfo.c (ffffffff815d2dd8)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (ffffffff815e795b)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (ffffffff8164ed08)
Location: drivers/base/cacheinfo.c:231
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
In drivers/base/cacheinfo.c (ffffffff8168a4a4)
Location: drivers/base/cacheinfo.c:222
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
In drivers/base/cacheinfo.c (ffffffff816a99a4)
Location: drivers/base/cacheinfo.c:216
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
In drivers/base/cacheinfo.c (ffffffff816e2f9a)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (ffffffff8170714a)
Location: drivers/base/cacheinfo.c:218
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cache_shared_cpu_map_setup(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817c1de0)
Location: drivers/base/cacheinfo.c:218
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff817c1de0-ffffffff817c1f2f: cache_shared_cpu_map_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cache_shared_cpu_map_setup(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817d7000)
Location: drivers/base/cacheinfo.c:218
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff817d7000-ffffffff817d714f: cache_shared_cpu_map_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cache_shared_cpu_map_setup(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817baa50)
Location: drivers/base/cacheinfo.c:218
Inline: False
```
**Symbols:**

```
ffffffff817baa50-ffffffff817babb0: cache_shared_cpu_map_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cache_shared_cpu_map_setup(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:218
Inline: False
```
**Symbols:**

```
ffffffff81844930-ffffffff81844b2a: cache_shared_cpu_map_setup (STB_LOCAL)
ffffffff81d033a7-ffffffff81d033bc: cache_shared_cpu_map_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cache_shared_cpu_map_setup(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:218
Inline: False
```
**Symbols:**

```
ffffffff81988b10-ffffffff81988d1c: cache_shared_cpu_map_setup (STB_LOCAL)
ffffffff81ecbaea-ffffffff81ecbaff: cache_shared_cpu_map_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cache_shared_cpu_map_setup(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:255
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff81af7a60-ffffffff81af7e52: cache_shared_cpu_map_setup (STB_LOCAL)
ffffffff8209875f-ffffffff82098783: cache_shared_cpu_map_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cache_shared_cpu_map_setup(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:357
Inline: False
```
**Symbols:**

```
ffffffff81b45de0-ffffffff81b461ea: cache_shared_cpu_map_setup (STB_LOCAL)
ffffffff8211974b-ffffffff8211975f: cache_shared_cpu_map_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cache_shared_cpu_map_setup(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:360
Inline: False
```
**Symbols:**

```
ffffffff81b9e000-ffffffff81b9e40a: cache_shared_cpu_map_setup (STB_LOCAL)
ffffffff821f770d-ffffffff821f7721: cache_shared_cpu_map_setup.cold (STB_LOCAL)
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
In drivers/base/cacheinfo.c (ffff8000108f4628)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (c09e0b58)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (c00000000098e660)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (ffffffe000585bca)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (ffffffff816cc89a)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (ffffffff816a7bca)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (ffffffff816fae0a)
Location: drivers/base/cacheinfo.c:218
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
In drivers/base/cacheinfo.c (ffffffff817156aa)
Location: drivers/base/cacheinfo.c:218
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
