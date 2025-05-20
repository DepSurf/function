# Function: <code>_edac_mc_free</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8175bb30)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff8175bb30-ffffffff8175bc1d: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff817cdd80)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff817cdd80-ffffffff817cde6d: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81816b60)
Location: drivers/edac/edac_mc.c:278
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff81816b60-ffffffff81816c51: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81842440)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff81842440-ffffffff81842531: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff818852b0)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff818852b0-ffffffff818853a1: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff818b7240)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff818b7240-ffffffff818b7336: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81987dc5)
Location: drivers/edac/edac_mc.c:223
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198bcf5)
Location: drivers/edac/edac_mc.c:227
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81970395)
Location: drivers/edac/edac_mc.c:227
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81a18cb5)
Location: drivers/edac/edac_mc.c:230
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81b81a45)
Location: drivers/edac/edac_mc.c:173
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d20195)
Location: drivers/edac/edac_mc.c:172
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d89395)
Location: drivers/edac/edac_mc.c:172
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81e40ad5)
Location: drivers/edac/edac_mc.c:173
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
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
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffff800010b0f2b8)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffff800010b0f2b8-ffff800010b0f3a0: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c0bed5f8)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
c0bed5f8-c0bed6e4: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c000000000c026f0)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
c000000000c026f0-c000000000c02864: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffe0006fc430)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffe0006fc430-ffffffe0006fc516: _edac_mc_free (STB_LOCAL)
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
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8185d0c0)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff8185d0c0-ffffffff8185d1b6: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81824690)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff81824690-ffffffff81824786: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff818ac6f0)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff818ac6f0-ffffffff818ac7e6: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _edac_mc_free(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff818c8940)
Location: drivers/edac/edac_mc.c:276
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_free
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff818c8940-ffffffff818c8a36: _edac_mc_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
