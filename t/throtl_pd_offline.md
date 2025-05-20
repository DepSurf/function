# Function: <code>throtl_pd_offline</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8144b3b0)
Location: block/blk-throttle.c:595
Inline: False
```
**Symbols:**

```
ffffffff8144b3b0-ffffffff8144b417: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81477b60)
Location: block/blk-throttle.c:593
Inline: False
```
**Symbols:**

```
ffffffff81477b60-ffffffff81477bc7: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814ac1e0)
Location: block/blk-throttle.c:591
Inline: False
```
**Symbols:**

```
ffffffff814ac1e0-ffffffff814ac24a: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814c65a0)
Location: block/blk-throttle.c:592
Inline: False
```
**Symbols:**

```
ffffffff814c65a0-ffffffff814c660a: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f4e00)
Location: block/blk-throttle.c:592
Inline: False
```
**Symbols:**

```
ffffffff814f4e00-ffffffff814f4e6a: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8150e440)
Location: block/blk-throttle.c:594
Inline: False
```
**Symbols:**

```
ffffffff8150e440-ffffffff8150e4aa: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156ef00)
Location: block/blk-throttle.c:610
Inline: False
```
**Symbols:**

```
ffffffff8156ef00-ffffffff8156ef65: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81589cc0)
Location: block/blk-throttle.c:618
Inline: False
```
**Symbols:**

```
ffffffff81589cc0-ffffffff81589d0f: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815906c0)
Location: block/blk-throttle.c:618
Inline: False
```
**Symbols:**

```
ffffffff815906c0-ffffffff8159070f: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:621
Inline: False
```
**Symbols:**

```
ffffffff815f7680-ffffffff815f770d: throtl_pd_offline (STB_LOCAL)
ffffffff81cd9cba-ffffffff81cd9ccf: throtl_pd_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff816aa4b4)
Location: block/blk-throttle.c:481
Inline: True
```
**Symbols:**

```
ffffffff816aa440-ffffffff816aa4dd: throtl_pd_offline (STB_LOCAL)
ffffffff81e8d7e5-ffffffff81e8d7fa: throtl_pd_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:475
Inline: False
```
**Symbols:**

```
ffffffff817655d0-ffffffff81765649: throtl_pd_offline (STB_LOCAL)
ffffffff82076cb9-ffffffff82076ccd: throtl_pd_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:474
Inline: False
```
**Symbols:**

```
ffffffff817a4690-ffffffff817a4709: throtl_pd_offline (STB_LOCAL)
ffffffff820f6b3c-ffffffff820f6b50: throtl_pd_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:474
Inline: False
```
**Symbols:**

```
ffffffff817e8260-ffffffff817e82d9: throtl_pd_offline (STB_LOCAL)
ffffffff821d3f8a-ffffffff821d3f9e: throtl_pd_offline.cold (STB_LOCAL)
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
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffff800010612080)
Location: block/blk-throttle.c:594
Inline: False
```
**Symbols:**

```
ffff800010612080-ffff8000106120e8: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07bc880)
Location: block/blk-throttle.c:594
Inline: False
```
**Symbols:**

```
c07bc880-c07bc8dc: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c0000000007b0310)
Location: block/blk-throttle.c:594
Inline: False
```
**Symbols:**

```
c0000000007b0310-c0000000007b03a4: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffe000449816)
Location: block/blk-throttle.c:594
Inline: False
```
**Symbols:**

```
ffffffe000449816-ffffffe000449878: throtl_pd_offline (STB_LOCAL)
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
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81506a20)
Location: block/blk-throttle.c:594
Inline: False
```
**Symbols:**

```
ffffffff81506a20-ffffffff81506a8a: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f6ee0)
Location: block/blk-throttle.c:594
Inline: False
```
**Symbols:**

```
ffffffff814f6ee0-ffffffff814f6f4a: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81502ab0)
Location: block/blk-throttle.c:594
Inline: False
```
**Symbols:**

```
ffffffff81502ab0-ffffffff81502b1a: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void throtl_pd_offline(struct blkg_policy_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8151bef0)
Location: block/blk-throttle.c:594
Inline: False
```
**Symbols:**

```
ffffffff8151bef0-ffffffff8151bf5a: throtl_pd_offline (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
