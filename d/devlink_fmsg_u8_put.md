# Function: <code>devlink_fmsg_u8_put</code>

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
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194f270)
Location: net/core/devlink.c:4233
Inline: True
```
**Symbols:**

```
ffffffff8194f270-ffffffff8194f296: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81985fe0)
Location: net/core/devlink.c:4287
Inline: True
```
**Symbols:**

```
ffffffff81985fe0-ffffffff81986006: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a55a70)
Location: net/core/devlink.c:4776
Inline: True
```
**Symbols:**

```
ffffffff81a55a70-ffffffff81a55ae1: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5cdd0)
Location: net/core/devlink.c:5465
Inline: True
```
**Symbols:**

```
ffffffff81a5cdd0-ffffffff81a5ce41: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3dd40)
Location: net/core/devlink.c:5668
Inline: True
```
**Symbols:**

```
ffffffff81a3dd40-ffffffff81a3dd73: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81af4da8)
Location: net/core/devlink.c:6281
Inline: True
```
**Symbols:**

```
ffffffff81d38585-ffffffff81d38599: devlink_fmsg_u8_put.cold (STB_LOCAL)
ffffffff81af42a0-ffffffff81af42ef: devlink_fmsg_u8_put (STB_GLOBAL)
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
In net/core/devlink.c (ffffffff81c791c6)
Location: net/core/devlink.c:6775
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
In net/core/devlink.c (ffffffff81e32106)
Location: net/core/devlink.c:7330
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
In net/devlink/health.c (ffffffff82046aa6)
Location: net/devlink/health.c:847
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
In net/devlink/health.c (ffffffff82112a31)
Location: net/devlink/health.c:830
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
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
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c257e8)
Location: net/core/devlink.c:4287
Inline: True
```
**Symbols:**

```
ffff800010c257e8-ffff800010c25824: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d407b8)
Location: net/core/devlink.c:4287
Inline: True
```
**Symbols:**

```
c0d407b8-c0d407f0: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25d10)
Location: net/core/devlink.c:4287
Inline: True
```
**Symbols:**

```
c000000000d25d10-c000000000d25d54: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079f2c0)
Location: net/core/devlink.c:4287
Inline: True
```
**Symbols:**

```
ffffffe00079f2c0-ffffffe00079f2f6: devlink_fmsg_u8_put (STB_GLOBAL)
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
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925e50)
Location: net/core/devlink.c:4287
Inline: True
```
**Symbols:**

```
ffffffff81925e50-ffffffff81925e76: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dfc00)
Location: net/core/devlink.c:4287
Inline: True
```
**Symbols:**

```
ffffffff818dfc00-ffffffff818dfc26: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81976fe0)
Location: net/core/devlink.c:4287
Inline: True
```
**Symbols:**

```
ffffffff81976fe0-ffffffff81977006: devlink_fmsg_u8_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_put(struct devlink_fmsg *fmsg, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819994d0)
Location: net/core/devlink.c:4287
Inline: True
```
**Symbols:**

```
ffffffff819994d0-ffffffff819994f6: devlink_fmsg_u8_put (STB_GLOBAL)
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
