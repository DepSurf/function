# Function: <code>vmacache_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107ee9f)
Location: include/linux/vmacache.h:13
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff811b8420)
Location: include/linux/vmacache.h:13
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_flush_all
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff8121383a)
Location: include/linux/vmacache.h:13
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080bc9)
Location: include/linux/vmacache.h:13
Inline: True
```
```
In mm/vmacache.c (ffffffff811d2774)
Location: include/linux/vmacache.h:13
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
  - mm/vmacache.c:vmacache_flush_all
```
```
In fs/exec.c (ffffffff8123a2e8)
Location: include/linux/vmacache.h:13
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810855c9)
Location: include/linux/vmacache.h:13
Inline: True
```
```
In mm/vmacache.c (ffffffff811e2634)
Location: include/linux/vmacache.h:13
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
  - mm/vmacache.c:vmacache_flush_all
```
```
In fs/exec.c (ffffffff8124d03f)
Location: include/linux/vmacache.h:13
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108248f)
Location: include/linux/vmacache.h:13
Inline: True
```
```
In mm/vmacache.c (ffffffff811ec466)
Location: include/linux/vmacache.h:13
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
  - mm/vmacache.c:vmacache_flush_all
```
```
In fs/exec.c (ffffffff81258fe1)
Location: include/linux/vmacache.h:13
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088d16)
Location: include/linux/vmacache.h:14
Inline: True
```
```
In mm/vmacache.c (ffffffff812027d6)
Location: include/linux/vmacache.h:14
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
  - mm/vmacache.c:vmacache_flush_all
```
```
In fs/exec.c (ffffffff8127b175)
Location: include/linux/vmacache.h:14
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b725)
Location: include/linux/vmacache.h:14
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In mm/vmacache.c (ffffffff81223b01)
Location: include/linux/vmacache.h:14
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff812a22e8)
Location: include/linux/vmacache.h:14
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81094848)
Location: include/linux/vmacache.h:8
Inline: True
```
```
In mm/vmacache.c (ffffffff81236b72)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff812b7449)
Location: include/linux/vmacache.h:8
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81098fc6)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff812480b1)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff812d4ed0)
Location: include/linux/vmacache.h:8
Inline: True
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
In kernel/fork.c (ffffffff8109f52b)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff81256511)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff812e6a59)
Location: include/linux/vmacache.h:8
Inline: True
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
In kernel/fork.c (ffffffff810a6657)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff81284bb1)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff8131dce2)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
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
In kernel/fork.c (ffffffff810a20c9)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff8128ee91)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff8132919f)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
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
In kernel/fork.c (ffffffff810a2ddf)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff81294511)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff8132efac)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
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
In kernel/fork.c (ffffffff810b4540)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff812d4b63)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff8137c79c)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
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
In kernel/fork.c (ffffffff810ca928)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff81333c0b)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff813fa83f)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3bc4)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffff8000102edc2c)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffff80001038ed88)
Location: include/linux/vmacache.h:8
Inline: True
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
In kernel/fork.c (c03525f8)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (c0511b34)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (c057528c)
Location: include/linux/vmacache.h:8
Inline: True
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
In kernel/fork.c (c000000000139c74)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (c0000000003b1b5c)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (c000000000485d00)
Location: include/linux/vmacache.h:8
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0496)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffe000202040)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffe00025e732)
Location: include/linux/vmacache.h:8
Inline: True
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
In kernel/fork.c (ffffffff81098e4b)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff8124eb61)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff812df039)
Location: include/linux/vmacache.h:8
Inline: True
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
In kernel/fork.c (ffffffff8108789b)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff81241b01)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff812cf13e)
Location: include/linux/vmacache.h:8
Inline: True
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
In kernel/fork.c (ffffffff81098dfb)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff8124c901)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff812dce49)
Location: include/linux/vmacache.h:8
Inline: True
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
In kernel/fork.c (ffffffff810a0a1d)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/vmacache.c (ffffffff8125c2c1)
Location: include/linux/vmacache.h:8
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
```
```
In fs/exec.c (ffffffff812edc3c)
Location: include/linux/vmacache.h:8
Inline: True
```
</details>
</li>
</ul>

## Differences
