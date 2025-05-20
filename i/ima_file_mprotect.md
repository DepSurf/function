# Function: <code>ima_file_mprotect</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_file_mprotect(struct vm_area_struct *vma, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81515fa0)
Location: security/integrity/ima/ima_main.c:408
Inline: False
Direct callers:
  - security/security.c:security_file_mprotect
```
**Symbols:**

```
ffffffff81515fa0-ffffffff815160e6: ima_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_file_mprotect(struct vm_area_struct *vma, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81533070)
Location: security/integrity/ima/ima_main.c:414
Inline: False
Direct callers:
  - security/security.c:security_file_mprotect
```
**Symbols:**

```
ffffffff81533070-ffffffff815331c3: ima_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_file_mprotect(struct vm_area_struct *vma, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8153b530)
Location: security/integrity/ima/ima_main.c:414
Inline: False
Direct callers:
  - security/security.c:security_file_mprotect
```
**Symbols:**

```
ffffffff8153b530-ffffffff8153b6a8: ima_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_file_mprotect(struct vm_area_struct *vma, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81599fb0)
Location: security/integrity/ima/ima_main.c:431
Inline: False
Direct callers:
  - security/security.c:security_file_mprotect
```
**Symbols:**

```
ffffffff81599fb0-ffffffff8159a12a: ima_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_file_mprotect(struct vm_area_struct *vma, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8163ebf0)
Location: security/integrity/ima/ima_main.c:433
Inline: False
Direct callers:
  - security/security.c:security_file_mprotect
```
**Symbols:**

```
ffffffff8163ebf0-ffffffff8163edd0: ima_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_file_mprotect(struct vm_area_struct *vma, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f68a0)
Location: security/integrity/ima/ima_main.c:438
Inline: False
Direct callers:
  - security/security.c:security_file_mprotect
```
**Symbols:**

```
ffffffff816f68a0-ffffffff816f6a7e: ima_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_file_mprotect(struct vm_area_struct *vma, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81730ab0)
Location: security/integrity/ima/ima_main.c:454
Inline: False
Direct callers:
  - security/security.c:security_file_mprotect
```
**Symbols:**

```
ffffffff81730ab0-ffffffff81730d00: ima_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_file_mprotect(struct vm_area_struct *vma, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81771540)
Location: security/integrity/ima/ima_main.c:468
Inline: False
Direct callers:
  - security/security.c:security_file_mprotect
```
**Symbols:**

```
ffffffff81771540-ffffffff8177178e: ima_file_mprotect (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
