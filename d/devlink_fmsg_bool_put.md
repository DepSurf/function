# Function: <code>devlink_fmsg_bool_put</code>

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
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194f240)
Location: net/core/devlink.c:4227
Inline: True
```
**Symbols:**

```
ffffffff8194f240-ffffffff8194f266: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81985fb0)
Location: net/core/devlink.c:4281
Inline: True
```
**Symbols:**

```
ffffffff81985fb0-ffffffff81985fd6: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a55970)
Location: net/core/devlink.c:4767
Inline: True
```
**Symbols:**

```
ffffffff81a55970-ffffffff81a559e1: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ccd0)
Location: net/core/devlink.c:5456
Inline: True
```
**Symbols:**

```
ffffffff81a5ccd0-ffffffff81a5cd41: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3dd00)
Location: net/core/devlink.c:5659
Inline: True
```
**Symbols:**

```
ffffffff81a3dd00-ffffffff81a3dd33: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81af4d08)
Location: net/core/devlink.c:6272
Inline: True
```
**Symbols:**

```
ffffffff81d38571-ffffffff81d38585: devlink_fmsg_bool_put.cold (STB_LOCAL)
ffffffff81af4250-ffffffff81af429f: devlink_fmsg_bool_put (STB_GLOBAL)
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
In net/core/devlink.c (ffffffff81c79126)
Location: net/core/devlink.c:6767
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
In net/core/devlink.c (ffffffff81e32056)
Location: net/core/devlink.c:7322
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
In net/devlink/health.c (ffffffff820469f6)
Location: net/devlink/health.c:839
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
In net/devlink/health.c (ffffffff82112bf1)
Location: net/devlink/health.c:824
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
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
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c257a8)
Location: net/core/devlink.c:4281
Inline: True
```
**Symbols:**

```
ffff800010c257a8-ffff800010c257e4: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d40780)
Location: net/core/devlink.c:4281
Inline: True
```
**Symbols:**

```
c0d40780-c0d407b8: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25cc0)
Location: net/core/devlink.c:4281
Inline: True
```
**Symbols:**

```
c000000000d25cc0-c000000000d25d04: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079f28a)
Location: net/core/devlink.c:4281
Inline: True
```
**Symbols:**

```
ffffffe00079f28a-ffffffe00079f2c0: devlink_fmsg_bool_put (STB_GLOBAL)
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
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925e20)
Location: net/core/devlink.c:4281
Inline: True
```
**Symbols:**

```
ffffffff81925e20-ffffffff81925e46: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dfbd0)
Location: net/core/devlink.c:4281
Inline: True
```
**Symbols:**

```
ffffffff818dfbd0-ffffffff818dfbf6: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81976fb0)
Location: net/core/devlink.c:4281
Inline: True
```
**Symbols:**

```
ffffffff81976fb0-ffffffff81976fd6: devlink_fmsg_bool_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_bool_put(struct devlink_fmsg *fmsg, bool value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819994a0)
Location: net/core/devlink.c:4281
Inline: True
```
**Symbols:**

```
ffffffff819994a0-ffffffff819994c6: devlink_fmsg_bool_put (STB_GLOBAL)
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
