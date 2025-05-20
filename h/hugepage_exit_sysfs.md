# Function: <code>hugepage_exit_sysfs</code>

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
In mm/huge_memory.c (ffffffff81f8d697)
Location: mm/huge_memory.c:603
Inline: True
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
In mm/huge_memory.c (ffffffff81fb775b)
Location: mm/huge_memory.c:334
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
In mm/huge_memory.c (ffffffff81ff40d4)
Location: mm/huge_memory.c:364
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
In mm/huge_memory.c (ffffffff820d68b1)
Location: mm/huge_memory.c:366
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
In mm/huge_memory.c (ffffffff826df51f)
Location: mm/huge_memory.c:366
Inline: True
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
In mm/huge_memory.c (ffffffff82709944)
Location: mm/huge_memory.c:366
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828c0b28)
Location: mm/huge_memory.c:376
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828d9eb4)
Location: mm/huge_memory.c:381
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828e235b)
Location: mm/huge_memory.c:373
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff82cff735)
Location: mm/huge_memory.c:373
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff82fec0e1)
Location: mm/huge_memory.c:366
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff831f6940)
Location: mm/huge_memory.c:379
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff832dd456)
Location: mm/huge_memory.c:379
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff83492c85)
Location: mm/huge_memory.c:378
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff83ec6aef)
Location: mm/huge_memory.c:439
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff836ebadf)
Location: mm/huge_memory.c:440
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hugepage_exit_sysfs(struct kobject *hugepage_kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8391e680)
Location: mm/huge_memory.c:617
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init_sysfs
```
**Symbols:**

```
ffffffff8391e680-ffffffff8391e72d: hugepage_exit_sysfs (STB_LOCAL)
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
In mm/huge_memory.c (ffff80001145b520)
Location: mm/huge_memory.c:373
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000001385c7c)
Location: mm/huge_memory.c:373
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/huge_memory.c (ffffffff828cb20f)
Location: mm/huge_memory.c:373
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828c3934)
Location: mm/huge_memory.c:373
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828ddf8f)
Location: mm/huge_memory.c:373
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828e33a6)
Location: mm/huge_memory.c:373
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
