# Function: <code>icc_set_bw</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path *path, u32 avg_bw, u32 peak_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dcbb0)
Location: drivers/interconnect/core.c:591
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_put
  - drivers/interconnect/core.c:__icc_enable
```
**Symbols:**

```
ffffffff819dcbb0-ffffffff819dcdb1: icc_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path *path, u32 avg_bw, u32 peak_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dc330)
Location: drivers/interconnect/core.c:622
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_put
  - drivers/interconnect/core.c:__icc_enable
  - drivers/interconnect/bulk.c:icc_bulk_set_bw
```
**Symbols:**

```
ffffffff819dc330-ffffffff819dc4da: icc_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path *path, u32 avg_bw, u32 peak_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c25b0)
Location: drivers/interconnect/core.c:622
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_put
  - drivers/interconnect/core.c:__icc_enable
  - drivers/interconnect/bulk.c:icc_bulk_set_bw
```
**Symbols:**

```
ffffffff819c25b0-ffffffff819c275a: icc_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path *path, u32 avg_bw, u32 peak_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81a71e60)
Location: drivers/interconnect/core.c:622
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_put
  - drivers/interconnect/bulk.c:icc_bulk_set_bw
```
**Symbols:**

```
ffffffff81a71e60-ffffffff81a72004: icc_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path *path, u32 avg_bw, u32 peak_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81be3910)
Location: drivers/interconnect/core.c:622
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp_bw
  - drivers/interconnect/core.c:icc_put
  - drivers/interconnect/bulk.c:icc_bulk_set_bw
```
**Symbols:**

```
ffffffff81be3910-ffffffff81be3adf: icc_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path *path, u32 avg_bw, u32 peak_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8f5e0)
Location: drivers/interconnect/core.c:622
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp_bw
  - drivers/opp/core.c:_set_opp_bw
  - drivers/interconnect/core.c:icc_put
  - drivers/interconnect/bulk.c:icc_bulk_set_bw
```
**Symbols:**

```
ffffffff81d8f5e0-ffffffff81d8f7c4: icc_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path *path, u32 avg_bw, u32 peak_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81dfdbc0)
Location: drivers/interconnect/core.c:621
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp_bw
  - drivers/opp/core.c:_set_opp_bw
  - drivers/interconnect/bulk.c:icc_bulk_set_bw
```
**Symbols:**

```
ffffffff81dfdbc0-ffffffff81dfdda4: icc_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int icc_set_bw(struct icc_path *path, u32 avg_bw, u32 peak_bw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb4620)
Location: drivers/interconnect/core.c:688
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp_bw
  - drivers/opp/core.c:_set_opp_bw
  - drivers/interconnect/bulk.c:icc_bulk_set_bw
```
**Symbols:**

```
ffffffff81eb4620-ffffffff81eb4804: icc_set_bw (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
