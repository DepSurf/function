# Function: <code>devlink_fmsg_string_pair_put</code>

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
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194fae0)
Location: net/core/devlink.c:4349
Inline: True
```
**Symbols:**

```
ffffffff8194fae0-ffffffff8194fb24: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81987cc0)
Location: net/core/devlink.c:4403
Inline: True
```
**Symbols:**

```
ffffffff81987cc0-ffffffff81987d04: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a55c20)
Location: net/core/devlink.c:4907
Inline: True
```
**Symbols:**

```
ffffffff81a53580-ffffffff81a535dc: devlink_fmsg_string_pair_put.part.0 (STB_LOCAL)
ffffffff81a55c20-ffffffff81a55c5f: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d000)
Location: net/core/devlink.c:5596
Inline: True
```
**Symbols:**

```
ffffffff81a59d00-ffffffff81a59d5c: devlink_fmsg_string_pair_put.part.0 (STB_LOCAL)
ffffffff81a5d000-ffffffff81a5d03f: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a3e970)
Location: net/core/devlink.c:5799
Inline: True
```
**Symbols:**

```
ffffffff81a3ccb0-ffffffff81a3cd0c: devlink_fmsg_string_pair_put.part.0 (STB_LOCAL)
ffffffff81a3e970-ffffffff81a3e9af: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6412
Inline: True
```
**Symbols:**

```
ffffffff81d38710-ffffffff81d38725: devlink_fmsg_string_pair_put.cold (STB_LOCAL)
ffffffff81af4f50-ffffffff81af4fac: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c79080)
Location: net/core/devlink.c:6904
Inline: True
```
**Symbols:**

```
ffffffff81c79080-ffffffff81c790d0: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e31fa0)
Location: net/core/devlink.c:7459
Inline: True
```
**Symbols:**

```
ffffffff81e31fa0-ffffffff81e31ff0: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82046940)
Location: net/devlink/health.c:976
Inline: True
```
**Symbols:**

```
ffffffff82046940-ffffffff82046990: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:902
Inline: False
```
**Symbols:**

```
ffffffff82218437-ffffffff8221845e: devlink_fmsg_string_pair_put.cold (STB_LOCAL)
ffffffff821128c0-ffffffff82112937: devlink_fmsg_string_pair_put (STB_GLOBAL)
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
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffff800010c258f0)
Location: net/core/devlink.c:4403
Inline: True
```
**Symbols:**

```
ffff800010c24be8-ffff800010c24c18: devlink_fmsg_string_pair_put.part.0 (STB_LOCAL)
ffff800010c258f0-ffff800010c2595c: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (c0d4447c)
Location: net/core/devlink.c:4403
Inline: True
```
**Symbols:**

```
c0d3bf88-c0d3bfa8: devlink_fmsg_string_pair_put.part.0 (STB_LOCAL)
c0d4447c-c0d444c4: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25e50)
Location: net/core/devlink.c:4403
Inline: True
```
**Symbols:**

```
c000000000d25e50-c000000000d25ed0: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffe00079f5f8)
Location: net/core/devlink.c:4403
Inline: True
```
**Symbols:**

```
ffffffe00079cd98-ffffffe00079cdc6: devlink_fmsg_string_pair_put.part.0 (STB_LOCAL)
ffffffe00079f5f8-ffffffe00079f658: devlink_fmsg_string_pair_put (STB_GLOBAL)
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
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81927b30)
Location: net/core/devlink.c:4403
Inline: True
```
**Symbols:**

```
ffffffff81927b30-ffffffff81927b74: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e18e0)
Location: net/core/devlink.c:4403
Inline: True
```
**Symbols:**

```
ffffffff818e18e0-ffffffff818e1924: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81978cc0)
Location: net/core/devlink.c:4403
Inline: True
```
**Symbols:**

```
ffffffff81978cc0-ffffffff81978d04: devlink_fmsg_string_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_string_pair_put(struct devlink_fmsg *fmsg, const char *name, const char *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199b1b0)
Location: net/core/devlink.c:4403
Inline: True
```
**Symbols:**

```
ffffffff8199b1b0-ffffffff8199b1f4: devlink_fmsg_string_pair_put (STB_GLOBAL)
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
