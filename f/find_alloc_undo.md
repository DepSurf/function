# Function: <code>find_alloc_undo</code>

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
In ipc/sem.c (ffffffff81328368)
Location: ipc/sem.c:1688
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
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
In ipc/sem.c (ffffffff8135d000)
Location: ipc/sem.c:1686
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
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
In ipc/sem.c (ffffffff813736ea)
Location: ipc/sem.c:1677
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81386cfa)
Location: ipc/sem.c:1690
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
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
In ipc/sem.c (ffffffff813ab59d)
Location: ipc/sem.c:1783
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
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
In ipc/sem.c (ffffffff813dbbdb)
Location: ipc/sem.c:1858
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
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
In ipc/sem.c (ffffffff813f6254)
Location: ipc/sem.c:1865
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81422040)
Location: ipc/sem.c:1887
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81422040-ffffffff81422419: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143be00)
Location: ipc/sem.c:1888
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8143be00-ffffffff8143c1d9: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148c530)
Location: ipc/sem.c:1904
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8148c530-ffffffff8148c90c: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a9b60)
Location: ipc/sem.c:1903
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff814a9b60-ffffffff814a9f6a: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814afe40)
Location: ipc/sem.c:1905
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff814afe40-ffffffff814b0247: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1908
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff81508930-ffffffff81508d54: find_alloc_undo (STB_LOCAL)
ffffffff81cd2b5e-ffffffff81cd2b79: find_alloc_undo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1906
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff81599520-ffffffff81599937: find_alloc_undo (STB_LOCAL)
ffffffff81e85c6a-ffffffff81e85c85: find_alloc_undo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1906
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff816427a0-ffffffff81642bb7: find_alloc_undo (STB_LOCAL)
ffffffff82072de3-ffffffff82072dfe: find_alloc_undo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1906
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff8167ad30-ffffffff8167b141: find_alloc_undo (STB_LOCAL)
ffffffff820f2a37-ffffffff820f2a52: find_alloc_undo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1906
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff816b70d0-ffffffff816b74f6: find_alloc_undo (STB_LOCAL)
ffffffff821cfce7-ffffffff821cfd02: find_alloc_undo.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010523c68)
Location: ipc/sem.c:1888
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffff800010523c68-ffff800010524034: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dea48)
Location: ipc/sem.c:1888
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
c06dea48-c06dedc4: find_alloc_undo (STB_LOCAL)
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
In ipc/sem.c (c00000000066e740)
Location: ipc/sem.c:1888
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe000388b10)
Location: ipc/sem.c:1888
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffe000388b10-ffffffe000388e86: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814343e0)
Location: ipc/sem.c:1888
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff814343e0-ffffffff814347b9: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81424e60)
Location: ipc/sem.c:1888
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81424e60-ffffffff81425239: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81430580)
Location: ipc/sem.c:1888
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81430580-ffffffff81430959: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sem_undo *find_alloc_undo(struct ipc_namespace *ns, int semid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81446ba0)
Location: ipc/sem.c:1888
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81446ba0-ffffffff81446fa8: find_alloc_undo (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
