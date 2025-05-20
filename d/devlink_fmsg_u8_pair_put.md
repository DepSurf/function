# Function: <code>devlink_fmsg_u8_pair_put</code>

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
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194f960)
Location: net/core/devlink.c:4286
Inline: True
```
**Symbols:**

```
ffffffff8194f960-ffffffff8194f9d6: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81987b40)
Location: net/core/devlink.c:4340
Inline: True
```
**Symbols:**

```
ffffffff81987b40-ffffffff81987bb6: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a55d60)
Location: net/core/devlink.c:4844
Inline: True
```
**Symbols:**

```
ffffffff81a53580-ffffffff81a535dc: devlink_fmsg_u8_pair_put.part.0 (STB_LOCAL)
ffffffff81a55d60-ffffffff81a55dde: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d2c0)
Location: net/core/devlink.c:5533
Inline: True
```
**Symbols:**

```
ffffffff81a59d00-ffffffff81a59d5c: devlink_fmsg_u8_pair_put.part.0 (STB_LOCAL)
ffffffff81a5d2c0-ffffffff81a5d33e: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a3e7f0)
Location: net/core/devlink.c:5736
Inline: True
```
**Symbols:**

```
ffffffff81a3ccb0-ffffffff81a3cd0c: devlink_fmsg_u8_pair_put.part.0 (STB_LOCAL)
ffffffff81a3e7f0-ffffffff81a3e86e: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6349
Inline: True
```
**Symbols:**

```
ffffffff81d38698-ffffffff81d386c0: devlink_fmsg_u8_pair_put.cold (STB_LOCAL)
ffffffff81af4d60-ffffffff81af4e00: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81c791c2)
Location: net/core/devlink.c:6841
Inline: True
```
**Symbols:**

```
ffffffff81f05054-ffffffff81f05069: devlink_fmsg_u8_pair_put.cold (STB_LOCAL)
ffffffff81c79170-ffffffff81c79209: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81e32102)
Location: net/core/devlink.c:7396
Inline: True
```
**Symbols:**

```
ffffffff820ad052-ffffffff820ad067: devlink_fmsg_u8_pair_put.cold (STB_LOCAL)
ffffffff81e320b0-ffffffff81e32149: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff82046aa2)
Location: net/devlink/health.c:913
Inline: True
```
**Symbols:**

```
ffffffff82136839-ffffffff8213684e: devlink_fmsg_u8_pair_put.cold (STB_LOCAL)
ffffffff82046a50-ffffffff82046ae9: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:875
Inline: False
```
**Symbols:**

```
ffffffff822184ac-ffffffff822184e8: devlink_fmsg_u8_pair_put.cold (STB_LOCAL)
ffffffff82112a00-ffffffff82112ac9: devlink_fmsg_u8_pair_put (STB_GLOBAL)
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
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffff800010c25a40)
Location: net/core/devlink.c:4340
Inline: True
```
**Symbols:**

```
ffff800010c24be8-ffff800010c24c18: devlink_fmsg_u8_pair_put.part.0 (STB_LOCAL)
ffff800010c25a40-ffff800010c25ad4: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (c0d442c4)
Location: net/core/devlink.c:4340
Inline: True
```
**Symbols:**

```
c0d3bf88-c0d3bfa8: devlink_fmsg_u8_pair_put.part.0 (STB_LOCAL)
c0d442c4-c0d44354: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25fa0)
Location: net/core/devlink.c:4340
Inline: True
```
**Symbols:**

```
c000000000d25fa0-c000000000d26044: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffe00079f408)
Location: net/core/devlink.c:4340
Inline: True
```
**Symbols:**

```
ffffffe00079cd98-ffffffe00079cdc6: devlink_fmsg_u8_pair_put.part.0 (STB_LOCAL)
ffffffe00079f408-ffffffe00079f472: devlink_fmsg_u8_pair_put (STB_GLOBAL)
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
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819279b0)
Location: net/core/devlink.c:4340
Inline: True
```
**Symbols:**

```
ffffffff819279b0-ffffffff81927a26: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e1760)
Location: net/core/devlink.c:4340
Inline: True
```
**Symbols:**

```
ffffffff818e1760-ffffffff818e17d6: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81978b40)
Location: net/core/devlink.c:4340
Inline: True
```
**Symbols:**

```
ffffffff81978b40-ffffffff81978bb6: devlink_fmsg_u8_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u8_pair_put(struct devlink_fmsg *fmsg, const char *name, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199b030)
Location: net/core/devlink.c:4340
Inline: True
```
**Symbols:**

```
ffffffff8199b030-ffffffff8199b0a6: devlink_fmsg_u8_pair_put (STB_GLOBAL)
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
