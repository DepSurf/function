# Function: <code>delayed_ref_ctr_inc</code>

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
In kernel/events/uprobes.c (ffffffff811f64ed)
Location: kernel/events/uprobes.c:1289
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff8120e28f)
Location: kernel/events/uprobes.c:1277
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff8121b8cf)
Location: kernel/events/uprobes.c:1329
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1328
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff81246900-ffffffff812469d1: delayed_ref_ctr_inc.isra.0 (STB_LOCAL)
ffffffff8124914b-ffffffff81249163: delayed_ref_ctr_inc.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1328
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff81250f60-ffffffff81251031: delayed_ref_ctr_inc.isra.0 (STB_LOCAL)
ffffffff81be6886-ffffffff81be689e: delayed_ref_ctr_inc.isra.0.cold (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff81256669)
Location: kernel/events/uprobes.c:1326
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff8129234e)
Location: kernel/events/uprobes.c:1327
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff812e7c04)
Location: kernel/events/uprobes.c:1322
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff813518eb)
Location: kernel/events/uprobes.c:1326
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff81382b6a)
Location: kernel/events/uprobes.c:1323
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff813abf3a)
Location: kernel/events/uprobes.c:1323
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffff8000102a7090)
Location: kernel/events/uprobes.c:1329
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (c04d61f4)
Location: kernel/events/uprobes.c:1329
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (c00000000035a420)
Location: kernel/events/uprobes.c:1329
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81213f1f)
Location: kernel/events/uprobes.c:1329
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff81206c8f)
Location: kernel/events/uprobes.c:1329
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff81211cbf)
Location: kernel/events/uprobes.c:1329
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff81220c0d)
Location: kernel/events/uprobes.c:1329
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
</details>
</li>
</ul>

## Differences
