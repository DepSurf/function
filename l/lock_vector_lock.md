# Function: <code>lock_vector_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810556f0)
Location: arch/x86/kernel/apic/vector.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
**Symbols:**

```
ffffffff810556f0-ffffffff81055707: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055970)
Location: arch/x86/kernel/apic/vector.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81055970-ffffffff81055987: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058710)
Location: arch/x86/kernel/apic/vector.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81058710-ffffffff81058727: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81057ef0)
Location: arch/x86/kernel/apic/vector.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81057ef0-ffffffff81057f07: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105c626)
Location: arch/x86/kernel/apic/vector.c:51
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8105c480-ffffffff8105c497: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f5f5)
Location: arch/x86/kernel/apic/vector.c:52
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8105f450-ffffffff8105f467: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81065265)
Location: arch/x86/kernel/apic/vector.c:53
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810650d0-ffffffff810650e7: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068945)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810687c0-ffffffff810687d7: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810692b5)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff81069130-ffffffff81069147: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810702b5)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff81070110-ffffffff81070127: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81071815)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff81071540-ffffffff81071557: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81072315)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff81072040-ffffffff81072057: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107e1f5)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff8107def0-ffffffff8107df07: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108d875)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff8108d4e0-ffffffff8108d4fd: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a1f75)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff810a1b50-ffffffff810a1b6d: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a4f55)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff810a4b30-ffffffff810a4b4d: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810abfc0)
Location: arch/x86/kernel/apic/vector.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff810abb80-ffffffff810abb9d: lock_vector_lock (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068da5)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff81068c20-ffffffff81068c37: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81059115)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff81058f90-ffffffff81058fa7: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069255)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff810690d0-ffffffff810690e7: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void lock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106a965)
Location: arch/x86/kernel/apic/vector.c:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff8106a7e0-ffffffff8106a7f7: lock_vector_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
