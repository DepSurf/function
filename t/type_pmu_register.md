# Function: <code>type_pmu_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81f8804c)
Location: arch/x86/events/intel/uncore.c:1215
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff81fc343a)
Location: arch/x86/events/intel/uncore.c:1193
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff820a36c8)
Location: arch/x86/events/intel/uncore.c:1193
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff826a99e2)
Location: arch/x86/events/intel/uncore.c:1201
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff826d2b36)
Location: arch/x86/events/intel/uncore.c:1262
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff82888e52)
Location: arch/x86/events/intel/uncore.c:1263
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff8289ffd3)
Location: arch/x86/events/intel/uncore.c:1299
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff828a30af)
Location: arch/x86/events/intel/uncore.c:1331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int type_pmu_register(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82cc8dd8)
Location: arch/x86/events/intel/uncore.c:1331
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff82cc8dd8-ffffffff82cc8e13: type_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int type_pmu_register(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82fb4bef)
Location: arch/x86/events/intel/uncore.c:1491
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff82fb4bef-ffffffff82fb4c2d: type_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int type_pmu_register(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff831bf160)
Location: arch/x86/events/intel/uncore.c:1602
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff831bf160-ffffffff831bf19e: type_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int type_pmu_register(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8329facf)
Location: arch/x86/events/intel/uncore.c:1609
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8329facf-ffffffff8329fb0d: type_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int type_pmu_register(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8344e8e8)
Location: arch/x86/events/intel/uncore.c:1609
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8344e8e8-ffffffff8344e92c: type_pmu_register (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff83e6a291)
Location: arch/x86/events/intel/uncore.c:1609
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff8368ac2c)
Location: arch/x86/events/intel/uncore.c:1630
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff838ba7ec)
Location: arch/x86/events/intel/uncore.c:1630
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff828910af)
Location: arch/x86/events/intel/uncore.c:1331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff8288ef94)
Location: arch/x86/events/intel/uncore.c:1331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff828a40af)
Location: arch/x86/events/intel/uncore.c:1331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff828a40c3)
Location: arch/x86/events/intel/uncore.c:1331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
