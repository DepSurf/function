# Function: <code>pti_clone_user_shared</code>

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
Location: arch/x86/mm/pti.c:329
Inline: True
Inline callers:
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
Location: arch/x86/mm/pti.c:381
Inline: True
Inline callers:
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
Location: arch/x86/mm/pti.c:440
Inline: True
Inline callers:
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
Location: arch/x86/mm/pti.c:434
Inline: True
Inline callers:
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
Location: arch/x86/mm/pti.c:436
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pti_clone_user_shared();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff82ce80d7)
Location: arch/x86/mm/pti.c:436
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff82ce80d7-ffffffff82ce81c8: pti_clone_user_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pti_clone_user_shared();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff82fd5af6)
Location: arch/x86/mm/pti.c:435
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff82fd5af6-ffffffff82fd5be7: pti_clone_user_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff831e0758)
Location: arch/x86/mm/pti.c:435
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff832c3e20)
Location: arch/x86/mm/pti.c:435
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8347673e)
Location: arch/x86/mm/pti.c:435
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pti_clone_user_shared();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff83e9f510)
Location: arch/x86/mm/pti.c:435
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff83e9f510-ffffffff83e9f630: pti_clone_user_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pti_clone_user_shared();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff836c3690)
Location: arch/x86/mm/pti.c:435
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff836c3690-ffffffff836c37ab: pti_clone_user_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pti_clone_user_shared();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff838f4330)
Location: arch/x86/mm/pti.c:435
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff838f4330-ffffffff838f444b: pti_clone_user_shared (STB_LOCAL)
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
Location: arch/x86/mm/pti.c:436
Inline: True
Inline callers:
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
Location: arch/x86/mm/pti.c:436
Inline: True
Inline callers:
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
Location: arch/x86/mm/pti.c:436
Inline: True
Inline callers:
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
Location: arch/x86/mm/pti.c:436
Inline: True
Inline callers:
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
