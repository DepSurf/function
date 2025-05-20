# Function: <code>__cpufreq_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816af280)
Location: drivers/cpufreq/cpufreq.c:1493
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff816af280-ffffffff816af321: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81710c60)
Location: drivers/cpufreq/cpufreq.c:1522
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81710c60-ffffffff81710cfe: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817448d0)
Location: drivers/cpufreq/cpufreq.c:1491
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff817448d0-ffffffff81744970: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81762f60)
Location: drivers/cpufreq/cpufreq.c:1494
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81762f60-ffffffff81763000: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d8f00)
Location: drivers/cpufreq/cpufreq.c:1526
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff817d8f00-ffffffff817d8fa3: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81821b10)
Location: drivers/cpufreq/cpufreq.c:1524
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81821b10-ffffffff81821bb3: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184d9c0)
Location: drivers/cpufreq/cpufreq.c:1529
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff8184d9c0-ffffffff8184da5c: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81890a90)
Location: drivers/cpufreq/cpufreq.c:1717
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81890a90-ffffffff81890ace: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c2b70)
Location: drivers/cpufreq/cpufreq.c:1731
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff818c2b70-ffffffff818c2bae: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81994f4b)
Location: drivers/cpufreq/cpufreq.c:1768
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8199821b)
Location: drivers/cpufreq/cpufreq.c:1773
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
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
In drivers/cpufreq/cpufreq.c (ffffffff8197cd0b)
Location: drivers/cpufreq/cpufreq.c:1779
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
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
In drivers/cpufreq/cpufreq.c (ffffffff81a258cb)
Location: drivers/cpufreq/cpufreq.c:1785
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
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
In drivers/cpufreq/cpufreq.c (ffffffff81b8f35b)
Location: drivers/cpufreq/cpufreq.c:1817
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
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
In drivers/cpufreq/cpufreq.c (ffffffff81d2f6bb)
Location: drivers/cpufreq/cpufreq.c:1814
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
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
In drivers/cpufreq/cpufreq.c (ffffffff81d9896b)
Location: drivers/cpufreq/cpufreq.c:1821
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
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
In drivers/cpufreq/cpufreq.c (ffffffff81e505eb)
Location: drivers/cpufreq/cpufreq.c:1862
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
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
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1ec78)
Location: drivers/cpufreq/cpufreq.c:1731
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffff800010b1ec78-ffff800010b1ecd0: __cpufreq_get (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (c0bf9230)
Location: drivers/cpufreq/cpufreq.c:1731
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:show_cpuinfo_cur_freq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c11790)
Location: drivers/cpufreq/cpufreq.c:1731
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
c000000000c11790-c000000000c11808: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81867290)
Location: drivers/cpufreq/cpufreq.c:1731
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff81867290-ffffffff818672ce: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182ff40)
Location: drivers/cpufreq/cpufreq.c:1731
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff8182ff40-ffffffff8182ff7e: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b8020)
Location: drivers/cpufreq/cpufreq.c:1731
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff818b8020-ffffffff818b805e: __cpufreq_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int __cpufreq_get(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d42e0)
Location: drivers/cpufreq/cpufreq.c:1731
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get
```
**Symbols:**

```
ffffffff818d42e0-ffffffff818d431e: __cpufreq_get (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
