# Function: <code>devlink_fmsg_string_put</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194f300)
Location: net/core/devlink.c:4251
Inline: False
```
**Symbols:**

```
ffffffff8194f300-ffffffff8194f337: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81986070)
Location: net/core/devlink.c:4305
Inline: False
```
**Symbols:**

```
ffffffff81986070-ffffffff819860a7: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a55bd0)
Location: net/core/devlink.c:4803
Inline: False
```
**Symbols:**

```
ffffffff81a55bd0-ffffffff81a55c13: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5cfb0)
Location: net/core/devlink.c:5492
Inline: False
```
**Symbols:**

```
ffffffff81a5cfb0-ffffffff81a5cff3: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3de00)
Location: net/core/devlink.c:5695
Inline: False
```
**Symbols:**

```
ffffffff81a3de00-ffffffff81a3de43: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6308
Inline: False
```
**Symbols:**

```
ffffffff81d385c1-ffffffff81d385d5: devlink_fmsg_string_put.cold (STB_LOCAL)
ffffffff81af4390-ffffffff81af43e2: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6800
Inline: False
```
**Symbols:**

```
ffffffff81f04f70-ffffffff81f04f85: devlink_fmsg_string_put.cold (STB_LOCAL)
ffffffff81c78610-ffffffff81c78671: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7355
Inline: False
```
**Symbols:**

```
ffffffff820acf6e-ffffffff820acf83: devlink_fmsg_string_put.cold (STB_LOCAL)
ffffffff81e318f0-ffffffff81e31951: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:872
Inline: False
```
**Symbols:**

```
ffffffff82136762-ffffffff82136777: devlink_fmsg_string_put.cold (STB_LOCAL)
ffffffff820465f0-ffffffff82046651: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:849
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_fmsg_string_pair_put
```
**Symbols:**

```
ffffffff822183d4-ffffffff822183e9: devlink_fmsg_string_put.cold (STB_LOCAL)
ffffffff82112660-ffffffff821126ca: devlink_fmsg_string_put (STB_GLOBAL)
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
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c258a8)
Location: net/core/devlink.c:4305
Inline: False
```
**Symbols:**

```
ffff800010c258a8-ffff800010c258ec: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d40858)
Location: net/core/devlink.c:4305
Inline: False
```
**Symbols:**

```
c0d40858-c0d40898: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25df0)
Location: net/core/devlink.c:4305
Inline: False
```
**Symbols:**

```
c000000000d25df0-c000000000d25e50: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079f5b2)
Location: net/core/devlink.c:4305
Inline: False
```
**Symbols:**

```
ffffffe00079f5b2-ffffffe00079f5f8: devlink_fmsg_string_put (STB_GLOBAL)
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
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925ee0)
Location: net/core/devlink.c:4305
Inline: False
```
**Symbols:**

```
ffffffff81925ee0-ffffffff81925f17: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dfc90)
Location: net/core/devlink.c:4305
Inline: False
```
**Symbols:**

```
ffffffff818dfc90-ffffffff818dfcc7: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81977070)
Location: net/core/devlink.c:4305
Inline: False
```
**Symbols:**

```
ffffffff81977070-ffffffff819770a7: devlink_fmsg_string_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_fmsg_string_put(struct devlink_fmsg *fmsg, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81999560)
Location: net/core/devlink.c:4305
Inline: False
```
**Symbols:**

```
ffffffff81999560-ffffffff81999597: devlink_fmsg_string_put (STB_GLOBAL)
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
