# Function: <code>sync_global_pgds_l5</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_global_pgds_l5(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81084d70)
Location: arch/x86/mm/init_64.c:127
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81084d70-ffffffff81084f47: sync_global_pgds_l5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_global_pgds_l5(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bd8cbe)
Location: arch/x86/mm/init_64.c:127
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81bd8cbe-ffffffff81bd8e40: sync_global_pgds_l5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_global_pgds_l5(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bcacb8)
Location: arch/x86/mm/init_64.c:127
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81bcacb8-ffffffff81bcae3a: sync_global_pgds_l5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sync_global_pgds_l5(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ca01a0)
Location: arch/x86/mm/init_64.c:128
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81ca01a0-ffffffff81ca037a: sync_global_pgds_l5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sync_global_pgds_l5(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81e4f80d)
Location: arch/x86/mm/init_64.c:127
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81e4f80d-ffffffff81e4f9f6: sync_global_pgds_l5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sync_global_pgds_l5(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:133
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff810c1230-ffffffff810c1458: sync_global_pgds_l5 (STB_LOCAL)
ffffffff820547df-ffffffff8205485d: sync_global_pgds_l5.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sync_global_pgds_l5(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:133
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff810c4910-ffffffff810c4b3b: sync_global_pgds_l5 (STB_LOCAL)
ffffffff820d2ded-ffffffff820d2e6b: sync_global_pgds_l5.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sync_global_pgds_l5(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:133
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff810ccd60-ffffffff810ccf8b: sync_global_pgds_l5 (STB_LOCAL)
ffffffff821adc63-ffffffff821adce1: sync_global_pgds_l5.cold (STB_LOCAL)
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
