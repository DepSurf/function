# Function: <code>hmat_register_target_initiators</code>

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
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828f4009)
Location: drivers/acpi/hmat/hmat.c:520
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828f4009-ffffffff828f423c: hmat_register_target_initiators (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff8163ad30)
Location: drivers/acpi/hmat/hmat.c:541
Inline: False
```
**Symbols:**

```
ffffffff8163ad30-ffffffff8163b00f: hmat_register_target_initiators (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff816e7ca0)
Location: drivers/acpi/numa/hmat.c:562
Inline: False
```
**Symbols:**

```
ffffffff816e7ca0-ffffffff816e7fc2: hmat_register_target_initiators (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff817054e0)
Location: drivers/acpi/numa/hmat.c:576
Inline: False
```
**Symbols:**

```
ffffffff817054e0-ffffffff81705999: hmat_register_target_initiators (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff816e6b80)
Location: drivers/acpi/numa/hmat.c:577
Inline: False
```
**Symbols:**

```
ffffffff816e6b80-ffffffff816e7047: hmat_register_target_initiators (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (0)
Location: drivers/acpi/numa/hmat.c:577
Inline: False
```
**Symbols:**

```
ffffffff81760150-ffffffff8176064b: hmat_register_target_initiators (STB_LOCAL)
ffffffff81cf1cfd-ffffffff81cf1d1e: hmat_register_target_initiators.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (0)
Location: drivers/acpi/numa/hmat.c:577
Inline: False
```
**Symbols:**

```
ffffffff81893b50-ffffffff81894057: hmat_register_target_initiators (STB_LOCAL)
ffffffff81eb9cbd-ffffffff81eb9cd2: hmat_register_target_initiators.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (0)
Location: drivers/acpi/numa/hmat.c:585
Inline: False
```
**Symbols:**

```
ffffffff819db6d0-ffffffff819dbb60: hmat_register_target_initiators (STB_LOCAL)
ffffffff82092835-ffffffff8209284a: hmat_register_target_initiators.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (0)
Location: drivers/acpi/numa/hmat.c:585
Inline: False
```
**Symbols:**

```
ffffffff81a23380-ffffffff81a23812: hmat_register_target_initiators (STB_LOCAL)
ffffffff821135b7-ffffffff821135cc: hmat_register_target_initiators.cold (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff81a6e684)
Location: drivers/acpi/numa/hmat.c:781
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffff8000107a5f88)
Location: drivers/acpi/hmat/hmat.c:541
Inline: False
```
**Symbols:**

```
ffff8000107a5f88-ffff8000107a62d0: hmat_register_target_initiators (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff81608090)
Location: drivers/acpi/hmat/hmat.c:541
Inline: False
```
**Symbols:**

```
ffffffff81608090-ffffffff8160836f: hmat_register_target_initiators (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff815fa1e0)
Location: drivers/acpi/hmat/hmat.c:541
Inline: False
```
**Symbols:**

```
ffffffff815fa1e0-ffffffff815fa4bf: hmat_register_target_initiators (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hmat_register_target_initiators(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff81648eb0)
Location: drivers/acpi/hmat/hmat.c:541
Inline: False
```
**Symbols:**

```
ffffffff81648eb0-ffffffff8164918f: hmat_register_target_initiators (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
