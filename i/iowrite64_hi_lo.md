# Function: <code>iowrite64_hi_lo</code>

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
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510cb0)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff81510cb0-ffffffff81510cf2: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531720)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff81531720-ffffffff81531762: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595d60)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff81595d60-ffffffff81595db9: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b17f0)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff815b17f0-ffffffff815b1849: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc600)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff815bc600-ffffffff815bc659: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81623450)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff81623450-ffffffff816234a9: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f3420)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff816f3420-ffffffff816f34ae: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e5380)
Location: lib/iomap.c:272
Inline: False
```
**Symbols:**

```
ffffffff817e5380-ffffffff817e540e: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff818253c0)
Location: lib/iomap.c:272
Inline: False
```
**Symbols:**

```
ffffffff818253c0-ffffffff8182544e: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81876dd0)
Location: lib/iomap.c:272
Inline: False
```
**Symbols:**

```
ffffffff81876dd0-ffffffff81876e5e: iowrite64_hi_lo (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/perf.c (c0c396ac)
Location: include/linux/io-64-nonatomic-hi-lo.h:73
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e6cc0)
Location: lib/iomap.c:246
Inline: True
```
**Symbols:**

```
c0000000007e6cc0-c0000000007e6e14: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529d00)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff81529d00-ffffffff81529d42: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81519fe0)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff81519fe0-ffffffff8151a022: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525d90)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff81525d90-ffffffff81525dd2: iowrite64_hi_lo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iowrite64_hi_lo(u64 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f710)
Location: lib/iomap.c:246
Inline: False
```
**Symbols:**

```
ffffffff8153f710-ffffffff8153f752: iowrite64_hi_lo (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
