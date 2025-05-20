# Function: <code>edac_mc_alloc_csrows</code>

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
int edac_mc_alloc_csrows(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81988e70)
Location: drivers/edac/edac_mc.c:258
Inline: False
```
**Symbols:**

```
ffffffff81988e70-ffffffff81988f9f: edac_mc_alloc_csrows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int edac_mc_alloc_csrows(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198cbb0)
Location: drivers/edac/edac_mc.c:262
Inline: False
```
**Symbols:**

```
ffffffff8198cbb0-ffffffff8198ccdf: edac_mc_alloc_csrows (STB_LOCAL)
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
In drivers/edac/edac_mc.c (ffffffff81971660)
Location: drivers/edac/edac_mc.c:262
Inline: True
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
In drivers/edac/edac_mc.c (ffffffff81a1a2a7)
Location: drivers/edac/edac_mc.c:265
Inline: True
Inline callers:
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
In drivers/edac/edac_mc.c (ffffffff81b830ff)
Location: drivers/edac/edac_mc.c:210
Inline: True
Inline callers:
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
In drivers/edac/edac_mc.c (ffffffff81d21a5f)
Location: drivers/edac/edac_mc.c:209
Inline: True
Inline callers:
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
In drivers/edac/edac_mc.c (ffffffff81d8ac6d)
Location: drivers/edac/edac_mc.c:209
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int edac_mc_alloc_csrows(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81e42220)
Location: drivers/edac/edac_mc.c:210
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff81e42220-ffffffff81e423dc: edac_mc_alloc_csrows (STB_LOCAL)
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
</ul>
