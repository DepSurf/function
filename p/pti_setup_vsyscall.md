# Function: <code>pti_setup_vsyscall</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff826c57c2)
Location: arch/x86/mm/pti.c:250
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff826ef8bf)
Location: arch/x86/mm/pti.c:274
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828a6679)
Location: arch/x86/mm/pti.c:284
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828bec55)
Location: arch/x86/mm/pti.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828c514f)
Location: arch/x86/mm/pti.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pti_setup_vsyscall();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff82ce81c8)
Location: arch/x86/mm/pti.c:278
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff82ce81c8-ffffffff82ce8257: pti_setup_vsyscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pti_setup_vsyscall();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff82fd5be7)
Location: arch/x86/mm/pti.c:277
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff82fd5be7-ffffffff82fd5c76: pti_setup_vsyscall (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff831e0861)
Location: arch/x86/mm/pti.c:277
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff832c3f3f)
Location: arch/x86/mm/pti.c:277
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff83476855)
Location: arch/x86/mm/pti.c:277
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff83e9f899)
Location: arch/x86/mm/pti.c:277
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff836c3a29)
Location: arch/x86/mm/pti.c:277
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff838f4619)
Location: arch/x86/mm/pti.c:277
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff828b00e7)
Location: arch/x86/mm/pti.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828a82d4)
Location: arch/x86/mm/pti.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828c2fe6)
Location: arch/x86/mm/pti.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828c616f)
Location: arch/x86/mm/pti.c:278
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
