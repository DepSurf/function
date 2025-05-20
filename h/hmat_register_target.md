# Function: <code>hmat_register_target</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff8163b010)
Location: drivers/acpi/hmat/hmat.c:616
Inline: True
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff8163b010-ffffffff8163b0bd: hmat_register_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff816e7fd0)
Location: drivers/acpi/numa/hmat.c:712
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff816e7fd0-ffffffff816e80b0: hmat_register_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff817059a0)
Location: drivers/acpi/numa/hmat.c:712
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff817059a0-ffffffff81705a58: hmat_register_target.part.0 (STB_LOCAL)
ffffffff81705a60-ffffffff81705ac7: hmat_register_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff816e7050)
Location: drivers/acpi/numa/hmat.c:713
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff816e7050-ffffffff816e7148: hmat_register_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff817606ac)
Location: drivers/acpi/numa/hmat.c:713
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff81760650-ffffffff81760754: hmat_register_target (STB_LOCAL)
ffffffff81cf1d1e-ffffffff81cf1d32: hmat_register_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff818940ca)
Location: drivers/acpi/numa/hmat.c:713
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff81894060-ffffffff81894187: hmat_register_target (STB_LOCAL)
ffffffff81eb9cd2-ffffffff81eb9ce6: hmat_register_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff819dbbda)
Location: drivers/acpi/numa/hmat.c:725
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff819dbb70-ffffffff819dbc97: hmat_register_target (STB_LOCAL)
ffffffff8209284a-ffffffff8209285e: hmat_register_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff81a2389a)
Location: drivers/acpi/numa/hmat.c:725
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff81a23830-ffffffff81a23957: hmat_register_target (STB_LOCAL)
ffffffff821135cc-ffffffff821135e0: hmat_register_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/numa/hmat.c (0)
Location: drivers/acpi/numa/hmat.c:822
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff81a6e590-ffffffff81a6e720: hmat_register_target (STB_LOCAL)
ffffffff821f0f3f-ffffffff821f0f53: hmat_register_target.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffff8000107a62d0)
Location: drivers/acpi/hmat/hmat.c:616
Inline: True
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_callback
```
**Symbols:**

```
ffff8000107a62d0-ffff8000107a63c4: hmat_register_target (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff81608370)
Location: drivers/acpi/hmat/hmat.c:616
Inline: True
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff81608370-ffffffff8160841d: hmat_register_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff815fa4c0)
Location: drivers/acpi/hmat/hmat.c:616
Inline: True
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff815fa4c0-ffffffff815fa56d: hmat_register_target (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hmat_register_target(struct memory_target *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff81649190)
Location: drivers/acpi/hmat/hmat.c:616
Inline: True
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_callback
```
**Symbols:**

```
ffffffff81649190-ffffffff8164923d: hmat_register_target (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
