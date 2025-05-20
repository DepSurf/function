# Function: <code>bpf_strtol</code>

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
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e6680)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
ffffffff811e6680-ffffffff811e66f8: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f2dd0)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
ffffffff811f2dd0-ffffffff811f2e48: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81214c50)
Location: kernel/bpf/helpers.c:481
Inline: False
```
**Symbols:**

```
ffffffff81214c50-ffffffff81214cc7: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812167f0)
Location: kernel/bpf/helpers.c:492
Inline: False
```
**Symbols:**

```
ffffffff812167f0-ffffffff81216867: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81219530)
Location: kernel/bpf/helpers.c:500
Inline: False
```
**Symbols:**

```
ffffffff81219530-ffffffff812195a7: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:514
Inline: False
```
**Symbols:**

```
ffffffff81cb9051-ffffffff81cb906c: bpf_strtol.cold (STB_LOCAL)
ffffffff812502e0-ffffffff8125036b: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:528
Inline: False
```
**Symbols:**

```
ffffffff81e6a316-ffffffff81e6a331: bpf_strtol.cold (STB_LOCAL)
ffffffff81297600-ffffffff8129769f: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:512
Inline: False
```
**Symbols:**

```
ffffffff820613e3-ffffffff820613fe: bpf_strtol.cold (STB_LOCAL)
ffffffff812f2470-ffffffff812f250f: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:513
Inline: False
```
**Symbols:**

```
ffffffff820e0889-ffffffff820e08a4: bpf_strtol.cold (STB_LOCAL)
ffffffff8131eff0-ffffffff8131f08f: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:519
Inline: False
```
**Symbols:**

```
ffffffff821bcf82-ffffffff821bcf9d: bpf_strtol.cold (STB_LOCAL)
ffffffff81341420-ffffffff813414bf: bpf_strtol (STB_GLOBAL)
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
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffff800010276708)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
ffff800010276708-ffff8000102767c0: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c04a8db4)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
c04a8db4-c04a8e84: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c00000000031ee00)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
c00000000031ee00-c00000000031eea8: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffe0001aec78)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
ffffffe0001aec78-ffffffe0001aece4: bpf_strtol (STB_GLOBAL)
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
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811eb3f0)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
ffffffff811eb3f0-ffffffff811eb468: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811de1a0)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
ffffffff811de1a0-ffffffff811de218: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e91c0)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
ffffffff811e91c0-ffffffff811e9238: bpf_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_strtol(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f7570)
Location: kernel/bpf/helpers.c:437
Inline: False
```
**Symbols:**

```
ffffffff811f7570-ffffffff811f75e8: bpf_strtol (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
