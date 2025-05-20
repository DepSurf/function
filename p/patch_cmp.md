# Function: <code>patch_cmp</code>

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
int patch_cmp(const void *key, const void *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810394d0)
Location: arch/x86/kernel/alternative.c:944
Inline: False
```
**Symbols:**

```
ffffffff810394d0-ffffffff810394ec: patch_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int patch_cmp(const void *key, const void *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81039ca0)
Location: arch/x86/kernel/alternative.c:944
Inline: False
```
**Symbols:**

```
ffffffff81039ca0-ffffffff81039cbc: patch_cmp (STB_LOCAL)
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
In arch/x86/kernel/alternative.c (ffffffff81bbe0cd)
Location: arch/x86/kernel/alternative.c:1036
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
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
In arch/x86/kernel/alternative.c (ffffffff81c3696c)
Location: arch/x86/kernel/alternative.c:1049
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
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
In arch/x86/kernel/alternative.c (ffffffff81c28e0f)
Location: arch/x86/kernel/alternative.c:970
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
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
In arch/x86/kernel/alternative.c (ffffffff81d46f9f)
Location: arch/x86/kernel/alternative.c:970
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
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
In arch/x86/kernel/alternative.c (ffffffff81f1558c)
Location: arch/x86/kernel/alternative.c:1347
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
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
In arch/x86/kernel/alternative.c (ffffffff820bca58)
Location: arch/x86/kernel/alternative.c:1823
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
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
In arch/x86/kernel/alternative.c (ffffffff8213e2c8)
Location: arch/x86/kernel/alternative.c:2048
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
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
In arch/x86/kernel/alternative.c (ffffffff822202b8)
Location: arch/x86/kernel/alternative.c:2138
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
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
int patch_cmp(const void *key, const void *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81039e00)
Location: arch/x86/kernel/alternative.c:944
Inline: False
```
**Symbols:**

```
ffffffff81039e00-ffffffff81039e1c: patch_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int patch_cmp(const void *key, const void *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81029710)
Location: arch/x86/kernel/alternative.c:944
Inline: False
```
**Symbols:**

```
ffffffff81029710-ffffffff8102972c: patch_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int patch_cmp(const void *key, const void *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81039c60)
Location: arch/x86/kernel/alternative.c:944
Inline: False
```
**Symbols:**

```
ffffffff81039c60-ffffffff81039c7c: patch_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int patch_cmp(const void *key, const void *elt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ac60)
Location: arch/x86/kernel/alternative.c:944
Inline: False
```
**Symbols:**

```
ffffffff8103ac60-ffffffff8103ac7c: patch_cmp (STB_LOCAL)
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
