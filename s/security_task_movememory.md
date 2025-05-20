# Function: <code>security_task_movememory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e790)
Location: security/security.c:982
Inline: False
Direct callers:
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/migrate.c:SyS_move_pages
```
**Symbols:**

```
ffffffff8133e790-ffffffff8133e7d3: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373da0)
Location: security/security.c:1006
Inline: False
Direct callers:
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/migrate.c:SyS_move_pages
```
**Symbols:**

```
ffffffff81373da0-ffffffff81373de3: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a6d0)
Location: security/security.c:1027
Inline: False
Direct callers:
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
```
**Symbols:**

```
ffffffff8138a6d0-ffffffff8138a713: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139fc20)
Location: security/security.c:1670
Inline: False
Direct callers:
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
```
**Symbols:**

```
ffffffff8139fc20-ffffffff8139fc63: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5860)
Location: security/security.c:1632
Inline: False
Direct callers:
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
```
**Symbols:**

```
ffffffff813c5860-ffffffff813c58a9: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5850)
Location: security/security.c:1136
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff813f5850-ffffffff813f588a: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410e80)
Location: security/security.c:1744
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81410e80-ffffffff81410eba: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e6b0)
Location: security/security.c:1763
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff8143e6b0-ffffffff8143e6f1: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814580c0)
Location: security/security.c:1802
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff814580c0-ffffffff814580fa: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aaf50)
Location: security/security.c:1998
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff814aaf50-ffffffff814aaf8a: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8550)
Location: security/security.c:2015
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff814c8550-ffffffff814c858a: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ceb90)
Location: security/security.c:2078
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff814ceb90-ffffffff814cebca: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527850)
Location: security/security.c:2086
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff81527850-ffffffff8152788a: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc710)
Location: security/security.c:2092
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff815bc710-ffffffff815bc75d: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668790)
Location: security/security.c:2144
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff81668790-ffffffff816687dd: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0de0)
Location: security/security.c:3534
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff816a0de0-ffffffff816a0e2d: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd7b0)
Location: security/security.c:3593
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff816dd7b0-ffffffff816dd7fd: security_task_movememory (STB_GLOBAL)
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
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543e98)
Location: security/security.c:1802
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffff800010543e98-ffff800010543ee8: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9dec)
Location: security/security.c:1802
Inline: False
```
**Symbols:**

```
c06f9dec-c06f9e40: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000698700)
Location: security/security.c:1802
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
c000000000698700-c0000000006987a8: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a01ac)
Location: security/security.c:1802
Inline: False
```
**Symbols:**

```
ffffffe0003a01ac-ffffffe0003a01e8: security_task_movememory (STB_GLOBAL)
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
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814506a0)
Location: security/security.c:1802
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff814506a0-ffffffff814506da: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814410f0)
Location: security/security.c:1802
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff814410f0-ffffffff8144112a: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c740)
Location: security/security.c:1802
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff8144c740-ffffffff8144c77a: security_task_movememory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_movememory(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463b10)
Location: security/security.c:1802
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81463b10-ffffffff81463b4a: security_task_movememory (STB_GLOBAL)
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
