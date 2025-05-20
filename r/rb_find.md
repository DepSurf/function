# Function: <code>rb_find</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81021c98)
Location: include/linux/rbtree.h:283
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/events/uprobes.c (ffffffff81254f10)
Location: include/linux/rbtree.h:283
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_uprobe
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff810257e8)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/events/uprobes.c (ffffffff81290950)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_uprobe
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff810297c7)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/events/uprobes.c (ffffffff812e5735)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__find_uprobe
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030237)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/events/uprobes.c (ffffffff8134f295)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__find_uprobe
```
```
In fs/xattr.c (ffffffff814b720a)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_get
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff8103030c)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/events/uprobes.c (ffffffff81380465)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__find_uprobe
```
```
In fs/xattr.c (ffffffff814ec06a)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_get
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff810365ac)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In kernel/events/uprobes.c (ffffffff813a9785)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__find_uprobe
```
```
In fs/xattr.c (ffffffff8151ff8a)
Location: include/linux/rbtree.h:256
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_get
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
