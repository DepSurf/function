# Function: <code>swap_ra_info</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812483f4)
Location: mm/swap_state.c:664
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (ffffffff8125c9c4)
Location: mm/swap_state.c:626
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (ffffffff81277ba9)
Location: mm/swap_state.c:640
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (ffffffff81287699)
Location: mm/swap_state.c:640
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swap_ra_info(struct vm_fault *vmf, struct vma_swap_readahead *ra_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b8880)
Location: mm/swap_state.c:658
Inline: False
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
```
**Symbols:**

```
ffffffff812b8880-ffffffff812b8ade: swap_ra_info (STB_LOCAL)
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
In mm/swap_state.c (ffffffff812c4000)
Location: mm/swap_state.c:750
Inline: True
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
```
**Symbols:**

```
ffffffff812c4000-ffffffff812c425e: swap_ra_info.constprop.0 (STB_LOCAL)
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
In mm/swap_state.c (ffffffff812cadf0)
Location: mm/swap_state.c:719
Inline: True
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
```
**Symbols:**

```
ffffffff812cadf0-ffffffff812cb03e: swap_ra_info.constprop.0 (STB_LOCAL)
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
In mm/swap_state.c (ffffffff8130fe00)
Location: mm/swap_state.c:712
Inline: True
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
```
**Symbols:**

```
ffffffff8130fe00-ffffffff8130fffb: swap_ra_info.constprop.0 (STB_LOCAL)
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
In mm/swap_state.c (ffffffff8137a7e0)
Location: mm/swap_state.c:725
Inline: True
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
```
**Symbols:**

```
ffffffff8137a7e0-ffffffff8137aa06: swap_ra_info.constprop.0 (STB_LOCAL)
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
In mm/swap_state.c (ffffffff813f82f0)
Location: mm/swap_state.c:709
Inline: True
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
```
**Symbols:**

```
ffffffff813f82f0-ffffffff813f8526: swap_ra_info.constprop.0 (STB_LOCAL)
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
In mm/swap_state.c (ffffffff8142c633)
Location: mm/swap_state.c:719
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
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
In mm/swap_state.c (ffffffff81465d66)
Location: mm/swap_state.c:733
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
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
In mm/swap_state.c (ffff800010322214)
Location: mm/swap_state.c:640
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (c053a8a4)
Location: mm/swap_state.c:640
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (c0000000003f7c28)
Location: mm/swap_state.c:640
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (ffffffe000223222)
Location: mm/swap_state.c:640
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (ffffffff8127fc62)
Location: mm/swap_state.c:599
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (ffffffff81271adb)
Location: mm/swap_state.c:640
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (ffffffff8127da89)
Location: mm/swap_state.c:640
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
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
In mm/swap_state.c (ffffffff8128d639)
Location: mm/swap_state.c:640
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
