# Function: <code>pages_identical</code>

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
In mm/ksm.c (ffffffff811e546c)
Location: mm/ksm.c:851
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In mm/ksm.c (ffffffff81204096)
Location: mm/ksm.c:839
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In mm/ksm.c (ffffffff8121600b)
Location: mm/ksm.c:850
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff812217fd)
Location: mm/ksm.c:1007
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff8123cb0e)
Location: mm/ksm.c:1007
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff812603ec)
Location: mm/ksm.c:1030
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff81274b2f)
Location: mm/ksm.c:1031
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff8128fa77)
Location: mm/ksm.c:1045
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121ab19)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff8129f807)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81247575)
Location: include/linux/mm.h:3174
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff812d3e77)
Location: include/linux/mm.h:3174
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81251beb)
Location: include/linux/mm.h:3197
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff812df867)
Location: include/linux/mm.h:3197
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812559d6)
Location: include/linux/mm.h:3196
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff812e8193)
Location: include/linux/mm.h:3196
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81291686)
Location: include/linux/mm.h:3259
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff813300c3)
Location: include/linux/mm.h:3259
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e6cc5)
Location: include/linux/mm.h:3394
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff813a0ab1)
Location: include/linux/mm.h:3394
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813507ae)
Location: include/linux/mm.h:3618
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff81420313)
Location: include/linux/mm.h:3618
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81381af5)
Location: include/linux/mm.h:3837
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff81454f23)
Location: include/linux/mm.h:3837
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813aad03)
Location: include/linux/mm.h:4089
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff814901e0)
Location: include/linux/mm.h:4089
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a5f10)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffff80001033eb48)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d4f0c)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (c05452dc)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000358f80)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (c00000000041b1e8)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffe0002348a8)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81213169)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff81297de7)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81205ed9)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff812899a2)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81210f09)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff81295bf7)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121fe4e)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/ksm.c (ffffffff812a5a07)
Location: include/linux/mm.h:2909
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
</ul>

## Differences
