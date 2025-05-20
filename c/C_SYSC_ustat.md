# Function: <code>C_SYSC_ustat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263ce0)
Location: fs/compat.c:334
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_ustat
```
**Symbols:**

```
ffffffff81263ce0-ffffffff81263d96: C_SYSC_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128fe70)
Location: fs/compat.c:334
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_ustat
```
**Symbols:**

```
ffffffff8128fe70-ffffffff8128ff25: C_SYSC_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4eb0)
Location: fs/compat.c:320
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_ustat
```
**Symbols:**

```
ffffffff812a4eb0-ffffffff812a4f65: C_SYSC_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128ac80)
Location: fs/statfs.c:370
Inline: False
Direct callers:
  - fs/statfs.c:compat_SyS_ustat
```
**Symbols:**

```
ffffffff8128ac80-ffffffff8128ad35: C_SYSC_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad280)
Location: fs/statfs.c:371
Inline: False
Direct callers:
  - fs/statfs.c:compat_SyS_ustat
```
**Symbols:**

```
ffffffff812ad280-ffffffff812ad335: C_SYSC_ustat (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
