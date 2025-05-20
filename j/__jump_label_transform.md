# Function: <code>__jump_label_transform</code>

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
In arch/x86/kernel/jump_label.c (ffffffff8103397a)
Location: arch/x86/kernel/jump_label.c:39
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
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
In arch/x86/kernel/jump_label.c (ffffffff81032c9d)
Location: arch/x86/kernel/jump_label.c:40
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
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
In arch/x86/kernel/jump_label.c (ffffffff8103291d)
Location: arch/x86/kernel/jump_label.c:40
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81030ab0)
Location: arch/x86/kernel/jump_label.c:39
Inline: True
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81030ab0-ffffffff81030bc2: __jump_label_transform.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81032cc0)
Location: arch/x86/kernel/jump_label.c:40
Inline: True
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81032cc0-ffffffff81032dd5: __jump_label_transform.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81033fd0)
Location: arch/x86/kernel/jump_label.c:40
Inline: True
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81033fd0-ffffffff810340f1: __jump_label_transform.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __jump_label_transform(struct jump_entry *entry, enum jump_label_type type, void * (*poker)(void *, const void *, size_t), int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81a1fdb0)
Location: arch/x86/kernel/jump_label.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81a1fdb0-ffffffff81a1febc: __jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81a905b0)
Location: arch/x86/kernel/jump_label.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81a905b0-ffffffff81a90642: __jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81ac7930)
Location: arch/x86/kernel/jump_label.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81ac7930-ffffffff81ac79c2: __jump_label_transform (STB_LOCAL)
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
In arch/x86/kernel/jump_label.c (ffffffff81bc0333)
Location: arch/x86/kernel/jump_label.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
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
In arch/x86/kernel/jump_label.c (ffffffff81c392f3)
Location: arch/x86/kernel/jump_label.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
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
In arch/x86/kernel/jump_label.c (ffffffff81c2b743)
Location: arch/x86/kernel/jump_label.c:57
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
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
In arch/x86/kernel/jump_label.c (ffffffff81d49e23)
Location: arch/x86/kernel/jump_label.c:83
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
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
In arch/x86/kernel/jump_label.c (ffffffff81f19383)
Location: arch/x86/kernel/jump_label.c:83
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
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
In arch/x86/kernel/jump_label.c (ffffffff820c0e7e)
Location: arch/x86/kernel/jump_label.c:83
Inline: True
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
In arch/x86/kernel/jump_label.c (ffffffff82144b2e)
Location: arch/x86/kernel/jump_label.c:83
Inline: True
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
In arch/x86/kernel/jump_label.c (ffffffff8222724e)
Location: arch/x86/kernel/jump_label.c:83
Inline: True
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81a667a0)
Location: arch/x86/kernel/jump_label.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81a667a0-ffffffff81a66832: __jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81a23260)
Location: arch/x86/kernel/jump_label.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81a23260-ffffffff81a232f2: __jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81ad2bb0)
Location: arch/x86/kernel/jump_label.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81ad2bb0-ffffffff81ad2c42: __jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81adf0b0)
Location: arch/x86/kernel/jump_label.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81adf0b0-ffffffff81adf142: __jump_label_transform (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * (*poker)(void *, const void *, size_t)</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, type, poker, init</code> ➡️ <code>entry, type, init</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
