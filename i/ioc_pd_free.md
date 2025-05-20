# Function: <code>ioc_pd_free</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815113e0)
Location: block/blk-iocost.c:2028
Inline: False
```
**Symbols:**

```
ffffffff815113e0-ffffffff81511472: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815723c0)
Location: block/blk-iocost.c:2093
Inline: False
```
**Symbols:**

```
ffffffff815723c0-ffffffff8157247a: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158e670)
Location: block/blk-iocost.c:2956
Inline: False
```
**Symbols:**

```
ffffffff8158e670-ffffffff8158e79d: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815953d0)
Location: block/blk-iocost.c:2963
Inline: False
```
**Symbols:**

```
ffffffff815953d0-ffffffff815954fd: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2970
Inline: False
```
**Symbols:**

```
ffffffff815fc2f0-ffffffff815fc42a: ioc_pd_free (STB_LOCAL)
ffffffff81cd9e4d-ffffffff81cd9e68: ioc_pd_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2979
Inline: False
```
**Symbols:**

```
ffffffff816b09d0-ffffffff816b0b36: ioc_pd_free (STB_LOCAL)
ffffffff81e8d99b-ffffffff81e8d9b6: ioc_pd_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2987
Inline: False
```
**Symbols:**

```
ffffffff81770840-ffffffff8177099a: ioc_pd_free (STB_LOCAL)
ffffffff82076f11-ffffffff82076f2c: ioc_pd_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3002
Inline: False
```
**Symbols:**

```
ffffffff817af890-ffffffff817af9ea: ioc_pd_free (STB_LOCAL)
ffffffff820f6d81-ffffffff820f6d9c: ioc_pd_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3009
Inline: False
```
**Symbols:**

```
ffffffff817f36a0-ffffffff817f37fa: ioc_pd_free (STB_LOCAL)
ffffffff821d41cf-ffffffff821d41ea: ioc_pd_free.cold (STB_LOCAL)
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
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010615248)
Location: block/blk-iocost.c:2028
Inline: False
```
**Symbols:**

```
ffff800010615248-ffff800010615320: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07bf5e0)
Location: block/blk-iocost.c:2028
Inline: False
```
**Symbols:**

```
c07bf5e0-c07bf674: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b3c30)
Location: block/blk-iocost.c:2028
Inline: False
```
**Symbols:**

```
c0000000007b3c30-c0000000007b3d30: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044c920)
Location: block/blk-iocost.c:2028
Inline: False
```
**Symbols:**

```
ffffffe00044c920-ffffffe00044ca00: ioc_pd_free (STB_LOCAL)
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
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815099c0)
Location: block/blk-iocost.c:2028
Inline: False
```
**Symbols:**

```
ffffffff815099c0-ffffffff81509a52: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f9e70)
Location: block/blk-iocost.c:2028
Inline: False
```
**Symbols:**

```
ffffffff814f9e70-ffffffff814f9f02: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81505a50)
Location: block/blk-iocost.c:2028
Inline: False
```
**Symbols:**

```
ffffffff81505a50-ffffffff81505ae2: ioc_pd_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ioc_pd_free(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151eaf0)
Location: block/blk-iocost.c:2028
Inline: False
```
**Symbols:**

```
ffffffff8151eaf0-ffffffff8151eb80: ioc_pd_free (STB_LOCAL)
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
