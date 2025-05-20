# Function: <code>arch_jump_entry_size</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_jump_entry_size(struct jump_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81041690)
Location: arch/x86/kernel/jump_label.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81041690-ffffffff810416f9: arch_jump_entry_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_jump_entry_size(struct jump_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81049320)
Location: arch/x86/kernel/jump_label.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81049320-ffffffff81049395: arch_jump_entry_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_jump_entry_size(struct jump_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81054340)
Location: arch/x86/kernel/jump_label.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81054340-ffffffff810543b5: arch_jump_entry_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_jump_entry_size(struct jump_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff810553a0)
Location: arch/x86/kernel/jump_label.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff810553a0-ffffffff81055415: arch_jump_entry_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_jump_entry_size(struct jump_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff8105c610)
Location: arch/x86/kernel/jump_label.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff8105c610-ffffffff8105c685: arch_jump_entry_size (STB_GLOBAL)
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
