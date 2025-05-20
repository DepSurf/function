# Function: <code>destroy_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void destroy_context(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032fa0)
Location: arch/x86/kernel/ldt.c:147
Inline: False
```
**Symbols:**

```
ffffffff81032fa0-ffffffff81032fda: destroy_context (STB_GLOBAL)
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
In kernel/fork.c (ffffffff8107f8f9)
Location: arch/x86/include/asm/mmu_context.h:113
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
In kernel/fork.c (ffffffff81083fd9)
Location: arch/x86/include/asm/mmu_context.h:123
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
In kernel/fork.c (ffffffff81080f29)
Location: arch/x86/include/asm/mmu_context.h:145
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
In kernel/fork.c (ffffffff81087829)
Location: arch/x86/include/asm/mmu_context.h:204
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
In kernel/fork.c (ffffffff8108a865)
Location: arch/x86/include/asm/mmu_context.h:205
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff81092805)
Location: arch/x86/include/asm/mmu_context.h:204
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff810966d7)
Location: arch/x86/include/asm/mmu_context.h:205
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff8109cda7)
Location: arch/x86/include/asm/mmu_context.h:205
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff810a39d7)
Location: arch/x86/include/asm/mmu_context.h:120
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff8109f817)
Location: arch/x86/include/asm/mmu_context.h:123
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff810a0947)
Location: arch/x86/include/asm/mmu_context.h:123
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff810b1d5d)
Location: arch/x86/include/asm/mmu_context.h:123
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff810c841d)
Location: arch/x86/include/asm/mmu_context.h:123
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff810e567f)
Location: arch/x86/include/asm/mmu_context.h:123
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff810f1694)
Location: arch/x86/include/asm/mmu_context.h:163
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff810faa58)
Location: arch/x86/include/asm/mmu_context.h:163
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void destroy_context(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/mmu_context.c (c0000000000904d0)
Location: arch/powerpc/mm/book3s64/mmu_context.c:254
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
c0000000000904d0-c0000000000905c8: destroy_context (STB_GLOBAL)
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
In kernel/fork.c (0)
Location: arch/riscv/include/asm/mmu_context.h:28
Inline: True
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
In kernel/fork.c (ffffffff810966c7)
Location: arch/x86/include/asm/mmu_context.h:205
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff81085147)
Location: arch/x86/include/asm/mmu_context.h:205
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff81096677)
Location: arch/x86/include/asm/mmu_context.h:205
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffff8109e257)
Location: arch/x86/include/asm/mmu_context.h:205
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
