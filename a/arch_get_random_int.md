# Function: <code>arch_get_random_int</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8141b291)
Location: arch/x86/include/asm/archrandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81512bd5)
Location: arch/x86/include/asm/archrandom.h:102
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_int
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81463466)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81565555)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_int
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81482702)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81591cb5)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_int
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81461da2)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff815a8525)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8148dc82)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff8160ee40)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff814c2a02)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81648935)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff814d70b2)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81666b55)
Location: arch/x86/include/asm/archrandom.h:105
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81502f0e)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff8169c8f5)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81520eae)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff816bf665)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff815840be)
Location: arch/x86/include/asm/archrandom.h:78
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff817710a3)
Location: arch/x86/include/asm/archrandom.h:78
Inline: True
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
In drivers/char/random.c (ffffffff8178c0d3)
Location: arch/x86/include/asm/archrandom.h:78
Inline: True
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
In drivers/char/random.c (ffffffff8176ef42)
Location: arch/x86/include/asm/archrandom.h:78
Inline: True
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
In drivers/char/random.c (ffffffff817f471e)
Location: arch/x86/include/asm/archrandom.h:78
Inline: True
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (0)
Location: include/linux/random.h:174
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/random.h:174
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (0)
Location: include/linux/random.h:174
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/random.h:174
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (0)
Location: arch/powerpc/include/asm/archrandom.h:14
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/powerpc/include/asm/archrandom.h:14
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (0)
Location: include/linux/random.h:174
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/random.h:174
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8151948e)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff816850b5)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8150977e)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81662d55)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8151551e)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff816b34a5)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8152ecae)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff816cda25)
Location: arch/x86/include/asm/archrandom.h:92
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
</ul>

## Differences
