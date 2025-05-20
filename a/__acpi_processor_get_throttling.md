# Function: <code>__acpi_processor_get_throttling</code>

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
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81531270)
Location: drivers/acpi/processor_throttling.c:905
Inline: False
```
**Symbols:**

```
ffffffff81531270-ffffffff81531283: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81592250)
Location: drivers/acpi/processor_throttling.c:905
Inline: False
```
**Symbols:**

```
ffffffff81592250-ffffffff81592269: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815c96a0)
Location: drivers/acpi/processor_throttling.c:906
Inline: False
```
**Symbols:**

```
ffffffff815c96a0-ffffffff815c96b9: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815e2c80)
Location: drivers/acpi/processor_throttling.c:906
Inline: False
```
**Symbols:**

```
ffffffff815e2c80-ffffffff815e2c99: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81614810)
Location: drivers/acpi/processor_throttling.c:893
Inline: False
```
**Symbols:**

```
ffffffff81614810-ffffffff81614829: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81635d00)
Location: drivers/acpi/processor_throttling.c:893
Inline: False
```
**Symbols:**

```
ffffffff81635d00-ffffffff81635d19: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e32f8)
Location: drivers/acpi/processor_throttling.c:893
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff816e28e0-ffffffff816e28f9: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81700f58)
Location: drivers/acpi/processor_throttling.c:892
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff81700560-ffffffff81700579: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e27e8)
Location: drivers/acpi/processor_throttling.c:889
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff816e20c0-ffffffff816e20d9: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8175b078)
Location: drivers/acpi/processor_throttling.c:879
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff8175a8c0-ffffffff8175a8d9: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8188ecb6)
Location: drivers/acpi/processor_throttling.c:879
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff8188dc50-ffffffff8188dc6f: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff819d64c6)
Location: drivers/acpi/processor_throttling.c:877
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff819d5660-ffffffff819d567f: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a1de06)
Location: drivers/acpi/processor_throttling.c:877
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff81a1cfb0-ffffffff81a1cfcf: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a6911f)
Location: drivers/acpi/processor_throttling.c:877
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff81a682c0-ffffffff81a682df: __acpi_processor_get_throttling (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816054d0)
Location: drivers/acpi/processor_throttling.c:893
Inline: False
```
**Symbols:**

```
ffffffff816054d0-ffffffff816054e9: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815f0580)
Location: drivers/acpi/processor_throttling.c:893
Inline: False
```
**Symbols:**

```
ffffffff815f0580-ffffffff815f0599: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81629fe0)
Location: drivers/acpi/processor_throttling.c:893
Inline: False
```
**Symbols:**

```
ffffffff81629fe0-ffffffff81629ff9: __acpi_processor_get_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __acpi_processor_get_throttling(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81643e80)
Location: drivers/acpi/processor_throttling.c:893
Inline: False
```
**Symbols:**

```
ffffffff81643e80-ffffffff81643e99: __acpi_processor_get_throttling (STB_LOCAL)
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
