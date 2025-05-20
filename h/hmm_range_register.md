# Function: <code>hmm_range_register</code>

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
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror, long unsigned int start, long unsigned int end, unsigned int page_shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812c2e20)
Location: mm/hmm.c:869
Inline: False
```
**Symbols:**

```
ffffffff812c2e20-ffffffff812c2f01: hmm_range_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d4cd0)
Location: mm/hmm.c:791
Inline: False
```
**Symbols:**

```
ffffffff812d4cd0-ffffffff812d4d8c: hmm_range_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037b0a0)
Location: mm/hmm.c:791
Inline: False
```
**Symbols:**

```
ffff80001037b0a0-ffff80001037b204: hmm_range_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c0565c30)
Location: mm/hmm.c:791
Inline: False
```
**Symbols:**

```
c0565c30-c0565d18: hmm_range_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046e600)
Location: mm/hmm.c:791
Inline: False
```
**Symbols:**

```
c00000000046e600-c00000000046e748: hmm_range_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe0002513f4)
Location: mm/hmm.c:791
Inline: False
```
**Symbols:**

```
ffffffe0002513f4-ffffffe0002514b6: hmm_range_register (STB_GLOBAL)
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
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cd2b0)
Location: mm/hmm.c:791
Inline: False
```
**Symbols:**

```
ffffffff812cd2b0-ffffffff812cd36c: hmm_range_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812be120)
Location: mm/hmm.c:791
Inline: False
```
**Symbols:**

```
ffffffff812be120-ffffffff812be1dc: hmm_range_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cb0c0)
Location: mm/hmm.c:791
Inline: False
```
**Symbols:**

```
ffffffff812cb0c0-ffffffff812cb17c: hmm_range_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hmm_range_register(struct hmm_range *range, struct hmm_mirror *mirror);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dbe20)
Location: mm/hmm.c:791
Inline: False
```
**Symbols:**

```
ffffffff812dbe20-ffffffff812dbedc: hmm_range_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int page_shift</code>
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
