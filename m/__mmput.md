# Function: <code>__mmput</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107fc66)
Location: kernel/fork.c:710
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff81084436)
Location: kernel/fork.c:862
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff810813a6)
Location: kernel/fork.c:909
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff81087c96)
Location: kernel/fork.c:920
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff8108b172)
Location: kernel/fork.c:989
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff81092f12)
Location: kernel/fork.c:1044
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff81097052)
Location: kernel/fork.c:1061
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff8109d752)
Location: kernel/fork.c:1076
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff810a4912)
Location: kernel/fork.c:1090
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff810a0022)
Location: kernel/fork.c:1087
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff810a0de2)
Location: kernel/fork.c:1093
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff810b22c2)
Location: kernel/fork.c:1112
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff810c86f2)
Location: kernel/fork.c:1184
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mmput(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e58c0)
Location: kernel/fork.c:1204
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/fork.c:mmput_async_fn
```
**Symbols:**

```
ffffffff810e58c0-ffffffff810e59f1: __mmput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mmput(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f0f30)
Location: kernel/fork.c:1345
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/fork.c:mmput_async_fn
```
**Symbols:**

```
ffffffff810f0f30-ffffffff810f1070: __mmput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mmput(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fa300)
Location: kernel/fork.c:1340
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/fork.c:mmput_async_fn
```
**Symbols:**

```
ffffffff810fa300-ffffffff810fa440: __mmput (STB_LOCAL)
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
In kernel/fork.c (ffff8000100f1ea0)
Location: kernel/fork.c:1076
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (c0350dec)
Location: kernel/fork.c:1076
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (c000000000137cd8)
Location: kernel/fork.c:1076
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffe0000c0e2e)
Location: kernel/fork.c:1076
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/fork.c:mmput_async_fn
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
In kernel/fork.c (ffffffff81097072)
Location: kernel/fork.c:1076
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff81085af2)
Location: kernel/fork.c:1076
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff81097022)
Location: kernel/fork.c:1076
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
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
In kernel/fork.c (ffffffff8109ee22)
Location: kernel/fork.c:1076
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
