# Function: <code>ident_p4d_init</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c37c)
Location: arch/x86/mm/ident_map.c:60
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81070e13)
Location: arch/x86/mm/ident_map.c:61
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81073d32)
Location: arch/x86/mm/ident_map.c:61
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81079c22)
Location: arch/x86/mm/ident_map.c:61
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff8107d949)
Location: arch/x86/mm/ident_map.c:61
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff8107e9d9)
Location: arch/x86/mm/ident_map.c:61
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ident_p4d_init(struct x86_mapping_info *info, p4d_t *p4d_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81084850)
Location: arch/x86/mm/ident_map.c:61
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
**Symbols:**

```
ffffffff81084850-ffffffff8108499a: ident_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ident_p4d_init(struct x86_mapping_info *info, p4d_t *p4d_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085d50)
Location: arch/x86/mm/ident_map.c:61
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
**Symbols:**

```
ffffffff81085d50-ffffffff81085ea6: ident_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ident_p4d_init(struct x86_mapping_info *info, p4d_t *p4d_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086b00)
Location: arch/x86/mm/ident_map.c:61
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
**Symbols:**

```
ffffffff81086b00-ffffffff81086c54: ident_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ident_p4d_init(struct x86_mapping_info *info, p4d_t *p4d_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81095e10)
Location: arch/x86/mm/ident_map.c:61
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
**Symbols:**

```
ffffffff81095e10-ffffffff81095f64: ident_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ident_p4d_init(struct x86_mapping_info *info, p4d_t *p4d_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a8640)
Location: arch/x86/mm/ident_map.c:61
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
**Symbols:**

```
ffffffff810a8640-ffffffff810a87da: ident_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ident_p4d_init(struct x86_mapping_info *info, p4d_t *p4d_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c1930)
Location: arch/x86/mm/ident_map.c:61
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
**Symbols:**

```
ffffffff810c1930-ffffffff810c1acd: ident_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ident_p4d_init(struct x86_mapping_info *info, p4d_t *p4d_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c5010)
Location: arch/x86/mm/ident_map.c:61
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
**Symbols:**

```
ffffffff810c5010-ffffffff810c51ad: ident_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ident_p4d_init(struct x86_mapping_info *info, p4d_t *p4d_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810cd460)
Location: arch/x86/mm/ident_map.c:74
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
**Symbols:**

```
ffffffff810cd460-ffffffff810cd5fd: ident_p4d_init (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d9d9)
Location: arch/x86/mm/ident_map.c:61
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff8106ccfa)
Location: arch/x86/mm/ident_map.c:61
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff8107d989)
Location: arch/x86/mm/ident_map.c:61
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff8107fa79)
Location: arch/x86/mm/ident_map.c:61
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
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
