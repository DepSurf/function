# Function: <code>arch_get_random_seed_int</code>

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
In lib/random32.c (ffffffff8141b287)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff8146345d)
Location: arch/x86/include/asm/archrandom.h:115
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff814826f9)
Location: arch/x86/include/asm/archrandom.h:115
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff81461d94)
Location: arch/x86/include/asm/archrandom.h:115
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff8148dc74)
Location: arch/x86/include/asm/archrandom.h:115
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff814c29f0)
Location: arch/x86/include/asm/archrandom.h:115
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff814d70a0)
Location: arch/x86/include/asm/archrandom.h:115
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff81502f00)
Location: arch/x86/include/asm/archrandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff81520ea0)
Location: arch/x86/include/asm/archrandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff815840b0)
Location: arch/x86/include/asm/archrandom.h:88
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (0)
Location: include/linux/random.h:186
Inline: True
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
In lib/random32.c (0)
Location: include/linux/random.h:186
Inline: True
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
In lib/random32.c (c0000000013a0168)
Location: arch/powerpc/include/asm/archrandom.h:26
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
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
In lib/random32.c (0)
Location: include/linux/random.h:186
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
In lib/random32.c (ffffffff81519480)
Location: arch/x86/include/asm/archrandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff81509770)
Location: arch/x86/include/asm/archrandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff81515510)
Location: arch/x86/include/asm/archrandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
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
In lib/random32.c (ffffffff8152eca0)
Location: arch/x86/include/asm/archrandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
</details>
</li>
</ul>

## Differences
