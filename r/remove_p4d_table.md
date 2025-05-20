# Function: <code>remove_p4d_table</code>

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
In arch/x86/mm/init_64.c (ffffffff819025a4)
Location: arch/x86/mm/init_64.c:1058
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff8198c519)
Location: arch/x86/mm/init_64.c:1066
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff819e88c4)
Location: arch/x86/mm/init_64.c:1080
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff81a2414d)
Location: arch/x86/mm/init_64.c:1073
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff81a94813)
Location: arch/x86/mm/init_64.c:1140
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff81acc0f3)
Location: arch/x86/mm/init_64.c:1140
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_p4d_table(p4d_t *p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc42e1)
Location: arch/x86/mm/init_64.c:1148
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81bc42e1-ffffffff81bc43ae: remove_p4d_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_p4d_table(p4d_t *p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3d1da)
Location: arch/x86/mm/init_64.c:1142
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81c3d1da-ffffffff81c3d2a7: remove_p4d_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_p4d_table(p4d_t *p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2f580)
Location: arch/x86/mm/init_64.c:1184
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81c2f580-ffffffff81c2f6b5: remove_p4d_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_p4d_table(p4d_t *p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4dc7e)
Location: arch/x86/mm/init_64.c:1185
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81d4dc7e-ffffffff81d4ddb6: remove_p4d_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_p4d_table(p4d_t *p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1d9f1)
Location: arch/x86/mm/init_64.c:1185
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff81f1d9f1-ffffffff81f1db48: remove_p4d_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_p4d_table(p4d_t *p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c5dc0)
Location: arch/x86/mm/init_64.c:1186
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff820c5dc0-ffffffff820c5f66: remove_p4d_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_p4d_table(p4d_t *p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82149e20)
Location: arch/x86/mm/init_64.c:1186
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff82149e20-ffffffff82149fc6: remove_p4d_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_p4d_table(p4d_t *p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap *altmap, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222c8d0)
Location: arch/x86/mm/init_64.c:1186
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff8222c8d0-ffffffff8222ca76: remove_p4d_table (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81a6af63)
Location: arch/x86/mm/init_64.c:1140
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff81a27469)
Location: arch/x86/mm/init_64.c:1140
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff81ad7373)
Location: arch/x86/mm/init_64.c:1140
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
In arch/x86/mm/init_64.c (ffffffff81ae3833)
Location: arch/x86/mm/init_64.c:1140
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
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
