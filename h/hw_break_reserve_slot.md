# Function: <code>hw_break_reserve_slot</code>

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
In arch/x86/kernel/kgdb.c (ffffffff81060f99)
Location: arch/x86/kernel/kgdb.c:242
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff81060dc0)
Location: arch/x86/kernel/kgdb.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff81063e60)
Location: arch/x86/kernel/kgdb.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff81062dc1)
Location: arch/x86/kernel/kgdb.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff81066f4e)
Location: arch/x86/kernel/kgdb.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff81069b61)
Location: arch/x86/kernel/kgdb.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff8106f8f1)
Location: arch/x86/kernel/kgdb.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff810739dc)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff8107499c)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hw_break_reserve_slot(int breakno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8107b930)
Location: arch/x86/kernel/kgdb.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
```
**Symbols:**

```
ffffffff8107b930-ffffffff8107ba03: hw_break_reserve_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hw_break_reserve_slot(int breakno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8107b820)
Location: arch/x86/kernel/kgdb.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
```
**Symbols:**

```
ffffffff8107b820-ffffffff8107b8f3: hw_break_reserve_slot (STB_LOCAL)
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
In arch/x86/kernel/kgdb.c (ffffffff8107cac7)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff8108ac5c)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff8109bc0b)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff810b291b)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff810b5a24)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff810bce64)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff8107399c)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff810638cc)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff8107394c)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
In arch/x86/kernel/kgdb.c (ffffffff810759ac)
Location: arch/x86/kernel/kgdb.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
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
</ul>
