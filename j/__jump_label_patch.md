# Function: <code>__jump_label_patch</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct jump_label_patch __jump_label_patch(struct jump_entry *entry, enum jump_label_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/kernel/jump_label.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
```
**Symbols:**

```
ffffffff81041700-ffffffff810417ec: __jump_label_patch (STB_LOCAL)
ffffffff81c98f93-ffffffff81c98fb9: __jump_label_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct jump_label_patch __jump_label_patch(struct jump_entry *entry, enum jump_label_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/kernel/jump_label.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
```
**Symbols:**

```
ffffffff810493a0-ffffffff810494a9: __jump_label_patch (STB_LOCAL)
ffffffff81e4854d-ffffffff81e48573: __jump_label_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct jump_label_patch __jump_label_patch(struct jump_entry *entry, enum jump_label_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff810543d0)
Location: arch/x86/kernel/jump_label.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff810543d0-ffffffff810544fb: __jump_label_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct jump_label_patch __jump_label_patch(struct jump_entry *entry, enum jump_label_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81055430)
Location: arch/x86/kernel/jump_label.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff81055430-ffffffff8105555b: __jump_label_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct jump_label_patch __jump_label_patch(struct jump_entry *entry, enum jump_label_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff8105c6a0)
Location: arch/x86/kernel/jump_label.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
```
**Symbols:**

```
ffffffff8105c6a0-ffffffff8105c7cb: __jump_label_patch (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
