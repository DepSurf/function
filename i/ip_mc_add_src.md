# Function: <code>ip_mc_add_src</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81796940)
Location: net/ipv4/igmp.c:1955
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
```
**Symbols:**

```
ffffffff81796940-ffffffff81796c18: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81803eb0)
Location: net/ipv4/igmp.c:1965
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_inc_group
```
**Symbols:**

```
ffffffff81803eb0-ffffffff81804182: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81834e30)
Location: net/ipv4/igmp.c:2003
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_inc_group
```
**Symbols:**

```
ffffffff81834e30-ffffffff81835102: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81856360)
Location: net/ipv4/igmp.c:2012
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_inc_group
```
**Symbols:**

```
ffffffff81856360-ffffffff8185664f: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d6220)
Location: net/ipv4/igmp.c:2038
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_inc_group
```
**Symbols:**

```
ffffffff818d6220-ffffffff818d650c: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192cb60)
Location: net/ipv4/igmp.c:2049
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
**Symbols:**

```
ffffffff8192cb60-ffffffff8192ce42: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195ba70)
Location: net/ipv4/igmp.c:2065
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
**Symbols:**

```
ffffffff8195ba70-ffffffff8195bd52: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c0750)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff819c0750-ffffffff819c0a3e: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f72f0)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff819f72f0-ffffffff819f75de: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae72a0)
Location: net/ipv4/igmp.c:2065
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81ae72a0-ffffffff81ae7558: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af4170)
Location: net/ipv4/igmp.c:2065
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81af4170-ffffffff81af4432: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81adf7b0)
Location: net/ipv4/igmp.c:2073
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81adf7b0-ffffffff81adfa72: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81b9ec90)
Location: net/ipv4/igmp.c:2073
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81b9ec90-ffffffff81b9eff2: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d31050)
Location: net/ipv4/igmp.c:2080
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81d31050-ffffffff81d313bb: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef9810)
Location: net/ipv4/igmp.c:2080
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81ef9810-ffffffff81ef9b7b: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f592b0)
Location: net/ipv4/igmp.c:2081
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81f592b0-ffffffff81f5961b: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201f770)
Location: net/ipv4/igmp.c:2083
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff8201f770-ffffffff8201faec: ip_mc_add_src (STB_LOCAL)
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
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010caf670)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffff800010caf670-ffff800010caf9b4: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dba0bc)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
c0dba0bc-c0dba338: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc6e10)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
c000000000dc6e10-c000000000dc71b0: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe000807704)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffe000807704-ffffffe00080791c: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81997090)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81997090-ffffffff8199737e: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81950b50)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81950b50-ffffffff81950e3e: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a01930)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81a01930-ffffffff81a01c1e: ip_mc_add_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_mc_add_src(struct in_device *in_dev, __be32 *pmca, int sfmode, int sfcount, __be32 *psfsrc, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0be40)
Location: net/ipv4/igmp.c:2067
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
**Symbols:**

```
ffffffff81a0be40-ffffffff81a0c145: ip_mc_add_src (STB_LOCAL)
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
