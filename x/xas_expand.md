# Function: <code>xas_expand</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1821a)
Location: lib/xarray.c:539
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a87ce1)
Location: lib/xarray.c:554
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abef81)
Location: lib/xarray.c:555
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xas_expand(struct xa_state *xas, void *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fa690)
Location: lib/xarray.c:555
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff815fa690-ffffffff815fa8ac: xas_expand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xas_expand(struct xa_state *xas, void *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161ee90)
Location: lib/xarray.c:558
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff8161ee90-ffffffff8161f0ac: xas_expand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff816024e0)
Location: lib/xarray.c:558
Inline: True
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff816024e0-ffffffff816026fc: xas_expand.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:558
Inline: True
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81670630-ffffffff81670873: xas_expand.constprop.0 (STB_LOCAL)
ffffffff81cdfd4c-ffffffff81cdfdb3: xas_expand.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:561
Inline: True
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff8178b930-ffffffff8178bbb1: xas_expand.constprop.0 (STB_LOCAL)
ffffffff81ea66dd-ffffffff81ea6743: xas_expand.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:561
Inline: True
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff82048e60-ffffffff820490f6: xas_expand.constprop.0 (STB_LOCAL)
ffffffff820b7eaa-ffffffff820b7f10: xas_expand.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:559
Inline: True
Direct callers:
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff820c7710-ffffffff820c79d0: xas_expand.constprop.0 (STB_LOCAL)
ffffffff821392fe-ffffffff82139359: xas_expand.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:559
Inline: True
Direct callers:
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff821a2090-ffffffff821a2350: xas_expand.constprop.0 (STB_LOCAL)
ffffffff8221b0a3-ffffffff8221b0fe: xas_expand.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9a178)
Location: lib/xarray.c:555
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96f4c)
Location: lib/xarray.c:555
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee05c0)
Location: lib/xarray.c:555
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c1b28)
Location: lib/xarray.c:555
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5ddd1)
Location: lib/xarray.c:555
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1aea1)
Location: lib/xarray.c:555
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81aca1c1)
Location: lib/xarray.c:555
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad6791)
Location: lib/xarray.c:555
Inline: True
Inline callers:
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
