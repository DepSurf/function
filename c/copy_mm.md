# Function: <code>copy_mm</code>

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
In kernel/fork.c (ffffffff8107ee31)
Location: kernel/fork.c:953
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff81080b5b)
Location: kernel/fork.c:1009
Inline: True
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
In kernel/fork.c (ffffffff81085562)
Location: kernel/fork.c:1163
Inline: True
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
In kernel/fork.c (ffffffff81082426)
Location: kernel/fork.c:1210
Inline: True
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
In kernel/fork.c (ffffffff81088cb4)
Location: kernel/fork.c:1222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_mm(long unsigned int clone_flags, struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b690)
Location: kernel/fork.c:1291
Inline: False
```
**Symbols:**

```
ffffffff8108b690-ffffffff8108bd0d: copy_mm (STB_LOCAL)
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
In kernel/fork.c (ffffffff810947db)
Location: kernel/fork.c:1347
Inline: True
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
In kernel/fork.c (ffffffff81098f51)
Location: kernel/fork.c:1374
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff8109f4b6)
Location: kernel/fork.c:1385
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810a65ea)
Location: kernel/fork.c:1399
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810a205c)
Location: kernel/fork.c:1396
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810a2d72)
Location: kernel/fork.c:1402
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810b44d3)
Location: kernel/fork.c:1481
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810ca8d9)
Location: kernel/fork.c:1552
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810e7f09)
Location: kernel/fork.c:1575
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810f3b4e)
Location: kernel/fork.c:1716
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810fcf1f)
Location: kernel/fork.c:1712
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffff8000100f3ba0)
Location: kernel/fork.c:1385
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (c03525b8)
Location: kernel/fork.c:1385
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (c000000000139c40)
Location: kernel/fork.c:1385
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffe0000c0470)
Location: kernel/fork.c:1385
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff81098dd6)
Location: kernel/fork.c:1385
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff81087826)
Location: kernel/fork.c:1385
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff81098d86)
Location: kernel/fork.c:1385
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810a09a8)
Location: kernel/fork.c:1385
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
