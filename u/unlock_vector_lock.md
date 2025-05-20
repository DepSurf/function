# Function: <code>unlock_vector_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055710)
Location: arch/x86/kernel/apic/vector.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
**Symbols:**

```
ffffffff81055710-ffffffff81055729: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055990)
Location: arch/x86/kernel/apic/vector.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81055990-ffffffff810559a9: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058730)
Location: arch/x86/kernel/apic/vector.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81058730-ffffffff81058749: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81057f10)
Location: arch/x86/kernel/apic/vector.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81057f10-ffffffff81057f29: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105c4a0)
Location: arch/x86/kernel/apic/vector.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/apic/vector.c:lapic_offline
```
**Symbols:**

```
ffffffff8105c4a0-ffffffff8105c4b9: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f611)
Location: arch/x86/kernel/apic/vector.c:60
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8105f470-ffffffff8105f489: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81065281)
Location: arch/x86/kernel/apic/vector.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810650f0-ffffffff81065109: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068961)
Location: arch/x86/kernel/apic/vector.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810687e0-ffffffff810687f9: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810692d1)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff81069150-ffffffff81069169: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810702d1)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff81070130-ffffffff81070149: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81071831)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff81071560-ffffffff81071579: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81072331)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff81072060-ffffffff81072079: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107e211)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff8107df10-ffffffff8107df29: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108d891)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff8108d500-ffffffff8108d51d: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a1f91)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff810a1b80-ffffffff810a1b9d: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a4f71)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff810a4b60-ffffffff810a4b7d: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810abff0)
Location: arch/x86/kernel/apic/vector.c:69
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
ffffffff810abbb0-ffffffff810abbcd: unlock_vector_lock (STB_GLOBAL)
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
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068dc1)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff81068c40-ffffffff81068c59: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81059131)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff81058fb0-ffffffff81058fc9: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069271)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff810690f0-ffffffff81069109: unlock_vector_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void unlock_vector_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106a981)
Location: arch/x86/kernel/apic/vector.c:58
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
ffffffff8106a800-ffffffff8106a817: unlock_vector_lock (STB_GLOBAL)
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
