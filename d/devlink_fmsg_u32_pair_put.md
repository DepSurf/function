# Function: <code>devlink_fmsg_u32_pair_put</code>

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
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194f9e0)
Location: net/core/devlink.c:4307
Inline: True
```
**Symbols:**

```
ffffffff8194f9e0-ffffffff8194fa56: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81987bc0)
Location: net/core/devlink.c:4361
Inline: True
```
**Symbols:**

```
ffffffff81987bc0-ffffffff81987c36: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a55e60)
Location: net/core/devlink.c:4865
Inline: True
```
**Symbols:**

```
ffffffff81a53580-ffffffff81a535dc: devlink_fmsg_u32_pair_put.part.0 (STB_LOCAL)
ffffffff81a55e60-ffffffff81a55ede: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d1c0)
Location: net/core/devlink.c:5554
Inline: True
```
**Symbols:**

```
ffffffff81a59d00-ffffffff81a59d5c: devlink_fmsg_u32_pair_put.part.0 (STB_LOCAL)
ffffffff81a5d1c0-ffffffff81a5d23e: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a3e870)
Location: net/core/devlink.c:5757
Inline: True
```
**Symbols:**

```
ffffffff81a3ccb0-ffffffff81a3cd0c: devlink_fmsg_u32_pair_put.part.0 (STB_LOCAL)
ffffffff81a3e870-ffffffff81a3e8ee: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6370
Inline: True
```
**Symbols:**

```
ffffffff81d386c0-ffffffff81d386e8: devlink_fmsg_u32_pair_put.cold (STB_LOCAL)
ffffffff81af4e00-ffffffff81af4ea0: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81c79032)
Location: net/core/devlink.c:6862
Inline: True
```
**Symbols:**

```
ffffffff81f0502a-ffffffff81f0503f: devlink_fmsg_u32_pair_put.cold (STB_LOCAL)
ffffffff81c78fe0-ffffffff81c79079: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81e31f42)
Location: net/core/devlink.c:7417
Inline: True
```
**Symbols:**

```
ffffffff820ad028-ffffffff820ad03d: devlink_fmsg_u32_pair_put.cold (STB_LOCAL)
ffffffff81e31ef0-ffffffff81e31f89: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff820468e2)
Location: net/devlink/health.c:934
Inline: True
```
**Symbols:**

```
ffffffff8213680f-ffffffff82136824: devlink_fmsg_u32_pair_put.cold (STB_LOCAL)
ffffffff82046890-ffffffff82046929: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:884
Inline: False
```
**Symbols:**

```
ffffffff82218560-ffffffff8221859c: devlink_fmsg_u32_pair_put.cold (STB_LOCAL)
ffffffff82112ca0-ffffffff82112d69: devlink_fmsg_u32_pair_put (STB_GLOBAL)
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
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffff800010c25ad8)
Location: net/core/devlink.c:4361
Inline: True
```
**Symbols:**

```
ffff800010c24be8-ffff800010c24c18: devlink_fmsg_u32_pair_put.part.0 (STB_LOCAL)
ffff800010c25ad8-ffff800010c25b6c: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (c0d44354)
Location: net/core/devlink.c:4361
Inline: True
```
**Symbols:**

```
c0d3bf88-c0d3bfa8: devlink_fmsg_u32_pair_put.part.0 (STB_LOCAL)
c0d44354-c0d443e4: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d26050)
Location: net/core/devlink.c:4361
Inline: True
```
**Symbols:**

```
c000000000d26050-c000000000d260f4: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffe00079f472)
Location: net/core/devlink.c:4361
Inline: True
```
**Symbols:**

```
ffffffe00079cd98-ffffffe00079cdc6: devlink_fmsg_u32_pair_put.part.0 (STB_LOCAL)
ffffffe00079f472-ffffffe00079f4dc: devlink_fmsg_u32_pair_put (STB_GLOBAL)
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
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81927a30)
Location: net/core/devlink.c:4361
Inline: True
```
**Symbols:**

```
ffffffff81927a30-ffffffff81927aa6: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e17e0)
Location: net/core/devlink.c:4361
Inline: True
```
**Symbols:**

```
ffffffff818e17e0-ffffffff818e1856: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81978bc0)
Location: net/core/devlink.c:4361
Inline: True
```
**Symbols:**

```
ffffffff81978bc0-ffffffff81978c36: devlink_fmsg_u32_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u32_pair_put(struct devlink_fmsg *fmsg, const char *name, u32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199b0b0)
Location: net/core/devlink.c:4361
Inline: True
```
**Symbols:**

```
ffffffff8199b0b0-ffffffff8199b126: devlink_fmsg_u32_pair_put (STB_GLOBAL)
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
