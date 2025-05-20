# Function: <code>find_pers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168f460)
Location: drivers/md/md.c:670
Inline: False
Direct callers:
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8168f460-ffffffff8168f4cd: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f0270)
Location: drivers/md/md.c:665
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff816f0270-ffffffff816f02dd: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81721b10)
Location: drivers/md/md.c:678
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81721b10-ffffffff81721b7d: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81739250)
Location: drivers/md/md.c:690
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81739250-ffffffff817392bd: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817abcc0)
Location: drivers/md/md.c:725
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff817abcc0-ffffffff817abd2d: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f2830)
Location: drivers/md/md.c:737
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff817f2830-ffffffff817f289d: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8181e730)
Location: drivers/md/md.c:730
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8181e730-ffffffff8181e79d: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81860c00)
Location: drivers/md/md.c:791
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81860c00-ffffffff81860c6f: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81892830)
Location: drivers/md/md.c:803
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81892830-ffffffff8189289f: find_pers (STB_LOCAL)
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
In drivers/md/md.c (ffffffff8196d242)
Location: drivers/md/md.c:929
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
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
In drivers/md/md.c (ffffffff819740c2)
Location: drivers/md/md.c:917
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
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
In drivers/md/md.c (ffffffff819580f4)
Location: drivers/md/md.c:876
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
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
In drivers/md/md.c (ffffffff819fd874)
Location: drivers/md/md.c:877
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
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
In drivers/md/md.c (ffffffff81b64eef)
Location: drivers/md/md.c:882
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
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
In drivers/md/md.c (ffffffff81cfffe9)
Location: drivers/md/md.c:871
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
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
In drivers/md/md.c (ffffffff81d63206)
Location: drivers/md/md.c:847
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
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
In drivers/md/md.c (ffffffff81e1a0f4)
Location: drivers/md/md.c:958
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
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
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae3fe0)
Location: drivers/md/md.c:803
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffff800010ae3fe0-ffff800010ae4098: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc691c)
Location: drivers/md/md.c:803
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
c0bc691c-c0bc69a8: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bcdea0)
Location: drivers/md/md.c:803
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
c000000000bcdea0-c000000000bce108: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006db09e)
Location: drivers/md/md.c:803
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffe0006db09e-ffffffe0006db11a: find_pers (STB_LOCAL)
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
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818386b0)
Location: drivers/md/md.c:803
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff818386b0-ffffffff8183871f: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817ffd20)
Location: drivers/md/md.c:803
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff817ffd20-ffffffff817ffd8f: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81887ce0)
Location: drivers/md/md.c:803
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81887ce0-ffffffff81887d4f: find_pers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct md_personality *find_pers(int level, char *clevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a4010)
Location: drivers/md/md.c:803
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff818a4010-ffffffff818a407f: find_pers (STB_LOCAL)
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
