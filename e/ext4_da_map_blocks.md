# Function: <code>ext4_da_map_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81296e4f)
Location: fs/ext4/inode.c:1538
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c446f)
Location: fs/ext4/inode.c:1695
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812d9b1f)
Location: fs/ext4/inode.c:1724
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fda3f)
Location: fs/ext4/inode.c:1778
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8132221f)
Location: fs/ext4/inode.c:1786
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81351329)
Location: fs/ext4/inode.c:1789
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136a1c9)
Location: fs/ext4/inode.c:1833
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/ext4/inode.c (ffffffff813935e0)
Location: fs/ext4/inode.c:1849
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff813935e0-ffffffff81393962: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff813abf90)
Location: fs/ext4/inode.c:1825
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff813abf90-ffffffff813ac308: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff813f8380)
Location: fs/ext4/inode.c:1676
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff813f8380-ffffffff813f863d: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff8140a010)
Location: fs/ext4/inode.c:1693
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff8140a010-ffffffff8140a2e0: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff81410140)
Location: fs/ext4/inode.c:1692
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff81410140-ffffffff814104a6: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1686
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff81465740-ffffffff81465b12: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
ffffffff81ccada5-ffffffff81ccadcc: ext4_da_map_blocks.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1708
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff814e50c0-ffffffff814e54af: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
ffffffff81e7dc49-ffffffff81e7dc68: ext4_da_map_blocks.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1728
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff8157e740-ffffffff8157eb64: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
ffffffff8206e112-ffffffff8206e131: ext4_da_map_blocks.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1674
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff815b2530-ffffffff815b28fd: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
ffffffff820edaa5-ffffffff820edac4: ext4_da_map_blocks.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1686
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff815eb370-ffffffff815eb6f9: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
ffffffff821cabd4-ffffffff821cabf3: ext4_da_map_blocks.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/inode.c (ffff80001047eab0)
Location: fs/ext4/inode.c:1825
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffff80001047eab0-ffff80001047ee58: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (c063f8c8)
Location: fs/ext4/inode.c:1825
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
c063f8c8-c063fccc: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (c0000000005a2370)
Location: fs/ext4/inode.c:1825
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
c0000000005a2370-c0000000005a2818: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffe000309512)
Location: fs/ext4/inode.c:1825
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffe000309512-ffffffe000309814: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff813a4570)
Location: fs/ext4/inode.c:1825
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff813a4570-ffffffff813a48e8: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff81395000)
Location: fs/ext4/inode.c:1825
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff81395000-ffffffff81395378: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff813a1dd0)
Location: fs/ext4/inode.c:1825
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff813a1dd0-ffffffff813a2148: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff813b5250)
Location: fs/ext4/inode.c:1825
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff813b5250-ffffffff813b55c8: ext4_da_map_blocks.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
