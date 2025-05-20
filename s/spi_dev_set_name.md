# Function: <code>spi_dev_set_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e6c95)
Location: drivers/spi/spi.c:464
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81645285)
Location: drivers/spi/spi.c:467
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff81676385)
Location: drivers/spi/spi.c:468
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff8168a8b5)
Location: drivers/spi/spi.c:470
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff816f40d3)
Location: drivers/spi/spi.c:474
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff81730b1d)
Location: drivers/spi/spi.c:478
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff817536ed)
Location: drivers/spi/spi.c:518
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff8178eacd)
Location: drivers/spi/spi.c:521
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff817b268d)
Location: drivers/spi/spi.c:522
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff8187abdd)
Location: drivers/spi/spi.c:528
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff818898cd)
Location: drivers/spi/spi.c:537
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff8186c1dc)
Location: drivers/spi/spi.c:533
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void spi_dev_set_name(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818f8a70)
Location: drivers/spi/spi.c:566
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_add_device
```
**Symbols:**

```
ffffffff818f8a70-ffffffff818f8b03: spi_dev_set_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void spi_dev_set_name(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a49e10)
Location: drivers/spi/spi.c:535
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_add_device
```
**Symbols:**

```
ffffffff81a49e10-ffffffff81a49ebe: spi_dev_set_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void spi_dev_set_name(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd02f0)
Location: drivers/spi/spi.c:597
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_add_device
```
**Symbols:**

```
ffffffff81bd02f0-ffffffff81bd039e: spi_dev_set_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void spi_dev_set_name(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c27f70)
Location: drivers/spi/spi.c:598
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_add_device
```
**Symbols:**

```
ffffffff81c27f70-ffffffff81c2801e: spi_dev_set_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void spi_dev_set_name(struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cda580)
Location: drivers/spi/spi.c:598
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/spi/spi.c:__spi_add_device
```
**Symbols:**

```
ffffffff81cda580-ffffffff81cda62e: spi_dev_set_name (STB_LOCAL)
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
In drivers/spi/spi.c (ffff8000109c298c)
Location: drivers/spi/spi.c:522
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aafbdc)
Location: drivers/spi/spi.c:522
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a866d0)
Location: drivers/spi/spi.c:522
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe0006166be)
Location: drivers/spi/spi.c:522
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
</details>
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
In drivers/spi/spi.c (ffffffff8177716d)
Location: drivers/spi/spi.c:522
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff81756f1d)
Location: drivers/spi/spi.c:522
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff817a750d)
Location: drivers/spi/spi.c:522
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
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
In drivers/spi/spi.c (ffffffff817c138d)
Location: drivers/spi/spi.c:522
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
