# Function: <code>acpi_ec_flush_work</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81504010)
Location: drivers/acpi/ec.c:543
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_freeze_sync
```
**Symbols:**

```
ffffffff81504010-ffffffff81504038: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81546330)
Location: drivers/acpi/ec.c:545
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_sync
```
**Symbols:**

```
ffffffff81546330-ffffffff81546358: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8157c2e0)
Location: drivers/acpi/ec.c:545
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_sync
```
**Symbols:**

```
ffffffff8157c2e0-ffffffff8157c308: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81593f60)
Location: drivers/acpi/ec.c:545
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_sync
```
**Symbols:**

```
ffffffff81593f60-ffffffff81593f88: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c4fa0)
Location: drivers/acpi/ec.c:559
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_sync
```
**Symbols:**

```
ffffffff815c4fa0-ffffffff815c4fc8: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e61e0)
Location: drivers/acpi/ec.c:550
Inline: False
```
**Symbols:**

```
ffffffff815e61e0-ffffffff815e61fb: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816918b6)
Location: drivers/acpi/ec.c:556
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff81691760-ffffffff81691789: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816af5d8)
Location: drivers/acpi/ec.c:539
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff816af4a0-ffffffff816af4c9: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81691be8)
Location: drivers/acpi/ec.c:540
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff81691ab0-ffffffff81691ad9: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff817076b4)
Location: drivers/acpi/ec.c:542
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff81707550-ffffffff81707579: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81835957)
Location: drivers/acpi/ec.c:561
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff818356f0-ffffffff81835713: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819698e7)
Location: drivers/acpi/ec.c:562
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff81969600-ffffffff81969623: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819afece)
Location: drivers/acpi/ec.c:562
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff819afbf0-ffffffff819afc13: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819fa37e)
Location: drivers/acpi/ec.c:562
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
```
**Symbols:**

```
ffffffff819fa0a0-ffffffff819fa0c3: acpi_ec_flush_work (STB_GLOBAL)
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
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010772f58)
Location: drivers/acpi/ec.c:550
Inline: False
```
**Symbols:**

```
ffff800010772f58-ffff800010772f80: acpi_ec_flush_work (STB_GLOBAL)
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
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d80d0)
Location: drivers/acpi/ec.c:550
Inline: False
```
**Symbols:**

```
ffffffff815d80d0-ffffffff815d80eb: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c1c90)
Location: drivers/acpi/ec.c:550
Inline: False
```
**Symbols:**

```
ffffffff815c1c90-ffffffff815c1cab: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815da4c0)
Location: drivers/acpi/ec.c:550
Inline: False
```
**Symbols:**

```
ffffffff815da4c0-ffffffff815da4db: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ec_flush_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f4380)
Location: drivers/acpi/ec.c:550
Inline: False
```
**Symbols:**

```
ffffffff815f4380-ffffffff815f439b: acpi_ec_flush_work (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
