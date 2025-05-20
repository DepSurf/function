# Function: <code>vga_switchoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81540fa0)
Location: drivers/gpu/vga/vga_switcheroo.c:488
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
```
**Symbols:**

```
ffffffff81540fa0-ffffffff81540fd9: vga_switchoff.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8164223c)
Location: drivers/gpu/vga/vga_switcheroo.c:625
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81641f20-ffffffff81641f59: vga_switchoff.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8167331c)
Location: drivers/gpu/vga/vga_switcheroo.c:625
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81673000-ffffffff81673039: vga_switchoff.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vga_switchoff(struct vga_switcheroo_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81686c40)
Location: drivers/gpu/vga/vga_switcheroo.c:626
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81686c40-ffffffff81686c84: vga_switchoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vga_switchoff(struct vga_switcheroo_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816f04a0)
Location: drivers/gpu/vga/vga_switcheroo.c:626
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff816f04a0-ffffffff816f04ed: vga_switchoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8172dbb7)
Location: drivers/gpu/vga/vga_switcheroo.c:680
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff8172d750-ffffffff8172d792: vga_switchoff.part.7 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81750335)
Location: drivers/gpu/vga/vga_switcheroo.c:685
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff8174fef0-ffffffff8174ff32: vga_switchoff.part.7 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8178c34a)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff8178bce0-ffffffff8178bd22: vga_switchoff.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817afcaa)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff817af900-ffffffff817af942: vga_switchoff.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81875fdd)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81875730-ffffffff81875775: vga_switchoff.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff818848bd)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81884010-ffffffff81884055: vga_switchoff.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8186713a)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81866890-ffffffff818668d5: vga_switchoff.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff818f6344)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff818f6320-ffffffff818f637b: vga_switchoff.isra.0 (STB_LOCAL)
ffffffff81d0f59f-ffffffff81d0f5b4: vga_switchoff.isra.0.cold (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81a46e64)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81a46e40-ffffffff81a46ea5: vga_switchoff.isra.0 (STB_LOCAL)
ffffffff81eda1b8-ffffffff81eda1cd: vga_switchoff.isra.0.cold (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81bcde14)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81bcddf0-ffffffff81bcde55: vga_switchoff.isra.0 (STB_LOCAL)
ffffffff8209cd15-ffffffff8209cd2a: vga_switchoff.isra.0.cold (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81c25a04)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81c259e0-ffffffff81c25a45: vga_switchoff.isra.0 (STB_LOCAL)
ffffffff8211dc20-ffffffff8211dc35: vga_switchoff.isra.0.cold (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81cd8184)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81cd8160-ffffffff81cd81c5: vga_switchoff.isra.0 (STB_LOCAL)
ffffffff821ff17d-ffffffff821ff192: vga_switchoff.isra.0.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817747da)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81774430-ffffffff81774472: vga_switchoff.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8175458a)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff817541e0-ffffffff81754222: vga_switchoff.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817a4b2a)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff817a4780-ffffffff817a47c2: vga_switchoff.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817be9aa)
Location: drivers/gpu/vga/vga_switcheroo.c:684
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_write
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff817be600-ffffffff817be642: vga_switchoff.part.0 (STB_LOCAL)
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
</ul>
