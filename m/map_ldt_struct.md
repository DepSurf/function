# Function: <code>map_ldt_struct</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int map_ldt_struct(struct mm_struct *mm, struct ldt_struct *ldt, int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031cf0)
Location: arch/x86/kernel/ldt.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81031cf0-ffffffff81031f44: map_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int map_ldt_struct(struct mm_struct *mm, struct ldt_struct *ldt, int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032f80)
Location: arch/x86/kernel/ldt.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81032f80-ffffffff810331f1: map_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int map_ldt_struct(struct mm_struct *mm, struct ldt_struct *ldt, int slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81034350)
Location: arch/x86/kernel/ldt.c:204
Inline: True
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81034350-ffffffff810345b5: map_ldt_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103660a)
Location: arch/x86/kernel/ldt.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810360e0-ffffffff81036351: map_ldt_struct.part.0 (STB_LOCAL)
ffffffff81036b5f-ffffffff81036bbe: map_ldt_struct.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036e3a)
Location: arch/x86/kernel/ldt.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81036a00-ffffffff81036c83: map_ldt_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038d61)
Location: arch/x86/kernel/ldt.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81038830-ffffffff81038a6d: map_ldt_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810395db)
Location: arch/x86/kernel/ldt.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81039180-ffffffff810393b1: map_ldt_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103b0ab)
Location: arch/x86/kernel/ldt.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff8103acb0-ffffffff8103aee1: map_ldt_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81040adb)
Location: arch/x86/kernel/ldt.c:288
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810406d0-ffffffff81040916: map_ldt_struct.part.0 (STB_LOCAL)
ffffffff81c98d40-ffffffff81c98dad: map_ldt_struct.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int map_ldt_struct(struct mm_struct *mm, struct ldt_struct *ldt, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81048060-ffffffff810482de: map_ldt_struct (STB_LOCAL)
ffffffff81e48301-ffffffff81e4836d: map_ldt_struct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int map_ldt_struct(struct mm_struct *mm, struct ldt_struct *ldt, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81052da0-ffffffff81053027: map_ldt_struct (STB_LOCAL)
ffffffff820521e9-ffffffff82052255: map_ldt_struct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int map_ldt_struct(struct mm_struct *mm, struct ldt_struct *ldt, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81053d80-ffffffff8105400a: map_ldt_struct (STB_LOCAL)
ffffffff820d0701-ffffffff820d076f: map_ldt_struct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int map_ldt_struct(struct mm_struct *mm, struct ldt_struct *ldt, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff8105afa0-ffffffff8105b23f: map_ldt_struct (STB_LOCAL)
ffffffff821ab216-ffffffff821ab284: map_ldt_struct.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036f9a)
Location: arch/x86/kernel/ldt.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81036b60-ffffffff81036de3: map_ldt_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81026894)
Location: arch/x86/kernel/ldt.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81026490-ffffffff810266ff: map_ldt_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036dfa)
Location: arch/x86/kernel/ldt.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810369c0-ffffffff81036c43: map_ldt_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037dfa)
Location: arch/x86/kernel/ldt.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810378c0-ffffffff81037b41: map_ldt_struct.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
