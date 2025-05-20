# Function: <code>ipc_idr_alloc</code>

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
In ipc/util.c (ffffffff813f090c)
Location: ipc/util.c:197
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffff8141cdf6)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffff81436c46)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffff81486ef2)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffff814a4512)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffff814aa4e0)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (0)
Location: ipc/util.c:202
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff81501f80-ffffffff815020aa: ipc_idr_alloc.constprop.0 (STB_LOCAL)
ffffffff81cd2815-ffffffff81cd28a9: ipc_idr_alloc.constprop.0.cold (STB_LOCAL)
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
In ipc/util.c (0)
Location: ipc/util.c:202
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff81593540-ffffffff81593695: ipc_idr_alloc.constprop.0 (STB_LOCAL)
ffffffff81e8595c-ffffffff81e859e8: ipc_idr_alloc.constprop.0.cold (STB_LOCAL)
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
In ipc/util.c (0)
Location: ipc/util.c:202
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff8163bf70-ffffffff8163c0c5: ipc_idr_alloc.constprop.0 (STB_LOCAL)
ffffffff82072b6a-ffffffff82072bf6: ipc_idr_alloc.constprop.0.cold (STB_LOCAL)
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
In ipc/util.c (0)
Location: ipc/util.c:202
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff81674420-ffffffff81674576: ipc_idr_alloc.constprop.0 (STB_LOCAL)
ffffffff820f27ce-ffffffff820f284d: ipc_idr_alloc.constprop.0.cold (STB_LOCAL)
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
In ipc/util.c (0)
Location: ipc/util.c:202
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff816b07e0-ffffffff816b0936: ipc_idr_alloc.constprop.0 (STB_LOCAL)
ffffffff821cfa7e-ffffffff821cfafd: ipc_idr_alloc.constprop.0.cold (STB_LOCAL)
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
In ipc/util.c (0)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (c06d9684)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (c0000000006662d8)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffe000384b88)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffff8142f226)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffff8141fca6)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffff8142b3c6)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
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
In ipc/util.c (ffffffff8144231b)
Location: ipc/util.c:201
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
</details>
</li>
</ul>

## Differences
