# Function: <code>bpf_get_current_uid_gid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_current_uid_gid(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81177460)
Location: kernel/bpf/helpers.c:141
Inline: True
```
**Symbols:**

```
ffffffff81177460-ffffffff811774be: bpf_get_current_uid_gid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_current_uid_gid(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81185eb0)
Location: kernel/bpf/helpers.c:141
Inline: True
```
**Symbols:**

```
ffffffff81185eb0-ffffffff81185f0b: bpf_get_current_uid_gid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81193240)
Location: kernel/bpf/helpers.c:135
Inline: False
```
**Symbols:**

```
ffffffff81193240-ffffffff8119329b: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8119a260)
Location: kernel/bpf/helpers.c:135
Inline: False
```
**Symbols:**

```
ffffffff8119a260-ffffffff8119a2bb: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811a9630)
Location: kernel/bpf/helpers.c:135
Inline: False
```
**Symbols:**

```
ffffffff811a9630-ffffffff811a968a: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811c0b40)
Location: kernel/bpf/helpers.c:135
Inline: False
```
**Symbols:**

```
ffffffff811c0b40-ffffffff811c0b9a: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811d2020)
Location: kernel/bpf/helpers.c:176
Inline: False
```
**Symbols:**

```
ffffffff811d2020-ffffffff811d207a: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e6380)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
ffffffff811e6380-ffffffff811e63de: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f2ad0)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
ffffffff811f2ad0-ffffffff811f2b2e: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81214970)
Location: kernel/bpf/helpers.c:186
Inline: False
```
**Symbols:**

```
ffffffff81214970-ffffffff812149ce: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81216510)
Location: kernel/bpf/helpers.c:197
Inline: False
```
**Symbols:**

```
ffffffff81216510-ffffffff8121656e: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81219250)
Location: kernel/bpf/helpers.c:198
Inline: False
```
**Symbols:**

```
ffffffff81219250-ffffffff812192ae: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8124fa30)
Location: kernel/bpf/helpers.c:198
Inline: False
```
**Symbols:**

```
ffffffff8124fa30-ffffffff8124fa8e: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81296cf0)
Location: kernel/bpf/helpers.c:217
Inline: False
```
**Symbols:**

```
ffffffff81296cf0-ffffffff81296d62: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f1ce0)
Location: kernel/bpf/helpers.c:232
Inline: False
```
**Symbols:**

```
ffffffff812f1ce0-ffffffff812f1d52: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8131e8c0)
Location: kernel/bpf/helpers.c:233
Inline: False
```
**Symbols:**

```
ffffffff8131e8c0-ffffffff8131e932: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81340cf0)
Location: kernel/bpf/helpers.c:237
Inline: False
```
**Symbols:**

```
ffffffff81340cf0-ffffffff81340d62: bpf_get_current_uid_gid (STB_GLOBAL)
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
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffff800010276408)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
ffff800010276408-ffff800010276474: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c04a8abc)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
c04a8abc-c04a8b28: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c00000000031e9a0)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
c00000000031e9a0-c00000000031ea38: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffe0001ae9f2)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
ffffffe0001ae9f2-ffffffe0001aea5e: bpf_get_current_uid_gid (STB_GLOBAL)
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
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811eb0f0)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
ffffffff811eb0f0-ffffffff811eb14e: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811ddea0)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
ffffffff811ddea0-ffffffff811ddefe: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e8ec0)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
ffffffff811e8ec0-ffffffff811e8f1e: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_get_current_uid_gid(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f7270)
Location: kernel/bpf/helpers.c:171
Inline: False
```
**Symbols:**

```
ffffffff811f7270-ffffffff811f72ce: bpf_get_current_uid_gid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_3</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_4</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_5</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
