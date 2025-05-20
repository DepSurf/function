# Function: <code>flag_nproc_exceeded</code>

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
void flag_nproc_exceeded(struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ced00)
Location: kernel/sys.c:480
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff810ced00-ffffffff810ced7d: flag_nproc_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flag_nproc_exceeded(struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e7520)
Location: kernel/sys.c:487
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff810e7520-ffffffff810e75b5: flag_nproc_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flag_nproc_exceeded(struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81108170)
Location: kernel/sys.c:488
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff81108170-ffffffff81108202: flag_nproc_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flag_nproc_exceeded(struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81114480)
Location: kernel/sys.c:495
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff81114480-ffffffff81114512: flag_nproc_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flag_nproc_exceeded(struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111de70)
Location: kernel/sys.c:495
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff8111de70-ffffffff8111df02: flag_nproc_exceeded (STB_LOCAL)
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
