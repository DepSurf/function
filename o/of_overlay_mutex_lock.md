# Function: <code>of_overlay_mutex_lock</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void of_overlay_mutex_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (ffff800010b783e0)
Location: drivers/of/overlay.c:108
Inline: True
Inline callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffff800010b78a58-ffff800010b78a80: of_overlay_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void of_overlay_mutex_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (c0c5a49c)
Location: drivers/of/overlay.c:108
Inline: True
Inline callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c0c5ab58-c0c5ab7c: of_overlay_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void of_overlay_mutex_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (c000000000c57ca8)
Location: drivers/of/overlay.c:108
Inline: True
Inline callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c000000000c58950-c000000000c5898c: of_overlay_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void of_overlay_mutex_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/overlay.c (ffffffe00072b382)
Location: drivers/of/overlay.c:108
Inline: True
Inline callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffffffe00072b9cc-ffffffe00072b9f6: of_overlay_mutex_lock (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
