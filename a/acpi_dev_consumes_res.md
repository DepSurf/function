# Function: <code>acpi_dev_consumes_res</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814f292a)
Location: drivers/acpi/resource.c:684
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff8150054c)
Location: drivers/acpi/resource.c:684
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff8154273c)
Location: drivers/acpi/resource.c:729
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff8157869c)
Location: drivers/acpi/resource.c:729
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff815902ec)
Location: drivers/acpi/resource.c:729
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff815c10cc)
Location: drivers/acpi/resource.c:721
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff815e238c)
Location: drivers/acpi/resource.c:721
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_dev_consumes_res(struct acpi_device *adev, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168cd60)
Location: drivers/acpi/resource.c:721
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
**Symbols:**

```
ffffffff8168cd60-ffffffff8168ce3a: acpi_dev_consumes_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_dev_consumes_res(struct acpi_device *adev, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff816aaa60)
Location: drivers/acpi/resource.c:714
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
**Symbols:**

```
ffffffff816aaa60-ffffffff816aab3a: acpi_dev_consumes_res (STB_LOCAL)
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
In drivers/acpi/resource.c (ffffffff8168d3ac)
Location: drivers/acpi/resource.c:759
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81702bdc)
Location: drivers/acpi/resource.c:766
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff81830ba3)
Location: drivers/acpi/resource.c:766
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff81963d33)
Location: drivers/acpi/resource.c:903
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff819aa1d3)
Location: drivers/acpi/resource.c:944
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff819f4463)
Location: drivers/acpi/resource.c:1007
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffff80001076ed50)
Location: drivers/acpi/resource.c:721
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff815d464c)
Location: drivers/acpi/resource.c:721
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff815be20c)
Location: drivers/acpi/resource.c:721
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff815d666c)
Location: drivers/acpi/resource.c:721
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In drivers/acpi/resource.c (ffffffff815f052c)
Location: drivers/acpi/resource.c:721
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
</ul>
