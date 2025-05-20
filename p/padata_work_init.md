# Function: <code>padata_work_init</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8124a1ca)
Location: kernel/padata.c:99
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
  - kernel/padata.c:padata_do_multithreaded
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
In kernel/padata.c (ffffffff8125485a)
Location: kernel/padata.c:99
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
  - kernel/padata.c:padata_do_multithreaded
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
In kernel/padata.c (ffffffff81258dfb)
Location: kernel/padata.c:99
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
  - kernel/padata.c:padata_do_multithreaded
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
In kernel/padata.c (ffffffff81294a67)
Location: kernel/padata.c:86
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
  - kernel/padata.c:padata_do_multithreaded
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
In kernel/padata.c (ffffffff812ea478)
Location: kernel/padata.c:86
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
  - kernel/padata.c:padata_do_multithreaded
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void padata_work_init(struct padata_work *pw, work_func_t work_fn, void *data, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff820c1ff0)
Location: kernel/padata.c:94
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
  - kernel/padata.c:padata_do_multithreaded
```
**Symbols:**

```
ffffffff820c1ff0-ffffffff820c202a: padata_work_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void padata_work_init(struct padata_work *pw, work_func_t work_fn, void *data, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff82145d20)
Location: kernel/padata.c:94
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
  - kernel/padata.c:padata_do_multithreaded
```
**Symbols:**

```
ffffffff82145d20-ffffffff82145d5a: padata_work_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void padata_work_init(struct padata_work *pw, work_func_t work_fn, void *data, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff82228440)
Location: kernel/padata.c:94
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
  - kernel/padata.c:padata_do_multithreaded
```
**Symbols:**

```
ffffffff82228440-ffffffff8222847a: padata_work_init (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
