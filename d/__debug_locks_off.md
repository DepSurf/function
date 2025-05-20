# Function: <code>__debug_locks_off</code>

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
In kernel/panic.c (ffffffff81080bbd)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff813f87b1)
Location: include/linux/debug_locks.h:14
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
In kernel/panic.c (ffffffff810829ed)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff8143f641)
Location: include/linux/debug_locks.h:14
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
In kernel/panic.c (ffffffff8108744d)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff8145c741)
Location: include/linux/debug_locks.h:14
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
In kernel/panic.c (ffffffff810842dd)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff81461971)
Location: include/linux/debug_locks.h:14
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
In kernel/panic.c (ffffffff8108abdd)
Location: include/linux/debug_locks.h:15
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff8148d871)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffff8108e45d)
Location: include/linux/debug_locks.h:15
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff814c25f0)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffff810966ed)
Location: include/linux/debug_locks.h:15
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff814d6c9a)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffff8109ae1d)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffff81502ada)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffff810a133d)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffff81520a7a)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffff810a8254)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffff81bbfaca)
Location: include/linux/debug_locks.h:15
Inline: True
Inline callers:
  - lib/debug_locks.c:debug_locks_off
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
In kernel/panic.c (ffffffff810a3fa4)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffff81c38a8a)
Location: include/linux/debug_locks.h:15
Inline: True
Inline callers:
  - lib/debug_locks.c:debug_locks_off
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
In kernel/panic.c (ffffffff810a4bf4)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffff815a78ea)
Location: include/linux/debug_locks.h:15
Inline: True
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
In kernel/panic.c (ffffffff810b6414)
Location: include/linux/debug_locks.h:14
Inline: True
```
```
In lib/debug_locks.c (ffffffff8161082a)
Location: include/linux/debug_locks.h:14
Inline: True
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
In kernel/panic.c (ffffffff810cc99e)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff816dcd1a)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - lib/debug_locks.c:debug_locks_off
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
In kernel/panic.c (ffffffff810ea78a)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff817ccb1a)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - lib/debug_locks.c:debug_locks_off
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
In kernel/panic.c (ffffffff810f636a)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff8180af2a)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - lib/debug_locks.c:debug_locks_off
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
In kernel/panic.c (ffffffff810ff71a)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffffffff8185170a)
Location: include/linux/debug_locks.h:14
Inline: True
Inline callers:
  - lib/debug_locks.c:debug_locks_off
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
In kernel/panic.c (ffff8000100f61d4)
Location: include/linux/debug_locks.h:15
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In lib/debug_locks.c (ffff800010629fc8)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (c035453c)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (c07d1294)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (c00000000013be40)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (c0000000007cbdd0)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffe0000c1f08)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffe00045aa7a)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffff8109ac5d)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffff8151905a)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffff8108969d)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffff8150935a)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffff8109ac0d)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffff815150ea)
Location: include/linux/debug_locks.h:15
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
In kernel/panic.c (ffffffff810a287d)
Location: include/linux/debug_locks.h:15
Inline: True
```
```
In lib/debug_locks.c (ffffffff8152e85a)
Location: include/linux/debug_locks.h:15
Inline: True
```
</details>
</li>
</ul>

## Differences
