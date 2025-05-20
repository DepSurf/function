# Function: <code>cpu_cache_sysfs_init</code>

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
In drivers/base/cacheinfo.c (ffffffff81552755)
Location: drivers/base/cacheinfo.c:442
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
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
In drivers/base/cacheinfo.c (ffffffff815a46fc)
Location: drivers/base/cacheinfo.c:442
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
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
Location: drivers/base/cacheinfo.c:577
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
Location: drivers/base/cacheinfo.c:577
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
Location: drivers/base/cacheinfo.c:590
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
In drivers/base/cacheinfo.c (ffffffff8168a5ac)
Location: drivers/base/cacheinfo.c:580
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
In drivers/base/cacheinfo.c (ffffffff816a9aac)
Location: drivers/base/cacheinfo.c:574
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
In drivers/base/cacheinfo.c (ffffffff816e30c6)
Location: drivers/base/cacheinfo.c:579
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
In drivers/base/cacheinfo.c (ffffffff81707276)
Location: drivers/base/cacheinfo.c:579
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpu_cache_sysfs_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817c1a30)
Location: drivers/base/cacheinfo.c:579
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cache_add_dev
```
**Symbols:**

```
ffffffff817c1a30-ffffffff817c1ae9: cpu_cache_sysfs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpu_cache_sysfs_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817d6c50)
Location: drivers/base/cacheinfo.c:586
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cache_add_dev
```
**Symbols:**

```
ffffffff817d6c50-ffffffff817d6d09: cpu_cache_sysfs_init (STB_LOCAL)
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
In drivers/base/cacheinfo.c (ffffffff817bac15)
Location: drivers/base/cacheinfo.c:586
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
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
In drivers/base/cacheinfo.c (ffffffff81844ba6)
Location: drivers/base/cacheinfo.c:587
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
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
In drivers/base/cacheinfo.c (ffffffff81988dbf)
Location: drivers/base/cacheinfo.c:587
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81af8125)
Location: drivers/base/cacheinfo.c:639
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
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
In drivers/base/cacheinfo.c (ffffffff81b46655)
Location: drivers/base/cacheinfo.c:841
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
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
In drivers/base/cacheinfo.c (ffffffff81b9e995)
Location: drivers/base/cacheinfo.c:848
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
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
In drivers/base/cacheinfo.c (ffff8000108f47fc)
Location: drivers/base/cacheinfo.c:579
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
In drivers/base/cacheinfo.c (c09e0e9c)
Location: drivers/base/cacheinfo.c:579
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
In drivers/base/cacheinfo.c (c00000000098ea54)
Location: drivers/base/cacheinfo.c:579
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
Location: drivers/base/cacheinfo.c:579
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
In drivers/base/cacheinfo.c (ffffffff816cc9c6)
Location: drivers/base/cacheinfo.c:579
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
In drivers/base/cacheinfo.c (ffffffff816a7cf6)
Location: drivers/base/cacheinfo.c:579
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
In drivers/base/cacheinfo.c (ffffffff816faf36)
Location: drivers/base/cacheinfo.c:579
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
In drivers/base/cacheinfo.c (ffffffff817157d6)
Location: drivers/base/cacheinfo.c:579
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
</ul>
