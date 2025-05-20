# Function: <code>__jump_label_set_jump_code</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __jump_label_set_jump_code(struct jump_entry *entry, enum jump_label_type type, union jump_code_union *code, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81037290)
Location: arch/x86/kernel/jump_label.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_transform
```
**Symbols:**

```
ffffffff81037290-ffffffff81037368: __jump_label_set_jump_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __jump_label_set_jump_code(struct jump_entry *entry, enum jump_label_type type, union jump_code_union *code, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81037a60)
Location: arch/x86/kernel/jump_label.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_transform
```
**Symbols:**

```
ffffffff81037a60-ffffffff81037b38: __jump_label_set_jump_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const void *__jump_label_set_jump_code(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81039960)
Location: arch/x86/kernel/jump_label.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
```
**Symbols:**

```
ffffffff81039960-ffffffff81039a48: __jump_label_set_jump_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const void *__jump_label_set_jump_code(struct jump_entry *entry, enum jump_label_type type, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff8103a190)
Location: arch/x86/kernel/jump_label.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
```
**Symbols:**

```
ffffffff8103a190-ffffffff8103a278: __jump_label_set_jump_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const void *__jump_label_set_jump_code(struct jump_entry *entry, enum jump_label_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff8103bc60)
Location: arch/x86/kernel/jump_label.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
```
**Symbols:**

```
ffffffff8103bc60-ffffffff8103bd02: __jump_label_set_jump_code (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
void __jump_label_set_jump_code(struct jump_entry *entry, enum jump_label_type type, union jump_code_union *code, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81037bc0)
Location: arch/x86/kernel/jump_label.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_transform
```
**Symbols:**

```
ffffffff81037bc0-ffffffff81037c98: __jump_label_set_jump_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __jump_label_set_jump_code(struct jump_entry *entry, enum jump_label_type type, union jump_code_union *code, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff810275a0)
Location: arch/x86/kernel/jump_label.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_transform
```
**Symbols:**

```
ffffffff810275a0-ffffffff81027678: __jump_label_set_jump_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __jump_label_set_jump_code(struct jump_entry *entry, enum jump_label_type type, union jump_code_union *code, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81037a20)
Location: arch/x86/kernel/jump_label.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_transform
```
**Symbols:**

```
ffffffff81037a20-ffffffff81037af8: __jump_label_set_jump_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __jump_label_set_jump_code(struct jump_entry *entry, enum jump_label_type type, union jump_code_union *code, int init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81038a20)
Location: arch/x86/kernel/jump_label.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_transform
```
**Symbols:**

```
ffffffff81038a20-ffffffff81038af8: __jump_label_set_jump_code (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>union jump_code_union *code</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, type, code, init</code> ➡️ <code>entry, type, init</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>const void *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int init</code>
</li>
</ul>
</details>
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
