# Function: <code>lookup_undo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81327500)
Location: ipc/sem.c:1663
Inline: True
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff81327500-ffffffff81327568: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135c030)
Location: ipc/sem.c:1661
Inline: True
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff8135c030-ffffffff8135c098: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813726d0)
Location: ipc/sem.c:1652
Inline: True
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff813726d0-ffffffff81372738: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81385ac0)
Location: ipc/sem.c:1665
Inline: True
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff81385ac0-ffffffff81385b28: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813aa670)
Location: ipc/sem.c:1758
Inline: True
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff813aa670-ffffffff813aa6d8: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813d9520)
Location: ipc/sem.c:1833
Inline: True
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff813d9520-ffffffff813d9588: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f3a40)
Location: ipc/sem.c:1840
Inline: True
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff813f3a40-ffffffff813f3aad: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8141fe90)
Location: ipc/sem.c:1862
Inline: True
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff8141fe90-ffffffff8141fef8: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81439c90)
Location: ipc/sem.c:1863
Inline: True
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff81439c90-ffffffff81439cf8: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81489d10)
Location: ipc/sem.c:1879
Inline: False
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff81489d10-ffffffff81489d78: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a7350)
Location: ipc/sem.c:1878
Inline: False
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff814a7350-ffffffff814a73b8: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814ad280)
Location: ipc/sem.c:1880
Inline: False
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff814ad280-ffffffff814ad2e8: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81505770)
Location: ipc/sem.c:1883
Inline: False
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff81505770-ffffffff815057d8: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81597200)
Location: ipc/sem.c:1881
Inline: False
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff81597200-ffffffff81597280: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816402b0)
Location: ipc/sem.c:1881
Inline: False
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff816402b0-ffffffff81640330: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816787d0)
Location: ipc/sem.c:1881
Inline: False
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff816787d0-ffffffff81678850: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b4bc0)
Location: ipc/sem.c:1881
Inline: False
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff816b4bc0-ffffffff816b4c40: lookup_undo (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff8000105215b0)
Location: ipc/sem.c:1863
Inline: True
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffff8000105215b0-ffff800010521650: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dc5c0)
Location: ipc/sem.c:1863
Inline: True
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
c06dc5c0-c06dc65c: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066a810)
Location: ipc/sem.c:1863
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
c00000000066a810-c00000000066a8c8: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe000387750)
Location: ipc/sem.c:1863
Inline: True
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffe000387750-ffffffe0003877ca: lookup_undo (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81432270)
Location: ipc/sem.c:1863
Inline: True
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff81432270-ffffffff814322d8: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81422cf0)
Location: ipc/sem.c:1863
Inline: True
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff81422cf0-ffffffff81422d58: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142e410)
Location: ipc/sem.c:1863
Inline: True
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff8142e410-ffffffff8142e478: lookup_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct sem_undo *lookup_undo(struct sem_undo_list *ulp, int semid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81445770)
Location: ipc/sem.c:1863
Inline: True
Direct callers:
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
```
**Symbols:**

```
ffffffff81445770-ffffffff814457d8: lookup_undo (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
