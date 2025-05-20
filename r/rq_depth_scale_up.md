# Function: <code>rq_depth_scale_up</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814bda30)
Location: block/blk-rq-qos.c:143
Inline: False
Direct callers:
  - block/blk-wbt.c:scale_up
```
**Symbols:**

```
ffffffff814bda30-ffffffff814bda53: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814ec0d0)
Location: block/blk-rq-qos.c:145
Inline: False
Direct callers:
  - block/blk-wbt.c:scale_up
```
**Symbols:**

```
ffffffff814ec0d0-ffffffff814ec0f3: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81505510)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff81505510-ffffffff8150553a: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81565de0)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff81565de0-ffffffff81565e72: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81580d60)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff81580d60-ffffffff81580df2: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff815888c0)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff815888c0-ffffffff81588956: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff81cd9afd-ffffffff81cd9b34: rq_depth_scale_up.cold (STB_LOCAL)
ffffffff815ee590-ffffffff815ee650: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff81e8d592-ffffffff81e8d5c9: rq_depth_scale_up.cold (STB_LOCAL)
ffffffff8169ee20-ffffffff8169eefa: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:158
Inline: False
```
**Symbols:**

```
ffffffff82076bb1-ffffffff82076be8: rq_depth_scale_up.cold (STB_LOCAL)
ffffffff8175d6c0-ffffffff8175d79a: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:158
Inline: False
```
**Symbols:**

```
ffffffff820f69cf-ffffffff820f6a06: rq_depth_scale_up.cold (STB_LOCAL)
ffffffff8179c420-ffffffff8179c500: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:158
Inline: False
```
**Symbols:**

```
ffffffff821d3e1d-ffffffff821d3e54: rq_depth_scale_up.cold (STB_LOCAL)
ffffffff817dfe80-ffffffff817dff60: rq_depth_scale_up (STB_GLOBAL)
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
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffff800010607628)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffff800010607628-ffff800010607684: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c07b2814)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
c07b2814-c07b2860: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c0000000007a41d0)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
c0000000007a41d0-c0000000007a4244: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffe000442210)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffe000442210-ffffffe00044224e: rq_depth_scale_up (STB_GLOBAL)
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
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814fdaf0)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff814fdaf0-ffffffff814fdb1a: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814ee000)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff814ee000-ffffffff814ee02a: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814f9b80)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff814f9b80-ffffffff814f9baa: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rq_depth_scale_up(struct rq_depth *rqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81512be0)
Location: block/blk-rq-qos.c:164
Inline: False
```
**Symbols:**

```
ffffffff81512be0-ffffffff81512c0a: rq_depth_scale_up (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
