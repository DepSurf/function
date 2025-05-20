# Function: <code>secretmem_active</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool secretmem_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff813668a0)
Location: mm/secretmem.c:45
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff813668a0-ffffffff813668b6: secretmem_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool secretmem_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff813e3c20)
Location: mm/secretmem.c:45
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff813e3c20-ffffffff813e3c3a: secretmem_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool secretmem_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff8146b600)
Location: mm/secretmem.c:45
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff8146b600-ffffffff8146b61a: secretmem_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool secretmem_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff814a0400)
Location: mm/secretmem.c:45
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume_initcall
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff814a0400-ffffffff814a041a: secretmem_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool secretmem_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff814cfa70)
Location: mm/secretmem.c:45
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume_initcall
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff814cfa70-ffffffff814cfa8a: secretmem_active (STB_GLOBAL)
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
