# Function: <code>__dump_skip</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813bf9e2)
Location: fs/coredump.c:869
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
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
In fs/coredump.c (ffffffff8140f812)
Location: fs/coredump.c:876
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
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
In fs/coredump.c (ffffffff814854de)
Location: fs/coredump.c:815
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dump_skip(struct coredump_params *cprm, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81518a80)
Location: fs/coredump.c:821
Inline: False
Direct callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81518a80-ffffffff81518ba2: __dump_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dump_skip(struct coredump_params *cprm, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81550380)
Location: fs/coredump.c:823
Inline: False
Direct callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81550380-ffffffff815504a2: __dump_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dump_skip(struct coredump_params *cprm, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81586210)
Location: fs/coredump.c:823
Inline: False
Direct callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81586210-ffffffff81586332: __dump_skip (STB_LOCAL)
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
