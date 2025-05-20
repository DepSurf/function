# Function: <code>hv_get_partition_id</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff831c5052)
Location: arch/x86/hyperv/hv_init.c:349
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hv_get_partition_id();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff832a5a30)
Location: arch/x86/hyperv/hv_init.c:331
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff832a5a30-ffffffff832a5ad7: hv_get_partition_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hv_get_partition_id();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff83454acd)
Location: arch/x86/hyperv/hv_init.c:371
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff83454acd-ffffffff83454b8b: hv_get_partition_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hv_get_partition_id();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff83e72670)
Location: arch/x86/hyperv/hv_init.c:361
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff83e72670-ffffffff83e72733: hv_get_partition_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hv_get_partition_id();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff83693590)
Location: arch/x86/hyperv/hv_init.c:364
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff83693590-ffffffff83693653: hv_get_partition_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hv_get_partition_id();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff838c3110)
Location: arch/x86/hyperv/hv_init.c:398
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff838c3110-ffffffff838c3187: hv_get_partition_id (STB_LOCAL)
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
