# Function: <code>update_ref_ctr_warn</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f794c)
Location: kernel/events/uprobes.c:416
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (ffffffff8120f766)
Location: kernel/events/uprobes.c:404
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (ffffffff8121cda9)
Location: kernel/events/uprobes.c:413
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_ref_ctr_warn(struct uprobe *uprobe, struct mm_struct *mm, short int d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81249068)
Location: kernel/events/uprobes.c:407
Inline: False
Direct callers:
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81249068-ffffffff812490b4: update_ref_ctr_warn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_ref_ctr_warn(struct uprobe *uprobe, struct mm_struct *mm, short int d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81be67a3)
Location: kernel/events/uprobes.c:407
Inline: False
Direct callers:
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81be67a3-ffffffff81be67ef: update_ref_ctr_warn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_ref_ctr_warn(struct uprobe *uprobe, struct mm_struct *mm, short int d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81bd84a4)
Location: kernel/events/uprobes.c:407
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81bd84a4-ffffffff81bd84f0: update_ref_ctr_warn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_ref_ctr_warn(struct uprobe *uprobe, struct mm_struct *mm, short int d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81cb99cb)
Location: kernel/events/uprobes.c:407
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81cb99cb-ffffffff81cb9a17: update_ref_ctr_warn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_ref_ctr_warn(struct uprobe *uprobe, struct mm_struct *mm, short int d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81e6afa3)
Location: kernel/events/uprobes.c:401
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81e6afa3-ffffffff81e6b001: update_ref_ctr_warn (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff813519fd)
Location: kernel/events/uprobes.c:404
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (ffffffff81382c88)
Location: kernel/events/uprobes.c:402
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (ffffffff813ac058)
Location: kernel/events/uprobes.c:402
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (ffff8000102a7238)
Location: kernel/events/uprobes.c:413
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (c04d6388)
Location: kernel/events/uprobes.c:413
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (c00000000035a634)
Location: kernel/events/uprobes.c:413
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (ffffffff812153f9)
Location: kernel/events/uprobes.c:413
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (ffffffff81208159)
Location: kernel/events/uprobes.c:413
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (ffffffff81213199)
Location: kernel/events/uprobes.c:413
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
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
In kernel/events/uprobes.c (ffffffff81222137)
Location: kernel/events/uprobes.c:413
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:update_ref_ctr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
