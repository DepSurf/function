# Function: <code>rdrand_int</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81463477)
Location: arch/x86/include/asm/archrandom.h:57
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81565566)
Location: arch/x86/include/asm/archrandom.h:57
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
In lib/random32.c (ffffffff81482713)
Location: arch/x86/include/asm/archrandom.h:57
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81591cc6)
Location: arch/x86/include/asm/archrandom.h:57
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
In lib/random32.c (ffffffff81461db3)
Location: arch/x86/include/asm/archrandom.h:57
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff815a8536)
Location: arch/x86/include/asm/archrandom.h:57
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
In lib/random32.c (ffffffff8148dc93)
Location: arch/x86/include/asm/archrandom.h:57
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff8160ee51)
Location: arch/x86/include/asm/archrandom.h:57
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
In lib/random32.c (ffffffff814c2a13)
Location: arch/x86/include/asm/archrandom.h:57
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81648951)
Location: arch/x86/include/asm/archrandom.h:57
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
In lib/random32.c (ffffffff814d70c3)
Location: arch/x86/include/asm/archrandom.h:57
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81666b71)
Location: arch/x86/include/asm/archrandom.h:57
Inline: True
Inline callers:
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
In lib/random32.c (ffffffff81502f1f)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff8169c910)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
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
In lib/random32.c (ffffffff81520ebf)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff816bf680)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
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
In lib/random32.c (ffffffff815840cf)
Location: arch/x86/include/asm/archrandom.h:34
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff817710ad)
Location: arch/x86/include/asm/archrandom.h:34
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
In drivers/char/random.c (ffffffff8178c0dd)
Location: arch/x86/include/asm/archrandom.h:34
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
In drivers/char/random.c (ffffffff8176ef4c)
Location: arch/x86/include/asm/archrandom.h:34
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
In drivers/char/random.c (ffffffff817f4728)
Location: arch/x86/include/asm/archrandom.h:34
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8151949f)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff816850d0)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
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
In lib/random32.c (ffffffff8150978f)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff81662d70)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
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
In lib/random32.c (ffffffff8151552f)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff816b34c0)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
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
In lib/random32.c (ffffffff8152ecbf)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
```
```
In drivers/char/random.c (ffffffff816cda40)
Location: arch/x86/include/asm/archrandom.h:44
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
```
</details>
</li>
</ul>

## Differences
