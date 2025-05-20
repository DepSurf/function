# Function: <code>__dump_emit</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __dump_emit(struct coredump_params *cprm, const void *addr, int nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813bfb09)
Location: fs/coredump.c:848
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
Direct callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff813bf0b0-ffffffff813bf14f: __dump_emit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __dump_emit(struct coredump_params *cprm, const void *addr, int nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8140f939)
Location: fs/coredump.c:855
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
Direct callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff8140eee0-ffffffff8140ef7f: __dump_emit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __dump_emit(struct coredump_params *cprm, const void *addr, int nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff814855e0)
Location: fs/coredump.c:794
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
Direct callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:dump_emit
```
**Symbols:**

```
ffffffff81484620-ffffffff814846cb: __dump_emit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __dump_emit(struct coredump_params *cprm, const void *addr, int nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81518c06)
Location: fs/coredump.c:800
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:__dump_skip
Direct callers:
  - fs/coredump.c:__dump_skip
```
**Symbols:**

```
ffffffff81517b10-ffffffff81517bbb: __dump_emit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __dump_emit(struct coredump_params *cprm, const void *addr, int nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81550506)
Location: fs/coredump.c:802
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:__dump_skip
Direct callers:
  - fs/coredump.c:__dump_skip
```
**Symbols:**

```
ffffffff8154f400-ffffffff8154f4ab: __dump_emit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __dump_emit(struct coredump_params *cprm, const void *addr, int nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81586396)
Location: fs/coredump.c:802
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:__dump_skip
Direct callers:
  - fs/coredump.c:__dump_skip
```
**Symbols:**

```
ffffffff81585240-ffffffff815852eb: __dump_emit (STB_LOCAL)
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
