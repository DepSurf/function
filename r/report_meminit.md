# Function: <code>report_meminit</code>

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
In init/main.c (ffffffff82899ecc)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff8289ceb1)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void report_meminit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82cc319a)
Location: init/main.c:781
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff82cc319a-ffffffff82cc3214: report_meminit (STB_LOCAL)
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
In init/main.c (ffffffff82faf4ea)
Location: init/main.c:793
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff831b950b)
Location: init/main.c:794
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff8329986a)
Location: init/main.c:809
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff83447aa9)
Location: init/main.c:802
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff83e61283)
Location: init/main.c:807
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In mm/mm_init.c (ffffffff836e2f6e)
Location: mm/mm_init.c:2691
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
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
In mm/mm_init.c (ffffffff839157fe)
Location: mm/mm_init.c:2679
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
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
In init/main.c (ffff800011430ec8)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (c1500e60)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (c000000001343fc0)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffe000000b84)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff8288aeb1)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff82888e51)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff8289deb1)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
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
In init/main.c (ffffffff8289deb1)
Location: init/main.c:524
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
