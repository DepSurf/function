# Function: <code>cache_add_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81552740)
Location: drivers/base/cacheinfo.c:466
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
```
**Symbols:**

```
ffffffff81552740-ffffffff81552930: cache_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815a46e0)
Location: drivers/base/cacheinfo.c:466
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
```
**Symbols:**

```
ffffffff815a46e0-ffffffff815a48c6: cache_add_dev (STB_LOCAL)
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
In drivers/base/cacheinfo.c (ffffffff815d2ef9)
Location: drivers/base/cacheinfo.c:601
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
In drivers/base/cacheinfo.c (ffffffff815e7a68)
Location: drivers/base/cacheinfo.c:601
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
In drivers/base/cacheinfo.c (ffffffff8164ee0d)
Location: drivers/base/cacheinfo.c:614
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
In drivers/base/cacheinfo.c (ffffffff8168a59e)
Location: drivers/base/cacheinfo.c:604
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
In drivers/base/cacheinfo.c (ffffffff816a9a9e)
Location: drivers/base/cacheinfo.c:598
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
In drivers/base/cacheinfo.c (ffffffff816e30b5)
Location: drivers/base/cacheinfo.c:603
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
In drivers/base/cacheinfo.c (ffffffff81707265)
Location: drivers/base/cacheinfo.c:603
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817c2020)
Location: drivers/base/cacheinfo.c:603
Inline: False
```
**Symbols:**

```
ffffffff817c2020-ffffffff817c2178: cache_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817d7240)
Location: drivers/base/cacheinfo.c:610
Inline: False
```
**Symbols:**

```
ffffffff817d7240-ffffffff817d7398: cache_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817babe0)
Location: drivers/base/cacheinfo.c:610
Inline: False
```
**Symbols:**

```
ffffffff817babe0-ffffffff817baddd: cache_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:611
Inline: False
```
**Symbols:**

```
ffffffff81844b60-ffffffff81844f60: cache_add_dev (STB_LOCAL)
ffffffff81d033bc-ffffffff81d033df: cache_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:611
Inline: False
```
**Symbols:**

```
ffffffff81988d80-ffffffff81989184: cache_add_dev (STB_LOCAL)
ffffffff81ecbaff-ffffffff81ecbb22: cache_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:663
Inline: False
```
**Symbols:**

```
ffffffff81af8120-ffffffff81af84f2: cache_add_dev (STB_LOCAL)
ffffffff82098783-ffffffff8209879e: cache_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:865
Inline: False
```
**Symbols:**

```
ffffffff81b46650-ffffffff81b46a27: cache_add_dev (STB_LOCAL)
ffffffff8211977a-ffffffff82119795: cache_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cache_add_dev(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (0)
Location: drivers/base/cacheinfo.c:872
Inline: False
```
**Symbols:**

```
ffffffff81b9e990-ffffffff81b9ed67: cache_add_dev (STB_LOCAL)
ffffffff821f773c-ffffffff821f7757: cache_add_dev.cold (STB_LOCAL)
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
In drivers/base/cacheinfo.c (ffff8000108f47f0)
Location: drivers/base/cacheinfo.c:603
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
In drivers/base/cacheinfo.c (c09e0e84)
Location: drivers/base/cacheinfo.c:603
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
In drivers/base/cacheinfo.c (c00000000098ea48)
Location: drivers/base/cacheinfo.c:603
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
In drivers/base/cacheinfo.c (ffffffe000585ea4)
Location: drivers/base/cacheinfo.c:603
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
In drivers/base/cacheinfo.c (ffffffff816cc9b5)
Location: drivers/base/cacheinfo.c:603
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
In drivers/base/cacheinfo.c (ffffffff816a7ce5)
Location: drivers/base/cacheinfo.c:603
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
In drivers/base/cacheinfo.c (ffffffff816faf25)
Location: drivers/base/cacheinfo.c:603
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
In drivers/base/cacheinfo.c (ffffffff817157c5)
Location: drivers/base/cacheinfo.c:603
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
