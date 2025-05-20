# Function: <code>edac_mc_alloc_dimms</code>

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
int edac_mc_alloc_dimms(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81988390)
Location: drivers/edac/edac_mc.c:303
Inline: False
```
**Symbols:**

```
ffffffff81988390-ffffffff819885ef: edac_mc_alloc_dimms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int edac_mc_alloc_dimms(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198cce0)
Location: drivers/edac/edac_mc.c:307
Inline: False
```
**Symbols:**

```
ffffffff8198cce0-ffffffff8198cf3f: edac_mc_alloc_dimms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int edac_mc_alloc_dimms(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff819712b0)
Location: drivers/edac/edac_mc.c:307
Inline: False
```
**Symbols:**

```
ffffffff819712b0-ffffffff8197150f: edac_mc_alloc_dimms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int edac_mc_alloc_dimms(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:310
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff81a19d90-ffffffff81a1a0f6: edac_mc_alloc_dimms (STB_LOCAL)
ffffffff81d2a9ea-ffffffff81d2a9fe: edac_mc_alloc_dimms.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int edac_mc_alloc_dimms(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:255
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff81b82ba0-ffffffff81b82f31: edac_mc_alloc_dimms (STB_LOCAL)
ffffffff81ef6ba3-ffffffff81ef6bb8: edac_mc_alloc_dimms.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int edac_mc_alloc_dimms(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:254
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff81d214f0-ffffffff81d21881: edac_mc_alloc_dimms (STB_LOCAL)
ffffffff820a8919-ffffffff820a892e: edac_mc_alloc_dimms.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int edac_mc_alloc_dimms(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:254
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff81d8a6f0-ffffffff81d8aa85: edac_mc_alloc_dimms (STB_LOCAL)
ffffffff82129b09-ffffffff82129b1e: edac_mc_alloc_dimms.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int edac_mc_alloc_dimms(struct mem_ctl_info *mci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:255
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
```
**Symbols:**

```
ffffffff81e41e40-ffffffff81e42205: edac_mc_alloc_dimms (STB_LOCAL)
ffffffff8220b85d-ffffffff8220b872: edac_mc_alloc_dimms.cold (STB_LOCAL)
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
