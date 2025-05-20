# Function: <code>seq_puts_memcg_tunable</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812af4ce)
Location: mm/memcontrol.c:5718
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
ffffffff812af350-ffffffff812af36e: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812c0f2e)
Location: mm/memcontrol.c:6058
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
ffffffff812c0db0-ffffffff812c0dce: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812f63ee)
Location: mm/memcontrol.c:5965
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_min_show
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
In mm/memcontrol.c (ffffffff813016de)
Location: mm/memcontrol.c:6181
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_min_show
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
In mm/memcontrol.c (ffffffff81307ece)
Location: mm/memcontrol.c:6003
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_min_show
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
In mm/memcontrol.c (ffffffff8135211e)
Location: mm/memcontrol.c:6187
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_min_show
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
In mm/memcontrol.c (ffffffff813c9a8d)
Location: mm/memcontrol.c:6133
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_min_show
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
In mm/memcontrol.c (ffffffff8144fe4d)
Location: mm/memcontrol.c:6320
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_min_show
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
In mm/memcontrol.c (ffffffff8148575d)
Location: mm/memcontrol.c:6386
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_min_show
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
In mm/memcontrol.c (ffffffff814b48bd)
Location: mm/memcontrol.c:6674
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_min_show
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
In mm/memcontrol.c (ffff800010362374)
Location: mm/memcontrol.c:6058
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
ffff800010362170-ffff8000103621ac: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (c0554cdc)
Location: mm/memcontrol.c:6058
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
c0554b48-c0554b78: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (c00000000044f29c)
Location: mm/memcontrol.c:6058
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
c00000000044ef90-c00000000044efd4: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffe000241bd0)
Location: mm/memcontrol.c:6058
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
ffffffe0002419f0-ffffffe000241a2c: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812b950e)
Location: mm/memcontrol.c:6058
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
ffffffff812b9390-ffffffff812b93ae: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812aa79e)
Location: mm/memcontrol.c:6058
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
ffffffff812aa620-ffffffff812aa63e: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812b731e)
Location: mm/memcontrol.c:6058
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
ffffffff812b71a0-ffffffff812b71be: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff812c7bfe)
Location: mm/memcontrol.c:6058
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
Direct callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
```
**Symbols:**

```
ffffffff812c7a80-ffffffff812c7a9e: seq_puts_memcg_tunable.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
