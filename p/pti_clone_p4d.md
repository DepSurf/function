# Function: <code>pti_clone_p4d</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff826c56f6)
Location: arch/x86/mm/pti.c:315
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff826ef83c)
Location: arch/x86/mm/pti.c:364
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828a6530)
Location: arch/x86/mm/pti.c:422
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828beb68)
Location: arch/x86/mm/pti.c:416
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828c500a)
Location: arch/x86/mm/pti.c:418
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff82ce808c)
Location: arch/x86/mm/pti.c:418
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
**Symbols:**

```
ffffffff82ce808c-ffffffff82ce80d7: pti_clone_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff82fd5aab)
Location: arch/x86/mm/pti.c:417
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
**Symbols:**

```
ffffffff82fd5aab-ffffffff82fd5af6: pti_clone_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff831e0545)
Location: arch/x86/mm/pti.c:417
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff831e0545-ffffffff831e0590: pti_clone_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff832c3c13)
Location: arch/x86/mm/pti.c:417
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff832c3c13-ffffffff832c3c54: pti_clone_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8347650f)
Location: arch/x86/mm/pti.c:417
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8347650f-ffffffff8347655b: pti_clone_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff83e9f470)
Location: arch/x86/mm/pti.c:417
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
**Symbols:**

```
ffffffff83e9f470-ffffffff83e9f4f5: pti_clone_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff836c35f0)
Location: arch/x86/mm/pti.c:417
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
**Symbols:**

```
ffffffff836c35f0-ffffffff836c3675: pti_clone_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff838f4290)
Location: arch/x86/mm/pti.c:417
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
**Symbols:**

```
ffffffff838f4290-ffffffff838f4315: pti_clone_p4d (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff828affa2)
Location: arch/x86/mm/pti.c:418
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828a8194)
Location: arch/x86/mm/pti.c:418
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828c2ea1)
Location: arch/x86/mm/pti.c:418
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff828c602a)
Location: arch/x86/mm/pti.c:418
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
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
