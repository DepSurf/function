# Function: <code>padata_free_pd</code>

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
In kernel/padata.c (ffffffff81189fcd)
Location: kernel/padata.c:449
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_sysfs_release
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
In kernel/padata.c (ffffffff8119c8eb)
Location: kernel/padata.c:449
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811abbb0)
Location: kernel/padata.c:446
Inline: False
Direct callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff811abbb0-ffffffff811abbec: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811b3010)
Location: kernel/padata.c:442
Inline: False
Direct callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff811b3010-ffffffff811b304c: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811c6c60)
Location: kernel/padata.c:507
Inline: False
Direct callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff811c6c60-ffffffff811c6c9c: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811e6fd0)
Location: kernel/padata.c:508
Inline: False
Direct callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff811e6fd0-ffffffff811e700c: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811f7c00)
Location: kernel/padata.c:508
Inline: False
Direct callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff811f7c00-ffffffff811f7c3c: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8120fa70)
Location: kernel/padata.c:520
Inline: False
Direct callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff8120fa70-ffffffff8120fab1: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8121d0f0)
Location: kernel/padata.c:476
Inline: False
Direct callers:
  - kernel/padata.c:padata_free_shell
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
**Symbols:**

```
ffffffff8121d0f0-ffffffff8121d131: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81249b7e)
Location: kernel/padata.c:640
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
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
In kernel/padata.c (ffffffff81253dda)
Location: kernel/padata.c:615
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
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
In kernel/padata.c (ffffffff8125846a)
Location: kernel/padata.c:615
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
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
In kernel/padata.c (ffffffff81294073)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
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
In kernel/padata.c (ffffffff812ea0a7)
Location: kernel/padata.c:602
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
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
In kernel/padata.c (ffffffff81353f67)
Location: kernel/padata.c:615
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
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
In kernel/padata.c (ffffffff81385167)
Location: kernel/padata.c:615
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
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
In kernel/padata.c (ffffffff813ae4d7)
Location: kernel/padata.c:615
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
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
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffff8000102a8cb8)
Location: kernel/padata.c:476
Inline: False
Direct callers:
  - kernel/padata.c:padata_free_shell
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
**Symbols:**

```
ffff8000102a8cb8-ffff8000102a8cf4: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c04d7d7c)
Location: kernel/padata.c:476
Inline: False
Direct callers:
  - kernel/padata.c:padata_free_shell
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
**Symbols:**

```
c04d7d7c-c04d7db0: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c00000000035cc60)
Location: kernel/padata.c:476
Inline: False
Direct callers:
  - kernel/padata.c:padata_free_shell
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
**Symbols:**

```
c00000000035cc60-c00000000035ccbc: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffe0001d232e)
Location: kernel/padata.c:476
Inline: False
Direct callers:
  - kernel/padata.c:padata_free_shell
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_serial_worker
```
**Symbols:**

```
ffffffe0001d232e-ffffffe0001d236c: padata_free_pd (STB_LOCAL)
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
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81215740)
Location: kernel/padata.c:476
Inline: False
Direct callers:
  - kernel/padata.c:padata_free_shell
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
**Symbols:**

```
ffffffff81215740-ffffffff81215781: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812084a0)
Location: kernel/padata.c:476
Inline: False
Direct callers:
  - kernel/padata.c:padata_free_shell
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
**Symbols:**

```
ffffffff812084a0-ffffffff812084e1: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812134e0)
Location: kernel/padata.c:476
Inline: False
Direct callers:
  - kernel/padata.c:padata_free_shell
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
**Symbols:**

```
ffffffff812134e0-ffffffff81213521: padata_free_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81222800)
Location: kernel/padata.c:476
Inline: False
Direct callers:
  - kernel/padata.c:padata_free_shell
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
**Symbols:**

```
ffffffff81222800-ffffffff81222841: padata_free_pd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
