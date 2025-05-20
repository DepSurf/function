# Function: <code>devlink_fmsg_binary_pair_nest_end</code>

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
int devlink_fmsg_binary_pair_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a53950)
Location: net/core/devlink.c:4735
Inline: True
```
**Symbols:**

```
ffffffff81a53950-ffffffff81a539f5: devlink_fmsg_binary_pair_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5a430)
Location: net/core/devlink.c:5424
Inline: True
```
**Symbols:**

```
ffffffff81a5a430-ffffffff81a5a4d5: devlink_fmsg_binary_pair_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3cd10)
Location: net/core/devlink.c:5627
Inline: True
```
**Symbols:**

```
ffffffff81a3cd10-ffffffff81a3cd79: devlink_fmsg_binary_pair_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81af4c67)
Location: net/core/devlink.c:6240
Inline: True
```
**Symbols:**

```
ffffffff81d38450-ffffffff81d38464: devlink_fmsg_binary_pair_nest_end.cold (STB_LOCAL)
ffffffff81af3880-ffffffff81af38c7: devlink_fmsg_binary_pair_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81c78f66)
Location: net/core/devlink.c:6735
Inline: True
```
**Symbols:**

```
ffffffff81f04e22-ffffffff81f04e37: devlink_fmsg_binary_pair_nest_end.cold (STB_LOCAL)
ffffffff81c77650-ffffffff81c776a0: devlink_fmsg_binary_pair_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81e31e66)
Location: net/core/devlink.c:7290
Inline: True
```
**Symbols:**

```
ffffffff820ace0b-ffffffff820ace20: devlink_fmsg_binary_pair_nest_end.cold (STB_LOCAL)
ffffffff81e30180-ffffffff81e301d0: devlink_fmsg_binary_pair_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devlink_fmsg_binary_pair_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff82046776)
Location: net/devlink/health.c:807
Inline: True
```
**Symbols:**

```
ffffffff82136738-ffffffff8213674d: devlink_fmsg_binary_pair_nest_end.cold (STB_LOCAL)
ffffffff820460b0-ffffffff82046100: devlink_fmsg_binary_pair_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devlink_fmsg_binary_pair_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff82112ee4)
Location: net/devlink/health.c:784
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
```
**Symbols:**

```
ffffffff8221859c-ffffffff822185f0: devlink_fmsg_binary_pair_nest_end.cold (STB_LOCAL)
ffffffff82112d80-ffffffff82112e3e: devlink_fmsg_binary_pair_nest_end (STB_GLOBAL)
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
