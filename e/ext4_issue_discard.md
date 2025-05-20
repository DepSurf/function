# Function: <code>ext4_issue_discard</code>

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
In fs/ext4/mballoc.c (ffffffff812d179f)
Location: fs/ext4/mballoc.c:2761
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
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
In fs/ext4/mballoc.c (ffffffff81305744)
Location: fs/ext4/mballoc.c:2772
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
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
In fs/ext4/mballoc.c (ffffffff8131b702)
Location: fs/ext4/mballoc.c:2772
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
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
In fs/ext4/mballoc.c (ffffffff81312ae7)
Location: fs/ext4/mballoc.c:2787
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff8133729b)
Location: fs/ext4/mballoc.c:2787
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813659d6)
Location: fs/ext4/mballoc.c:2756
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff8137dd96)
Location: fs/ext4/mballoc.c:2756
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813a449f)
Location: fs/ext4/mballoc.c:2758
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813bd30f)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff81408fef)
Location: fs/ext4/mballoc.c:2899
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff8141b50f)
Location: fs/ext4/mballoc.c:3003
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff81421bb2)
Location: fs/ext4/mballoc.c:3535
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff814742f6)
Location: fs/ext4/mballoc.c:3617
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8146fa70-ffffffff8146fb38: ext4_issue_discard.constprop.0 (STB_LOCAL)
ffffffff81ccb34f-ffffffff81ccb3e7: ext4_issue_discard.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:3614
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
```
**Symbols:**

```
ffffffff814f0aa0-ffffffff814f0b8d: ext4_issue_discard.constprop.0 (STB_LOCAL)
ffffffff81e7e57c-ffffffff81e7e614: ext4_issue_discard.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:3584
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
```
**Symbols:**

```
ffffffff8158aed0-ffffffff8158afbd: ext4_issue_discard.constprop.0 (STB_LOCAL)
ffffffff8206ea22-ffffffff8206eaba: ext4_issue_discard.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:3807
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
```
**Symbols:**

```
ffffffff815c1e70-ffffffff815c1f57: ext4_issue_discard.constprop.0 (STB_LOCAL)
ffffffff820ee8ad-ffffffff820ee942: ext4_issue_discard.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:3831
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
```
**Symbols:**

```
ffffffff815fa9a0-ffffffff815faa87: ext4_issue_discard.constprop.0 (STB_LOCAL)
ffffffff821cba18-ffffffff821cbaad: ext4_issue_discard.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffff800010493fe4)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (c0655664)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (c0000000005bcfe4)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffe0003189b8)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813b58ef)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813a637f)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813b314f)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813c7c96)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
</details>
</li>
</ul>

## Differences
