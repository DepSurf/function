# Function: <code>set_mount_attributes</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812d3280)
Location: fs/namespace.c:2275
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812d3280-ffffffff812d32de: set_mount_attributes.isra.41 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812f0440)
Location: fs/namespace.c:2466
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812f0440-ffffffff812f049e: set_mount_attributes.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff81301fe0)
Location: fs/namespace.c:2469
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff81301fe0-ffffffff8130203e: set_mount_attributes.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff8133c0b9)
Location: fs/namespace.c:2527
Inline: True
Inline callers:
  - fs/namespace.c:do_reconfigure_mnt
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
In fs/namespace.c (ffffffff81347f59)
Location: fs/namespace.c:2533
Inline: True
Inline callers:
  - fs/namespace.c:do_reconfigure_mnt
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
In fs/namespace.c (ffffffff81352bbe)
Location: fs/namespace.c:2559
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff813a0fec)
Location: fs/namespace.c:2561
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff8142497a)
Location: fs/namespace.c:2602
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff814b10b3)
Location: fs/namespace.c:2707
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff814e60f3)
Location: fs/namespace.c:2785
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffffffff81519f26)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
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
In fs/namespace.c (ffff8000103b4e48)
Location: fs/namespace.c:2469
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffff8000103b4e48-ffff8000103b4f24: set_mount_attributes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_mount_attributes(struct mount *mnt, unsigned int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0593b10)
Location: fs/namespace.c:2469
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c0593b10-c0593b98: set_mount_attributes (STB_LOCAL)
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
In fs/namespace.c (c0000000004b13c0)
Location: fs/namespace.c:2469
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c0000000004b13c0-c0000000004b14e4: set_mount_attributes.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffe000277f5a)
Location: fs/namespace.c:2469
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffe000277f5a-ffffffe000278018: set_mount_attributes.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812fa5c0)
Location: fs/namespace.c:2469
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812fa5c0-ffffffff812fa61e: set_mount_attributes.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812eb1e0)
Location: fs/namespace.c:2469
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812eb1e0-ffffffff812eb23e: set_mount_attributes.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812f83b0)
Location: fs/namespace.c:2469
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812f83b0-ffffffff812f840e: set_mount_attributes.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff81309fd0)
Location: fs/namespace.c:2469
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff81309fd0-ffffffff8130a02c: set_mount_attributes.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
