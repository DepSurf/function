# Function: <code>map_ldt_struct_to_user</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103453a)
Location: arch/x86/kernel/ldt.c:180
Inline: True
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
In arch/x86/kernel/ldt.c (ffffffff81036299)
Location: arch/x86/kernel/ldt.c:180
Inline: True
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
In arch/x86/kernel/ldt.c (ffffffff81036bd0)
Location: arch/x86/kernel/ldt.c:180
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void map_ldt_struct_to_user(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038520)
Location: arch/x86/kernel/ldt.c:264
Inline: False
```
**Symbols:**

```
ffffffff81038520-ffffffff81038593: map_ldt_struct_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void map_ldt_struct_to_user(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038ed0)
Location: arch/x86/kernel/ldt.c:264
Inline: False
```
**Symbols:**

```
ffffffff81038ed0-ffffffff81038f43: map_ldt_struct_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void map_ldt_struct_to_user(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103a9c0)
Location: arch/x86/kernel/ldt.c:264
Inline: False
```
**Symbols:**

```
ffffffff8103a9c0-ffffffff8103aa3a: map_ldt_struct_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void map_ldt_struct_to_user(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:264
Inline: False
```
**Symbols:**

```
ffffffff810403a0-ffffffff8104043c: map_ldt_struct_to_user (STB_LOCAL)
ffffffff81c98c8b-ffffffff81c98cdb: map_ldt_struct_to_user.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void map_ldt_struct_to_user(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
**Symbols:**

```
ffffffff81047cb0-ffffffff81047d77: map_ldt_struct_to_user (STB_LOCAL)
ffffffff81e48247-ffffffff81e48297: map_ldt_struct_to_user.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void map_ldt_struct_to_user(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
**Symbols:**

```
ffffffff81052990-ffffffff81052a36: map_ldt_struct_to_user (STB_LOCAL)
ffffffff8205212f-ffffffff8205217f: map_ldt_struct_to_user.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void map_ldt_struct_to_user(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
**Symbols:**

```
ffffffff81053900-ffffffff810539b4: map_ldt_struct_to_user (STB_LOCAL)
ffffffff820d0649-ffffffff820d0695: map_ldt_struct_to_user.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void map_ldt_struct_to_user(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
**Symbols:**

```
ffffffff8105ab20-ffffffff8105abd4: map_ldt_struct_to_user (STB_LOCAL)
ffffffff821ab15e-ffffffff821ab1aa: map_ldt_struct_to_user.cold (STB_LOCAL)
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
In arch/x86/kernel/ldt.c (ffffffff81036d30)
Location: arch/x86/kernel/ldt.c:180
Inline: True
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
In arch/x86/kernel/ldt.c (ffffffff81026641)
Location: arch/x86/kernel/ldt.c:180
Inline: True
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
In arch/x86/kernel/ldt.c (ffffffff81036b90)
Location: arch/x86/kernel/ldt.c:180
Inline: True
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
In arch/x86/kernel/ldt.c (ffffffff81037a8e)
Location: arch/x86/kernel/ldt.c:180
Inline: True
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
