# Function: <code>devlink_fmsg_u64_pair_put</code>

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
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194fa60)
Location: net/core/devlink.c:4328
Inline: True
```
**Symbols:**

```
ffffffff8194fa60-ffffffff8194fad8: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81987c40)
Location: net/core/devlink.c:4382
Inline: True
```
**Symbols:**

```
ffffffff81987c40-ffffffff81987cb8: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a55ee0)
Location: net/core/devlink.c:4886
Inline: True
```
**Symbols:**

```
ffffffff81a53580-ffffffff81a535dc: devlink_fmsg_u64_pair_put.part.0 (STB_LOCAL)
ffffffff81a55ee0-ffffffff81a55f60: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d240)
Location: net/core/devlink.c:5575
Inline: True
```
**Symbols:**

```
ffffffff81a59d00-ffffffff81a59d5c: devlink_fmsg_u64_pair_put.part.0 (STB_LOCAL)
ffffffff81a5d240-ffffffff81a5d2c0: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a3e8f0)
Location: net/core/devlink.c:5778
Inline: True
```
**Symbols:**

```
ffffffff81a3ccb0-ffffffff81a3cd0c: devlink_fmsg_u64_pair_put.part.0 (STB_LOCAL)
ffffffff81a3e8f0-ffffffff81a3e970: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6391
Inline: True
```
**Symbols:**

```
ffffffff81d386e8-ffffffff81d38710: devlink_fmsg_u64_pair_put.cold (STB_LOCAL)
ffffffff81af4ea0-ffffffff81af4f42: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81c79262)
Location: net/core/devlink.c:6883
Inline: True
```
**Symbols:**

```
ffffffff81f05069-ffffffff81f0507e: devlink_fmsg_u64_pair_put.cold (STB_LOCAL)
ffffffff81c79210-ffffffff81c792a9: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81e321b2)
Location: net/core/devlink.c:7438
Inline: True
```
**Symbols:**

```
ffffffff820ad067-ffffffff820ad07c: devlink_fmsg_u64_pair_put.cold (STB_LOCAL)
ffffffff81e32160-ffffffff81e321f9: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff82046b52)
Location: net/devlink/health.c:955
Inline: True
```
**Symbols:**

```
ffffffff8213684e-ffffffff82136863: devlink_fmsg_u64_pair_put.cold (STB_LOCAL)
ffffffff82046b00-ffffffff82046b99: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:893
Inline: False
```
**Symbols:**

```
ffffffff822184e8-ffffffff82218524: devlink_fmsg_u64_pair_put.cold (STB_LOCAL)
ffffffff82112ae0-ffffffff82112ba9: devlink_fmsg_u64_pair_put (STB_GLOBAL)
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
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffff800010c25b70)
Location: net/core/devlink.c:4382
Inline: True
```
**Symbols:**

```
ffff800010c24be8-ffff800010c24c18: devlink_fmsg_u64_pair_put.part.0 (STB_LOCAL)
ffff800010c25b70-ffff800010c25c04: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (c0d443e4)
Location: net/core/devlink.c:4382
Inline: True
```
**Symbols:**

```
c0d3bf88-c0d3bfa8: devlink_fmsg_u64_pair_put.part.0 (STB_LOCAL)
c0d443e4-c0d4447c: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d26100)
Location: net/core/devlink.c:4382
Inline: True
```
**Symbols:**

```
c000000000d26100-c000000000d261a4: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffe00079f4dc)
Location: net/core/devlink.c:4382
Inline: True
```
**Symbols:**

```
ffffffe00079cd98-ffffffe00079cdc6: devlink_fmsg_u64_pair_put.part.0 (STB_LOCAL)
ffffffe00079f4dc-ffffffe00079f546: devlink_fmsg_u64_pair_put (STB_GLOBAL)
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
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81927ab0)
Location: net/core/devlink.c:4382
Inline: True
```
**Symbols:**

```
ffffffff81927ab0-ffffffff81927b28: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e1860)
Location: net/core/devlink.c:4382
Inline: True
```
**Symbols:**

```
ffffffff818e1860-ffffffff818e18d8: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81978c40)
Location: net/core/devlink.c:4382
Inline: True
```
**Symbols:**

```
ffffffff81978c40-ffffffff81978cb8: devlink_fmsg_u64_pair_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_u64_pair_put(struct devlink_fmsg *fmsg, const char *name, u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199b130)
Location: net/core/devlink.c:4382
Inline: True
```
**Symbols:**

```
ffffffff8199b130-ffffffff8199b1a8: devlink_fmsg_u64_pair_put (STB_GLOBAL)
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
