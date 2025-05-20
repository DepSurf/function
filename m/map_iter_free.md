# Function: <code>map_iter_free</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811c038d)
Location: kernel/bpf/inode.c:168
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff811c0350-ffffffff811c0370: map_iter_free.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811d17ed)
Location: kernel/bpf/inode.c:168
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff811d17b0-ffffffff811d17d0: map_iter_free.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e5b2e)
Location: kernel/bpf/inode.c:165
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff811e5ae0-ffffffff811e5b02: map_iter_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f236e)
Location: kernel/bpf/inode.c:166
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff811f2320-ffffffff811f2342: map_iter_free.part.0 (STB_LOCAL)
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
In kernel/bpf/inode.c (ffffffff81214170)
Location: kernel/bpf/inode.c:187
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:map_iter_alloc
  - kernel/bpf/inode.c:map_iter_alloc
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
In kernel/bpf/inode.c (ffffffff812159b0)
Location: kernel/bpf/inode.c:188
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:map_iter_alloc
  - kernel/bpf/inode.c:map_iter_alloc
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
In kernel/bpf/inode.c (ffffffff812185a0)
Location: kernel/bpf/inode.c:189
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:map_iter_alloc
  - kernel/bpf/inode.c:map_iter_alloc
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
In kernel/bpf/inode.c (ffffffff8124ebd0)
Location: kernel/bpf/inode.c:189
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:map_iter_alloc
  - kernel/bpf/inode.c:map_iter_alloc
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
In kernel/bpf/inode.c (ffffffff81295c7f)
Location: kernel/bpf/inode.c:189
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff812f0aaf)
Location: kernel/bpf/inode.c:189
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff8131d63f)
Location: kernel/bpf/inode.c:189
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
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
In kernel/bpf/inode.c (ffffffff8133f99f)
Location: kernel/bpf/inode.c:186
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffff80001027588c)
Location: kernel/bpf/inode.c:166
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffff800010275830-ffff800010275864: map_iter_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (c04a7fe4)
Location: kernel/bpf/inode.c:166
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
c04a7f94-c04a7fc0: map_iter_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (c00000000031d96c)
Location: kernel/bpf/inode.c:166
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
c00000000031d8f0-c00000000031d940: map_iter_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffe0001adf48)
Location: kernel/bpf/inode.c:166
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffe0001adef6-ffffffe0001adf2a: map_iter_free.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811ea98e)
Location: kernel/bpf/inode.c:166
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff811ea940-ffffffff811ea962: map_iter_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811dd74e)
Location: kernel/bpf/inode.c:166
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff811dd700-ffffffff811dd722: map_iter_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e875e)
Location: kernel/bpf/inode.c:166
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff811e8710-ffffffff811e8732: map_iter_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f6b0e)
Location: kernel/bpf/inode.c:166
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
Direct callers:
  - kernel/bpf/inode.c:bpffs_map_release
  - kernel/bpf/inode.c:bpffs_map_open
  - kernel/bpf/inode.c:bpffs_map_open
```
**Symbols:**

```
ffffffff811f6ac0-ffffffff811f6ae2: map_iter_free.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
