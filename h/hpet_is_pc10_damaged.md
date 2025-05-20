# Function: <code>hpet_is_pc10_damaged</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff832bd661)
Location: arch/x86/kernel/hpet.c:974
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In arch/x86/kernel/hpet.c (ffffffff8346f055)
Location: arch/x86/kernel/hpet.c:974
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool hpet_is_pc10_damaged();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff83e95210)
Location: arch/x86/kernel/hpet.c:974
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
**Symbols:**

```
ffffffff83e95210-ffffffff83e95328: hpet_is_pc10_damaged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool hpet_is_pc10_damaged();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff836b8d70)
Location: arch/x86/kernel/hpet.c:974
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
**Symbols:**

```
ffffffff836b8d70-ffffffff836b8e86: hpet_is_pc10_damaged (STB_LOCAL)
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
In arch/x86/kernel/hpet.c (ffffffff838e9b36)
Location: arch/x86/kernel/hpet.c:974
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
