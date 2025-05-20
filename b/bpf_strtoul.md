# Function: <code>bpf_strtoul</code>

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
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e6610)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
ffffffff811e6610-ffffffff811e6676: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f2d60)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
ffffffff811f2d60-ffffffff811f2dc6: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81214be0)
Location: kernel/bpf/helpers.c:506
Inline: False
```
**Symbols:**

```
ffffffff81214be0-ffffffff81214c45: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81216780)
Location: kernel/bpf/helpers.c:517
Inline: False
```
**Symbols:**

```
ffffffff81216780-ffffffff812167e5: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812194c0)
Location: kernel/bpf/helpers.c:525
Inline: False
```
**Symbols:**

```
ffffffff812194c0-ffffffff81219525: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:539
Inline: False
```
**Symbols:**

```
ffffffff81cb9036-ffffffff81cb9051: bpf_strtoul.cold (STB_LOCAL)
ffffffff81250260-ffffffff812502d9: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:553
Inline: False
```
**Symbols:**

```
ffffffff81e6a2fb-ffffffff81e6a316: bpf_strtoul.cold (STB_LOCAL)
ffffffff81297560-ffffffff812975f4: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:537
Inline: False
```
**Symbols:**

```
ffffffff820613c8-ffffffff820613e3: bpf_strtoul.cold (STB_LOCAL)
ffffffff812f23c0-ffffffff812f2454: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:538
Inline: False
```
**Symbols:**

```
ffffffff820e086e-ffffffff820e0889: bpf_strtoul.cold (STB_LOCAL)
ffffffff8131ef40-ffffffff8131efd4: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:544
Inline: False
```
**Symbols:**

```
ffffffff821bcf67-ffffffff821bcf82: bpf_strtoul.cold (STB_LOCAL)
ffffffff81341370-ffffffff81341404: bpf_strtoul (STB_GLOBAL)
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
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffff800010276660)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
ffff800010276660-ffff800010276704: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c04a8d00)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
c04a8d00-c04a8db4: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c00000000031ed60)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
c00000000031ed60-c00000000031edf4: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffe0001aec18)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
ffffffe0001aec18-ffffffe0001aec78: bpf_strtoul (STB_GLOBAL)
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
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811eb380)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
ffffffff811eb380-ffffffff811eb3e6: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811de130)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
ffffffff811de130-ffffffff811de196: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e9150)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
ffffffff811e9150-ffffffff811e91b6: bpf_strtoul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_strtoul(u64 buf, u64 buf_len, u64 flags, u64 res, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f7500)
Location: kernel/bpf/helpers.c:462
Inline: False
```
**Symbols:**

```
ffffffff811f7500-ffffffff811f7566: bpf_strtoul (STB_GLOBAL)
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
