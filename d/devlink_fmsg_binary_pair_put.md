# Function: <code>devlink_fmsg_binary_pair_put</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194fb30)
Location: net/core/devlink.c:4370
Inline: True
```
**Symbols:**

```
ffffffff8194fb30-ffffffff8194fb81: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81987d10)
Location: net/core/devlink.c:4424
Inline: True
```
**Symbols:**

```
ffffffff81987d10-ffffffff81987d61: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u32 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a55c90)
Location: net/core/devlink.c:4928
Inline: True
```
**Symbols:**

```
ffffffff81a55c90-ffffffff81a55d59: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u32 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d070)
Location: net/core/devlink.c:5617
Inline: True
```
**Symbols:**

```
ffffffff81a5d070-ffffffff81a5d135: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u32 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3e660)
Location: net/core/devlink.c:5820
Inline: True
```
**Symbols:**

```
ffffffff81a3e660-ffffffff81a3e76b: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u32 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6433
Inline: True
```
**Symbols:**

```
ffffffff81d38641-ffffffff81d38670: devlink_fmsg_binary_pair_put.cold (STB_LOCAL)
ffffffff81af4bd0-ffffffff81af4cc0: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u32 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81c78efd)
Location: net/core/devlink.c:6925
Inline: True
```
**Symbols:**

```
ffffffff81f04ff3-ffffffff81f0502a: devlink_fmsg_binary_pair_put.cold (STB_LOCAL)
ffffffff81c78ed0-ffffffff81c78fd7: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u32 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81e31dfd)
Location: net/core/devlink.c:7480
Inline: True
```
**Symbols:**

```
ffffffff820acff1-ffffffff820ad028: devlink_fmsg_binary_pair_put.cold (STB_LOCAL)
ffffffff81e31dd0-ffffffff81e31ed7: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u32 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff8204670d)
Location: net/devlink/health.c:997
Inline: True
```
**Symbols:**

```
ffffffff82136792-ffffffff821367c9: devlink_fmsg_binary_pair_put.cold (STB_LOCAL)
ffffffff820466e0-ffffffff820467e7: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u32 value_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:911
Inline: False
```
**Symbols:**

```
ffffffff822185f0-ffffffff8221864e: devlink_fmsg_binary_pair_put.cold (STB_LOCAL)
ffffffff82112e50-ffffffff82112f9a: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffff800010c25c08)
Location: net/core/devlink.c:4424
Inline: True
```
**Symbols:**

```
ffff800010c24be8-ffff800010c24c18: devlink_fmsg_binary_pair_put.part.0 (STB_LOCAL)
ffff800010c25c08-ffff800010c25c80: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (c0d444c4)
Location: net/core/devlink.c:4424
Inline: True
```
**Symbols:**

```
c0d3bf88-c0d3bfa8: devlink_fmsg_binary_pair_put.part.0 (STB_LOCAL)
c0d444c4-c0d44518: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d261b0)
Location: net/core/devlink.c:4424
Inline: True
```
**Symbols:**

```
c000000000d261b0-c000000000d2624c: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffe00079f546)
Location: net/core/devlink.c:4424
Inline: True
```
**Symbols:**

```
ffffffe00079cd98-ffffffe00079cdc6: devlink_fmsg_binary_pair_put.part.0 (STB_LOCAL)
ffffffe00079f546-ffffffe00079f5b2: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81927b80)
Location: net/core/devlink.c:4424
Inline: True
```
**Symbols:**

```
ffffffff81927b80-ffffffff81927bd1: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e1930)
Location: net/core/devlink.c:4424
Inline: True
```
**Symbols:**

```
ffffffff818e1930-ffffffff818e1981: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81978d10)
Location: net/core/devlink.c:4424
Inline: True
```
**Symbols:**

```
ffffffff81978d10-ffffffff81978d61: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_put(struct devlink_fmsg *fmsg, const char *name, const void *value, u16 value_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199b200)
Location: net/core/devlink.c:4424
Inline: True
```
**Symbols:**

```
ffffffff8199b200-ffffffff8199b251: devlink_fmsg_binary_pair_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u16 value_len</code> ➡️ <code>u32 value_len</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
