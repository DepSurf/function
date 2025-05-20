# Function: <code>devlink_fmsg_u64_put</code>

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
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194f2d0)
Location: net/core/devlink.c:4245
Inline: True
```
**Symbols:**

```
ffffffff8194f2d0-ffffffff8194f2f6: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81986040)
Location: net/core/devlink.c:4299
Inline: True
```
**Symbols:**

```
ffffffff81986040-ffffffff81986066: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a559f0)
Location: net/core/devlink.c:4794
Inline: True
```
**Symbols:**

```
ffffffff81a559f0-ffffffff81a55a61: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ce50)
Location: net/core/devlink.c:5483
Inline: True
```
**Symbols:**

```
ffffffff81a5ce50-ffffffff81a5cec1: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3ddc0)
Location: net/core/devlink.c:5686
Inline: True
```
**Symbols:**

```
ffffffff81a3ddc0-ffffffff81a3ddf3: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81af4eea)
Location: net/core/devlink.c:6299
Inline: True
```
**Symbols:**

```
ffffffff81d385ad-ffffffff81d385c1: devlink_fmsg_u64_put.cold (STB_LOCAL)
ffffffff81af4340-ffffffff81af438f: devlink_fmsg_u64_put (STB_GLOBAL)
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
In net/core/devlink.c (ffffffff81c79266)
Location: net/core/devlink.c:6792
Inline: True
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
In net/core/devlink.c (ffffffff81e321b6)
Location: net/core/devlink.c:7347
Inline: True
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
In net/devlink/health.c (ffffffff82046b56)
Location: net/devlink/health.c:864
Inline: True
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
In net/devlink/health.c (ffffffff82112b11)
Location: net/devlink/health.c:843
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
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
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c25868)
Location: net/core/devlink.c:4299
Inline: True
```
**Symbols:**

```
ffff800010c25868-ffff800010c258a4: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d40824)
Location: net/core/devlink.c:4299
Inline: True
```
**Symbols:**

```
c0d40824-c0d40858: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25db0)
Location: net/core/devlink.c:4299
Inline: True
```
**Symbols:**

```
c000000000d25db0-c000000000d25df0: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079f32c)
Location: net/core/devlink.c:4299
Inline: True
```
**Symbols:**

```
ffffffe00079f32c-ffffffe00079f362: devlink_fmsg_u64_put (STB_GLOBAL)
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
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925eb0)
Location: net/core/devlink.c:4299
Inline: True
```
**Symbols:**

```
ffffffff81925eb0-ffffffff81925ed6: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dfc60)
Location: net/core/devlink.c:4299
Inline: True
```
**Symbols:**

```
ffffffff818dfc60-ffffffff818dfc86: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81977040)
Location: net/core/devlink.c:4299
Inline: True
```
**Symbols:**

```
ffffffff81977040-ffffffff81977066: devlink_fmsg_u64_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_put(struct devlink_fmsg *fmsg, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81999530)
Location: net/core/devlink.c:4299
Inline: True
```
**Symbols:**

```
ffffffff81999530-ffffffff81999556: devlink_fmsg_u64_put (STB_GLOBAL)
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
