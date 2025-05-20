# Function: <code>madvise_willneed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811d190a)
Location: mm/madvise.c:220
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811ef389)
Location: mm/madvise.c:224
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811ffd09)
Location: mm/madvise.c:224
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int madvise_willneed(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81209ec0)
Location: mm/madvise.c:261
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff81209ec0-ffffffff8120a038: madvise_willneed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int madvise_willneed(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812230b0)
Location: mm/madvise.c:273
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff812230b0-ffffffff81223248: madvise_willneed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int madvise_willneed(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81244c50)
Location: mm/madvise.c:273
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81244c50-ffffffff81244e03: madvise_willneed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int madvise_willneed(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812592a0)
Location: mm/madvise.c:273
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff812592a0-ffffffff81259452: madvise_willneed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int madvise_willneed(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81274ad0)
Location: mm/madvise.c:273
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81274ad0-ffffffff81274c80: madvise_willneed (STB_LOCAL)
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
In mm/madvise.c (ffffffff81283c23)
Location: mm/madvise.c:253
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int madvise_willneed(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812b6090)
Location: mm/madvise.c:254
Inline: False
```
**Symbols:**

```
ffffffff812b6090-ffffffff812b6248: madvise_willneed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c12f9)
Location: mm/madvise.c:258
Inline: True
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
In mm/madvise.c (ffffffff812c80db)
Location: mm/madvise.c:258
Inline: True
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
In mm/madvise.c (ffffffff8130d0bc)
Location: mm/madvise.c:260
Inline: True
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
In mm/madvise.c (ffffffff8137854f)
Location: mm/madvise.c:275
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f5cb9)
Location: mm/madvise.c:274
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81428b90)
Location: mm/madvise.c:280
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff814623c0)
Location: mm/madvise.c:261
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffff80001031e158)
Location: mm/madvise.c:253
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c0538254)
Location: mm/madvise.c:253
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c0000000003f2540)
Location: mm/madvise.c:253
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffe000221288)
Location: mm/madvise.c:253
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
</details>
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
In mm/madvise.c (ffffffff8127c273)
Location: mm/madvise.c:253
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff8126e123)
Location: mm/madvise.c:253
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff8127a013)
Location: mm/madvise.c:253
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff81289bf3)
Location: mm/madvise.c:253
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
