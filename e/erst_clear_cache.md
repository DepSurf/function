# Function: <code>erst_clear_cache</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void erst_clear_cache(u64 record_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8189cb30)
Location: drivers/acpi/apei/erst.c:859
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff8189cb30-ffffffff8189cba7: erst_clear_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void erst_clear_cache(u64 record_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff819e5750)
Location: drivers/acpi/apei/erst.c:859
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff819e5750-ffffffff819e57c7: erst_clear_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void erst_clear_cache(u64 record_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81a2dd80)
Location: drivers/acpi/apei/erst.c:859
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81a2dd80-ffffffff81a2ddf3: erst_clear_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void erst_clear_cache(u64 record_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81a78fc0)
Location: drivers/acpi/apei/erst.c:892
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81a78fc0-ffffffff81a79033: erst_clear_cache (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
