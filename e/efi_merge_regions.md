# Function: <code>efi_merge_regions</code>

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
In arch/x86/platform/efi/efi.c (ffffffff81f7a7bd)
Location: arch/x86/platform/efi/efi.c:605
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff81fa3079)
Location: arch/x86/platform/efi/efi.c:583
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff81fde9b8)
Location: arch/x86/platform/efi/efi.c:615
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff820bf7ae)
Location: arch/x86/platform/efi/efi.c:611
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff826c78da)
Location: arch/x86/platform/efi/efi.c:612
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff826f19e1)
Location: arch/x86/platform/efi/efi.c:612
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff828a8781)
Location: arch/x86/platform/efi/efi.c:611
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff828c07a8)
Location: arch/x86/platform/efi/efi.c:613
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff828c6c42)
Location: arch/x86/platform/efi/efi.c:637
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void efi_merge_regions();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82ce9992)
Location: arch/x86/platform/efi/efi.c:568
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff82ce9992-ffffffff82ce9a0c: efi_merge_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void efi_merge_regions();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82fd73fd)
Location: arch/x86/platform/efi/efi.c:502
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff82fd73fd-ffffffff82fd7477: efi_merge_regions (STB_LOCAL)
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
In arch/x86/platform/efi/efi.c (ffffffff831e2442)
Location: arch/x86/platform/efi/efi.c:502
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff832c5dab)
Location: arch/x86/platform/efi/efi.c:502
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff83478b80)
Location: arch/x86/platform/efi/efi.c:505
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff83ea2d9a)
Location: arch/x86/platform/efi/efi.c:530
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff836c6fea)
Location: arch/x86/platform/efi/efi.c:533
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff838f7bea)
Location: arch/x86/platform/efi/efi.c:533
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff828b1bda)
Location: arch/x86/platform/efi/efi.c:637
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff828a9d5f)
Location: arch/x86/platform/efi/efi.c:637
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff828c4ad9)
Location: arch/x86/platform/efi/efi.c:637
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff828c7c7f)
Location: arch/x86/platform/efi/efi.c:637
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
