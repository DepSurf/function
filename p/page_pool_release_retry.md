# Function: <code>page_pool_release_retry</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (ffffffff81967870)
Location: net/core/page_pool.c:383
Inline: True
```
**Symbols:**

```
ffffffff81967840-ffffffff8196788d: page_pool_release_retry (STB_LOCAL)
ffffffff81967ad8-ffffffff81967b1b: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:479
Inline: False
```
**Symbols:**

```
ffffffff81a3adc0-ffffffff81a3ae0f: page_pool_release_retry (STB_LOCAL)
ffffffff81a3b33b-ffffffff81a3b37e: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:529
Inline: False
```
**Symbols:**

```
ffffffff81a3d1e0-ffffffff81a3d22f: page_pool_release_retry (STB_LOCAL)
ffffffff81c317f3-ffffffff81c31836: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:562
Inline: False
```
**Symbols:**

```
ffffffff81a24000-ffffffff81a2404f: page_pool_release_retry (STB_LOCAL)
ffffffff81c23ad6-ffffffff81c23b19: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:671
Inline: False
```
**Symbols:**

```
ffffffff81ad85d0-ffffffff81ad861f: page_pool_release_retry (STB_LOCAL)
ffffffff81d3787f-ffffffff81d378c2: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:808
Inline: False
```
**Symbols:**

```
ffffffff81c59490-ffffffff81c594f6: page_pool_release_retry (STB_LOCAL)
ffffffff81f0423c-ffffffff81f0427b: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e0f420)
Location: net/core/page_pool.c:809
Inline: False
```
**Symbols:**

```
ffffffff81e0f420-ffffffff81e0f4c5: page_pool_release_retry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e82bf0)
Location: net/core/page_pool.c:835
Inline: False
```
**Symbols:**

```
ffffffff81e82bf0-ffffffff81e82c95: page_pool_release_retry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f44de0)
Location: net/core/page_pool.c:903
Inline: False
```
**Symbols:**

```
ffffffff81f44de0-ffffffff81f44eac: page_pool_release_retry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0ce18)
Location: net/core/page_pool.c:383
Inline: True
```
**Symbols:**

```
ffff800010c0ce18-ffff800010c0cec4: page_pool_release_retry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d254f4)
Location: net/core/page_pool.c:383
Inline: True
```
**Symbols:**

```
c0d254f4-c0d255a4: page_pool_release_retry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf8900)
Location: net/core/page_pool.c:383
Inline: True
```
**Symbols:**

```
c000000000cf8900-c000000000cf89dc: page_pool_release_retry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe000789f00)
Location: net/core/page_pool.c:383
Inline: True
```
**Symbols:**

```
ffffffe000789f00-ffffffe000789f98: page_pool_release_retry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (ffffffff81907840)
Location: net/core/page_pool.c:383
Inline: True
```
**Symbols:**

```
ffffffff81907810-ffffffff8190785d: page_pool_release_retry (STB_LOCAL)
ffffffff81907aa8-ffffffff81907aeb: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (ffffffff818c1650)
Location: net/core/page_pool.c:383
Inline: True
```
**Symbols:**

```
ffffffff818c1620-ffffffff818c166d: page_pool_release_retry (STB_LOCAL)
ffffffff818c18b8-ffffffff818c18fb: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (ffffffff81958870)
Location: net/core/page_pool.c:383
Inline: True
```
**Symbols:**

```
ffffffff81958840-ffffffff8195888d: page_pool_release_retry (STB_LOCAL)
ffffffff81958ad8-ffffffff81958b1b: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void page_pool_release_retry(struct work_struct *wq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (ffffffff8197a9b0)
Location: net/core/page_pool.c:383
Inline: True
```
**Symbols:**

```
ffffffff8197a980-ffffffff8197a9cd: page_pool_release_retry (STB_LOCAL)
ffffffff8197ac18-ffffffff8197ac5b: page_pool_release_retry.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
