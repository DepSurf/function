# Function: <code>vdso_addr</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff810040b8)
Location: arch/x86/entry/vdso/vma.c:56
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
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
In arch/x86/entry/vdso/vma.c (ffffffff81003fef)
Location: arch/x86/entry/vdso/vma.c:51
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
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
In arch/x86/entry/vdso/vma.c (ffffffff8100419c)
Location: arch/x86/entry/vdso/vma.c:212
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff81004072)
Location: arch/x86/entry/vdso/vma.c:217
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff810042d2)
Location: arch/x86/entry/vdso/vma.c:218
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff81004a3f)
Location: arch/x86/entry/vdso/vma.c:218
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff8100499f)
Location: arch/x86/entry/vdso/vma.c:212
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c0f)
Location: arch/x86/entry/vdso/vma.c:212
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c8f)
Location: arch/x86/entry/vdso/vma.c:212
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int vdso_addr(long unsigned int start, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810058e0)
Location: arch/x86/entry/vdso/vma.c:330
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff810058e0-ffffffff81005993: vdso_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int vdso_addr(long unsigned int start, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004710)
Location: arch/x86/entry/vdso/vma.c:312
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004710-ffffffff810047c3: vdso_addr (STB_LOCAL)
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
In arch/x86/entry/vdso/vma.c (ffffffff8100489f)
Location: arch/x86/entry/vdso/vma.c:312
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff81004ecf)
Location: arch/x86/entry/vdso/vma.c:312
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff8100441f)
Location: arch/x86/entry/vdso/vma.c:312
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff81004d76)
Location: arch/x86/entry/vdso/vma.c:288
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff81004590)
Location: arch/x86/entry/vdso/vma.c:289
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff81006ea0)
Location: arch/x86/entry/vdso/vma.c:289
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c8f)
Location: arch/x86/entry/vdso/vma.c:212
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff8100336f)
Location: arch/x86/entry/vdso/vma.c:212
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c4f)
Location: arch/x86/entry/vdso/vma.c:212
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
In arch/x86/entry/vdso/vma.c (ffffffff81004d8f)
Location: arch/x86/entry/vdso/vma.c:212
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
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
