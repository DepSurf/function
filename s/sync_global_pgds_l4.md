# Function: <code>sync_global_pgds_l4</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81073b30)
Location: arch/x86/mm/init_64.c:133
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81073b30-ffffffff81073cac: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079430)
Location: arch/x86/mm/init_64.c:132
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81079430-ffffffff810795ac: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d160)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8107d160-ffffffff8107d2dd: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e1f0)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8107e1f0-ffffffff8107e36d: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81084f50)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81084f50-ffffffff81085192: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bd8e83)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81bd8e83-ffffffff81bd8ff8: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bcae3a)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81bcae3a-ffffffff81bcafaf: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ca037a)
Location: arch/x86/mm/init_64.c:165
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81ca037a-ffffffff81ca054b: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81e4f9f6)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff81e4f9f6-ffffffff81e4fbdd: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:170
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff810c1470-ffffffff810c16c8: sync_global_pgds_l4 (STB_LOCAL)
ffffffff8205485d-ffffffff820548d8: sync_global_pgds_l4.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:170
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff810c4b50-ffffffff810c4dab: sync_global_pgds_l4 (STB_LOCAL)
ffffffff820d2e6b-ffffffff820d2ee6: sync_global_pgds_l4.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:170
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:sync_global_pgds
```
**Symbols:**

```
ffffffff810ccfa0-ffffffff810cd1fb: sync_global_pgds_l4 (STB_LOCAL)
ffffffff821adce1-ffffffff821add5c: sync_global_pgds_l4.cold (STB_LOCAL)
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
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d1f0)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8107d1f0-ffffffff8107d36d: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ca40)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8106ca40-ffffffff8106cbae: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d1a0)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8107d1a0-ffffffff8107d31d: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sync_global_pgds_l4(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f290)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8107f290-ffffffff8107f409: sync_global_pgds_l4 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
