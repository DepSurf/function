# Function: <code>get_ins_reg_width</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff810739d0)
Location: arch/x86/mm/pf_in.c:164
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
```
**Symbols:**

```
ffffffff810739d0-ffffffff81073aaa: get_ins_reg_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff81074fb0)
Location: arch/x86/mm/pf_in.c:163
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff81074fb0-ffffffff8107508c: get_ins_reg_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff81078b30)
Location: arch/x86/mm/pf_in.c:163
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff81078b30-ffffffff81078c0c: get_ins_reg_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff81077420)
Location: arch/x86/mm/pf_in.c:163
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff81077420-ffffffff810774e8: get_ins_reg_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff8107d770)
Location: arch/x86/mm/pf_in.c:163
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff8107d770-ffffffff8107d838: get_ins_reg_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:163
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff810807c0-ffffffff81080884: get_ins_reg_width (STB_LOCAL)
ffffffff81080f1f-ffffffff81080f32: get_ins_reg_width.cold.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:163
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff81087310-ffffffff810873d4: get_ins_reg_width (STB_LOCAL)
ffffffff81087b2f-ffffffff81087b42: get_ins_reg_width.cold.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff8108aef0-ffffffff8108afa0: get_ins_reg_width (STB_LOCAL)
ffffffff8108b6df-ffffffff8108b6f2: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff8108bb60-ffffffff8108bc10: get_ins_reg_width (STB_LOCAL)
ffffffff8108c34f-ffffffff8108c362: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff81092fd0-ffffffff8109308c: get_ins_reg_width (STB_LOCAL)
ffffffff810937da-ffffffff810937ed: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff81092590-ffffffff8109264c: get_ins_reg_width (STB_LOCAL)
ffffffff81bd9fcf-ffffffff81bd9fe2: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff81093060-ffffffff8109311c: get_ins_reg_width (STB_LOCAL)
ffffffff81bcc02a-ffffffff81bcc03d: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff810a2e10-ffffffff810a2ee3: get_ins_reg_width (STB_LOCAL)
ffffffff81ca1f94-ffffffff81ca1faa: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff810b7470-ffffffff810b755a: get_ins_reg_width (STB_LOCAL)
ffffffff81e515ef-ffffffff81e51605: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff810d29e0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff810d29e0-ffffffff810d2ad7: get_ins_reg_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff810d5e50)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff810d5e50-ffffffff810d5f47: get_ins_reg_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff810de680)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff810de680-ffffffff810de777: get_ins_reg_width (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff8108ab20-ffffffff8108abd0: get_ins_reg_width (STB_LOCAL)
ffffffff8108b30f-ffffffff8108b322: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff81079690-ffffffff81079740: get_ins_reg_width (STB_LOCAL)
ffffffff81079e7f-ffffffff81079e92: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff8108aad0-ffffffff8108ab80: get_ins_reg_width (STB_LOCAL)
ffffffff8108b2bf-ffffffff8108b2d2: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
unsigned int get_ins_reg_width(long unsigned int ins_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:148
Inline: False
Direct callers:
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_imm_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
  - arch/x86/mm/pf_in.c:get_ins_reg_val
```
**Symbols:**

```
ffffffff8108cdd0-ffffffff8108ce80: get_ins_reg_width (STB_LOCAL)
ffffffff8108d5bf-ffffffff8108d5d2: get_ins_reg_width.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
