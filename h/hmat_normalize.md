# Function: <code>hmat_normalize</code>

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
u32 hmat_normalize(u16 entry, u64 base, u8 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828f39dc)
Location: drivers/acpi/hmat/hmat.c:151
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff828f39dc-ffffffff828f3a4b: hmat_normalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff8163ae56)
Location: drivers/acpi/hmat/hmat.c:161
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff8163acb0-ffffffff8163ad22: hmat_normalize.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff816e7dc7)
Location: drivers/acpi/numa/hmat.c:182
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff816e8158-ffffffff816e81bc: hmat_normalize.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff81705466)
Location: drivers/acpi/numa/hmat.c:191
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
```
**Symbols:**

```
ffffffff81c0302c-ffffffff81c03090: hmat_normalize.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff816e6b08)
Location: drivers/acpi/numa/hmat.c:191
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
```
**Symbols:**

```
ffffffff81bf4a4f-ffffffff81bf4ab1: hmat_normalize.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff817600d8)
Location: drivers/acpi/numa/hmat.c:191
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
```
**Symbols:**

```
ffffffff81cf1c9b-ffffffff81cf1cfd: hmat_normalize.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff81893ab7)
Location: drivers/acpi/numa/hmat.c:191
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
```
**Symbols:**

```
ffffffff81eb9c4c-ffffffff81eb9cbd: hmat_normalize.part.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff819db5b7)
Location: drivers/acpi/numa/hmat.c:190
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
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
In drivers/acpi/numa/hmat.c (ffffffff81a23267)
Location: drivers/acpi/numa/hmat.c:190
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
  - drivers/acpi/numa/hmat.c:hmat_initiator_perf
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
In drivers/acpi/numa/hmat.c (ffffffff81a6e224)
Location: drivers/acpi/numa/hmat.c:264
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffff8000107a60e0)
Location: drivers/acpi/hmat/hmat.c:161
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffff8000107a5ed0-ffff8000107a5f88: hmat_normalize.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff816081b6)
Location: drivers/acpi/hmat/hmat.c:161
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff81608010-ffffffff81608082: hmat_normalize.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff815fa306)
Location: drivers/acpi/hmat/hmat.c:161
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff815fa160-ffffffff815fa1d2: hmat_normalize.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff81648fd6)
Location: drivers/acpi/hmat/hmat.c:161
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff81648e30-ffffffff81648ea2: hmat_normalize.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
