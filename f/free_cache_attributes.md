# Function: <code>free_cache_attributes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81552450)
Location: drivers/base/cacheinfo.c:164
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
```
**Symbols:**

```
ffffffff81552450-ffffffff81552551: free_cache_attributes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815a43f0)
Location: drivers/base/cacheinfo.c:164
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff815a43f0-ffffffff815a44f7: free_cache_attributes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815d29f0)
Location: drivers/base/cacheinfo.c:293
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff815d29f0-ffffffff815d2b15: free_cache_attributes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815e76ac)
Location: drivers/base/cacheinfo.c:293
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff815e7580-ffffffff815e7686: free_cache_attributes.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff8164ea5c)
Location: drivers/base/cacheinfo.c:306
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff8164e950-ffffffff8164ea3e: free_cache_attributes.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff8168a1bc)
Location: drivers/base/cacheinfo.c:292
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff8168a0b0-ffffffff8168a19c: free_cache_attributes.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816a96bc)
Location: drivers/base/cacheinfo.c:286
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff816a95b0-ffffffff816a969c: free_cache_attributes.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816e2ccb)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff816e2bb0-ffffffff816e2caa: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81706e7b)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff81706d60-ffffffff81706e5a: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817c1bc0)
Location: drivers/base/cacheinfo.c:291
Inline: True
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff817c1bc0-ffffffff817c1c10: free_cache_attributes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817d6de0)
Location: drivers/base/cacheinfo.c:291
Inline: True
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff817d6de0-ffffffff817d6e30: free_cache_attributes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_cache_attributes(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817ba800)
Location: drivers/base/cacheinfo.c:291
Inline: True
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff817ba800-ffffffff817ba850: free_cache_attributes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff818446ee)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff81844620-ffffffff818446d0: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff819888cf)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff819887f0-ffffffff819888aa: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81af76af)
Location: drivers/base/cacheinfo.c:330
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
  - drivers/base/cacheinfo.c:detect_cache_attributes
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff81af7440-ffffffff81af74fa: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b458ef)
Location: drivers/base/cacheinfo.c:458
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b9dd9f)
Location: drivers/base/cacheinfo.c:461
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffff8000108f440c)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffff8000108f4228-ffff8000108f43c0: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (c09e0998)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
c09e0838-c09e096c: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (c00000000098e3f0)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
c00000000098e150-c00000000098e388: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffe000585a02)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffe00058581e-ffffffe0005859b8: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816cc5cb)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff816cc4b0-ffffffff816cc5aa: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816a78fb)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff816a77e0-ffffffff816a78da: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816fab3b)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff816faa20-ffffffff816fab1a: free_cache_attributes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817153db)
Location: drivers/base/cacheinfo.c:291
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
**Symbols:**

```
ffffffff817152c0-ffffffff817153ba: free_cache_attributes.part.0 (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
