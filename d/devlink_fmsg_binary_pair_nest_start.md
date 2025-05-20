# Function: <code>devlink_fmsg_binary_pair_nest_start</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_start(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a53b30)
Location: net/core/devlink.c:4721
Inline: True
```
**Symbols:**

```
ffffffff81a53b30-ffffffff81a53ba9: devlink_fmsg_binary_pair_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_start(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5aa50)
Location: net/core/devlink.c:5410
Inline: True
```
**Symbols:**

```
ffffffff81a5aa50-ffffffff81a5aac9: devlink_fmsg_binary_pair_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_start(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3e66e)
Location: net/core/devlink.c:5613
Inline: True
```
**Symbols:**

```
ffffffff81a3e9b0-ffffffff81a3ea29: devlink_fmsg_binary_pair_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_start(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81af4bde)
Location: net/core/devlink.c:6226
Inline: True
```
**Symbols:**

```
ffffffff81d38725-ffffffff81d3873a: devlink_fmsg_binary_pair_nest_start.cold (STB_LOCAL)
ffffffff81af4fb0-ffffffff81af5047: devlink_fmsg_binary_pair_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_start(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81c78ede)
Location: net/core/devlink.c:6721
Inline: True
```
**Symbols:**

```
ffffffff81f0507e-ffffffff81f05093: devlink_fmsg_binary_pair_nest_start.cold (STB_LOCAL)
ffffffff81c792b0-ffffffff81c7935b: devlink_fmsg_binary_pair_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_start(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81e31dde)
Location: net/core/devlink.c:7276
Inline: True
```
**Symbols:**

```
ffffffff820ad07c-ffffffff820ad091: devlink_fmsg_binary_pair_nest_start.cold (STB_LOCAL)
ffffffff81e32210-ffffffff81e322bb: devlink_fmsg_binary_pair_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_start(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff820466ee)
Location: net/devlink/health.c:793
Inline: True
```
**Symbols:**

```
ffffffff821368ef-ffffffff82136904: devlink_fmsg_binary_pair_nest_start.cold (STB_LOCAL)
ffffffff82046e20-ffffffff82046ecb: devlink_fmsg_binary_pair_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devlink_fmsg_binary_pair_nest_start(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82112e68)
Location: net/devlink/health.c:776
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
```
**Symbols:**

```
ffffffff82112020-ffffffff8211205a: devlink_fmsg_binary_pair_nest_start (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
