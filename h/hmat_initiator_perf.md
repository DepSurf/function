# Function: <code>hmat_initiator_perf</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828f40cc)
Location: drivers/acpi/hmat/hmat.c:438
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
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
In drivers/acpi/hmat/hmat.c (ffffffff8163ade7)
Location: drivers/acpi/hmat/hmat.c:459
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
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
In drivers/acpi/numa/hmat.c (ffffffff816e7d59)
Location: drivers/acpi/numa/hmat.c:480
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 hmat_initiator_perf(struct memory_target *target, struct memory_initiator *initiator, struct acpi_hmat_locality *hmat_loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff817053f0)
Location: drivers/acpi/numa/hmat.c:494
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff817053f0-ffffffff817054df: hmat_initiator_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 hmat_initiator_perf(struct memory_target *target, struct memory_initiator *initiator, struct acpi_hmat_locality *hmat_loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff816e6a90)
Location: drivers/acpi/numa/hmat.c:494
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff816e6a90-ffffffff816e6b7e: hmat_initiator_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 hmat_initiator_perf(struct memory_target *target, struct memory_initiator *initiator, struct acpi_hmat_locality *hmat_loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff81760060)
Location: drivers/acpi/numa/hmat.c:494
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff81760060-ffffffff8176014e: hmat_initiator_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 hmat_initiator_perf(struct memory_target *target, struct memory_initiator *initiator, struct acpi_hmat_locality *hmat_loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff81893a30)
Location: drivers/acpi/numa/hmat.c:494
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff81893a30-ffffffff81893b4e: hmat_initiator_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 hmat_initiator_perf(struct memory_target *target, struct memory_initiator *initiator, struct acpi_hmat_locality *hmat_loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff819db530)
Location: drivers/acpi/numa/hmat.c:493
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff819db530-ffffffff819db64e: hmat_initiator_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 hmat_initiator_perf(struct memory_target *target, struct memory_initiator *initiator, struct acpi_hmat_locality *hmat_loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff81a231e0)
Location: drivers/acpi/numa/hmat.c:493
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff81a231e0-ffffffff81a232fe: hmat_initiator_perf (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff81a6e1a0)
Location: drivers/acpi/numa/hmat.c:598
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffff8000107a6064)
Location: drivers/acpi/hmat/hmat.c:459
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
</details>
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
In drivers/acpi/hmat/hmat.c (ffffffff81608147)
Location: drivers/acpi/hmat/hmat.c:459
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
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
In drivers/acpi/hmat/hmat.c (ffffffff815fa297)
Location: drivers/acpi/hmat/hmat.c:459
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff81648f67)
Location: drivers/acpi/hmat/hmat.c:459
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
