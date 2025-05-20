# Function: <code>is_child_reaper</code>

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
In kernel/fork.c (ffffffff8107f31a)
Location: include/linux/pid.h:148
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff8109e274)
Location: include/linux/pid.h:148
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff810814d0)
Location: include/linux/pid.h:148
Inline: True
```
```
In kernel/pid.c (ffffffff810a1922)
Location: include/linux/pid.h:148
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff81085f1c)
Location: include/linux/pid.h:148
Inline: True
```
```
In kernel/pid.c (ffffffff810a69e2)
Location: include/linux/pid.h:148
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff81082946)
Location: include/linux/pid.h:150
Inline: True
```
```
In kernel/sys.c (ffffffff81097772)
Location: include/linux/pid.h:150
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810a3945)
Location: include/linux/pid.h:150
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (0)
Location: include/linux/pid.h:149
Inline: True
```
```
In kernel/sys.c (ffffffff8109e462)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810aa10e)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff8108d130)
Location: include/linux/pid.h:149
Inline: True
```
```
In kernel/sys.c (ffffffff810a2f42)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810b0d3c)
Location: include/linux/pid.h:149
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff81094e64)
Location: include/linux/pid.h:142
Inline: True
```
```
In kernel/sys.c (ffffffff810abb42)
Location: include/linux/pid.h:142
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810b9e33)
Location: include/linux/pid.h:142
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff810994bf)
Location: include/linux/pid.h:147
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b10a2)
Location: include/linux/pid.h:147
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810bfd25)
Location: include/linux/pid.h:147
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff8109fab9)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b7772)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810c60f5)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff810a6b59)
Location: include/linux/pid.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bf6c2)
Location: include/linux/pid.h:162
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
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
In kernel/fork.c (ffffffff810a266b)
Location: include/linux/pid.h:163
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810ba872)
Location: include/linux/pid.h:163
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
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
In kernel/fork.c (ffffffff810a335e)
Location: include/linux/pid.h:163
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bc1a2)
Location: include/linux/pid.h:163
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
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
In kernel/fork.c (ffffffff810b4ae9)
Location: include/linux/pid.h:164
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810ceb92)
Location: include/linux/pid.h:164
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
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
In kernel/fork.c (ffffffff810cafb5)
Location: include/linux/pid.h:165
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810e6d04)
Location: include/linux/pid.h:165
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
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
In kernel/fork.c (ffffffff810e8562)
Location: include/linux/pid.h:165
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff811078a4)
Location: include/linux/pid.h:165
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
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
In kernel/fork.c (ffffffff810f41c1)
Location: include/linux/pid.h:166
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff81113b94)
Location: include/linux/pid.h:166
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
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
In kernel/fork.c (ffffffff810fd583)
Location: include/linux/pid.h:157
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff8111d584)
Location: include/linux/pid.h:157
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
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
In kernel/fork.c (ffff8000100f4044)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffff8000101140bc)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffff800010124728)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (c0352ac8)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (c036ab2c)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (c03778f4)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (c00000000013a410)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (c00000000015b9ac)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (c00000000016e570)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffe0000c0816)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffe0000d1f84)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffe0000dc846)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff810993d9)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b1ae2)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810c0475)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff81087e29)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810a0402)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810aec79)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff81099389)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b1042)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810bf9c5)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
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
In kernel/fork.c (ffffffff810a0fc2)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b9332)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
```
```
In kernel/pid.c (ffffffff810c7df0)
Location: include/linux/pid.h:151
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
</details>
</li>
</ul>

## Differences
