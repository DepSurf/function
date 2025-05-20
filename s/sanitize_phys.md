# Function: <code>sanitize_phys</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107b432)
Location: arch/x86/mm/pat.c:515
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
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
In arch/x86/mm/pat.c (ffffffff81081d7b)
Location: arch/x86/mm/pat.c:515
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
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
In arch/x86/mm/pat.c (ffffffff81085a0e)
Location: arch/x86/mm/pat.c:516
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
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
In arch/x86/mm/pat.c (ffffffff810866fe)
Location: arch/x86/mm/pat.c:516
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
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
In arch/x86/mm/pat/memtype.c (ffffffff8108fe79)
Location: arch/x86/mm/pat/memtype.c:548
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
  - arch/x86/mm/pat/memtype.c:memtype_reserve
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
In arch/x86/mm/pat/memtype.c (ffffffff8108fb79)
Location: arch/x86/mm/pat/memtype.c:548
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
  - arch/x86/mm/pat/memtype.c:memtype_reserve
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
In arch/x86/mm/pat/memtype.c (ffffffff81090679)
Location: arch/x86/mm/pat/memtype.c:548
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
  - arch/x86/mm/pat/memtype.c:memtype_reserve
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
In arch/x86/mm/pat/memtype.c (ffffffff810a00b2)
Location: arch/x86/mm/pat/memtype.c:548
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
  - arch/x86/mm/pat/memtype.c:memtype_reserve
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
In arch/x86/mm/pat/memtype.c (ffffffff810b42c0)
Location: arch/x86/mm/pat/memtype.c:556
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_reserve
  - arch/x86/mm/pat/memtype.c:memtype_reserve
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
In arch/x86/mm/pat/memtype.c (ffffffff810cee6c)
Location: arch/x86/mm/pat/memtype.c:509
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_reserve
  - arch/x86/mm/pat/memtype.c:memtype_reserve
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
In arch/x86/mm/pat/memtype.c (ffffffff810d241c)
Location: arch/x86/mm/pat/memtype.c:509
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_reserve
  - arch/x86/mm/pat/memtype.c:memtype_reserve
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
In arch/x86/mm/pat/memtype.c (ffffffff810dabac)
Location: arch/x86/mm/pat/memtype.c:509
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_reserve
  - arch/x86/mm/pat/memtype.c:memtype_reserve
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
In arch/x86/mm/pat.c (ffffffff810856fe)
Location: arch/x86/mm/pat.c:516
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
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
In arch/x86/mm/pat.c (ffffffff8107447e)
Location: arch/x86/mm/pat.c:516
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
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
In arch/x86/mm/pat.c (ffffffff810856ae)
Location: arch/x86/mm/pat.c:516
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
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
In arch/x86/mm/pat.c (ffffffff810877fe)
Location: arch/x86/mm/pat.c:516
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
```
</details>
</li>
</ul>

## Differences
