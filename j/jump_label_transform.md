# Function: <code>jump_label_transform</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81bc0310)
Location: arch/x86/kernel/jump_label.c:87
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff81bc0310-ffffffff81bc0384: jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81c392d0)
Location: arch/x86/kernel/jump_label.c:87
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff81c392d0-ffffffff81c39344: jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81c2b720)
Location: arch/x86/kernel/jump_label.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff81c2b720-ffffffff81c2b798: jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81d49e00)
Location: arch/x86/kernel/jump_label.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff81d49e00-ffffffff81d49e6a: jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void jump_label_transform(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81f19360)
Location: arch/x86/kernel/jump_label.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff81f19360-ffffffff81f193d8: jump_label_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff820c0e60)
Location: arch/x86/kernel/jump_label.c:108
Inline: True
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff820c0e60-ffffffff820c0ecc: jump_label_transform.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff82144b10)
Location: arch/x86/kernel/jump_label.c:108
Inline: True
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff82144b10-ffffffff82144b83: jump_label_transform.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff82227230)
Location: arch/x86/kernel/jump_label.c:108
Inline: True
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff82227230-ffffffff822272a3: jump_label_transform.constprop.0 (STB_LOCAL)
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
